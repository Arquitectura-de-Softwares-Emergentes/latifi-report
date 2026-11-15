# ADR-0004: Repayment in equal installments

- Status: Accepted, amended on 2026-10-30 (see Amendment 1)
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

The event interface depends on how a borrower repays. With installments, the request event carries an installments count and the repayment event fires once per payment. With a single payment, the count disappears. The report already promises that the app shows "cuotas" in local currency (US-LEND-06, LEND-06), and REP-04 needs graduated signals of late and on-time payments.

Changing this after the Phase 3 deployment on Amoy means redeploying the contracts and rewriting the indexer, the reputation logic and the app screens. The product owner chose the model before any ABI text was written.

## Decision

Decision: installments (user-confirmed 2026-10-29).

The chosen option, copied as it was offered: "N equal installments, N from 1 to 6, one due date each (working default, N = 1 is the single-payment case)".

- `LoanRequested` carries `installments`, a `uint8` from 1 to 6.
- Interest is defined in Amendment 1 at the end of this record. The first version of this record described a rate that was flat over the whole term, and that wording was replaced before any contract was deployed.
- Installment k falls due at `fundedAt + k * termDays * 86400 / N` seconds with integer division, so the last one falls due exactly at `dueDate`. This is the same rule as in `docs/EVENTS.md` in `latifi-contracts`.
- `LoanRepaid(loanId, amountPaid, onTime)` fires once per payment. The loan reaches Repaid when the final payment settles it.

## Consequences

- One interface covers both the single-payment loan (N = 1) and the multi-payment loan, so no second ABI is needed.
- The contract in Phase 3 needs per-installment due-date logic, an overpayment rule and a rounding rule for the remainder. Phase 3 records these in `docs/EVENTS.md`.
- Reputation gets one on-time or late signal per payment instead of one per loan.
- A full repayment demo takes longer than a one-payment demo. Short test terms keep the live demo practical.

## Reversibility

Costly. After the Phase 3 deployment, dropping or changing installments means a new contract deployment and changes in the indexer, the reputation counters and the app.

## Source

ROADMAP decision 5.

## Amendment 1: interest is annual simple interest

Date: 2026-10-30, the day Juan confirmed the decision in the Phase 3 context.

Deciders: Juan Angulo, recorded in the Phase 3 context.

### Why

Phase 3 planning needed one unambiguous unit for `interestRateBps`. The product owner chose annual simple interest, which matches how loans are usually quoted. The original wording, a rate that was flat over the whole term, would have produced different amounts from the same inputs.

### Decision

- `interestRateBps` is an annual rate with simple interest, in basis points of the principal. It is valid from 1 to 5000, which is up to 50 percent a year. It is not compounded.
- The term is 1 to 365 days.
- Total owed = principal + principal * interestRateBps * termDays / 365 / 10000. The two chained divisions equal one floor division, so in integer math the interest is `floor(principal * interestRateBps * termDays / 3650000)`.
- The contract computes the total once, when the lender funds the request, and it never changes afterwards.
- Floor rounding favors the borrower. It loses less than one base unit (0.000001 token) per loan.
- Worked example: principal 100 tokens (100000000 base units), 1000 bps, 30 days. Interest is floor(100000000 * 1000 * 30 / 3650000) = 821917 base units, so the total owed is 100821917. With N = 2 the installments are 50410958 and 50410959.

### Settled in Phase 3

The original record left these details to Phase 3. They are now fixed:

- The last installment absorbs the rounding remainder, as in the example above.
- Paying more than an installment is worth reverts. Overpayment is not accepted.
- A late payment is accepted. The contract emits `LoanRepaid` for it with `onTime` set to false.
- Anyone can mark a loan Defaulted once an installment is more than 7 days overdue. The grace period is fixed in the contract, strictly more than 7 days, and no admin has any power over it.

### What did not change

- N stays between 1 and 6, and installment k falls due by the same formula as before.
- `LoanRepaid` still fires once per payment.
- The wire format is the same. `interestRateBps` stays a `uint16`, so the v0 event ABI is byte for byte unchanged. Only the written meaning of the field changed, in the NatSpec and in [`docs/EVENTS.md`](https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts/blob/develop/docs/EVENTS.md) of `latifi-contracts`.

### Consequences

- The NatSpec of `ILoanEvents` and `docs/EVENTS.md` in `latifi-contracts` say annual simple interest.
- Phase 4 and Phase 5 must show interest with this meaning, so the app and the API display the same amounts the contract enforces.
- The contract rules are written up in `docs/LOANBOOK.md` of `latifi-contracts`.

### Reversibility

Costly. After the Phase 3 deployment on Amoy, changing the meaning of the rate means a new contract deployment and changes in the API and the app.

### Source

Phase 3 context decisions "Interest and request limits" and "Decisions added after research".
