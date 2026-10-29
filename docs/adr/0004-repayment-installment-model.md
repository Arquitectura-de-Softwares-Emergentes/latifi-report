# ADR-0004: Repayment in equal installments

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

The event interface depends on how a borrower repays. With installments, the request event carries an installments count and the repayment event fires once per payment. With a single payment, the count disappears. The report already promises that the app shows "cuotas" in local currency (US-LEND-06, LEND-06), and REP-04 needs graduated signals of late and on-time payments.

Changing this after the Phase 3 deployment on Amoy means redeploying the contracts and rewriting the indexer, the reputation logic and the app screens. The product owner chose the model before any ABI text was written.

## Decision

Decision: installments (user-confirmed 2026-10-29).

The chosen option, copied as it was offered: "N equal installments, N from 1 to 6, one due date each (working default, N = 1 is the single-payment case)".

- `LoanRequested` carries `installments`, a `uint8` from 1 to 6.
- Interest is flat over the whole term, in basis points of the principal. The total owed is the principal plus that interest.
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
