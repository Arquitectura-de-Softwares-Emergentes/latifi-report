# Architecture decision records

This folder holds the decisions that shape LatiFi's implementation. Each record is short, says what was decided and why, and names what it would cost to undo. The Spanish report cites these files.

## Layout

Every record uses the same sections:

- Title, Status, Date and Deciders
- Context: the problem and the facts that matter
- Decision: what the team chose
- Consequences: what changes because of it
- Reversibility: reversible, costly or one-way, with one sentence naming the concrete cost of undoing it
- Source: the decision number in the project roadmap

## Status vocabulary

| Status | Meaning |
|--------|---------|
| Proposed | Written down, with an open point that still needs an answer. |
| Accepted | Agreed by the team and in force. |
| Superseded | Replaced by a later record, which the file links. |

An Accepted record can receive dated amendments at its end. The text above an amendment stays as the historical record, and the amendment says what changed and why. The Status line then names the amendment date, and the index below marks the record as amended.

## Index

| ADR | Title | Status |
|-----|-------|--------|
| [0001](0001-wallet-model-and-sdk-role.md) | Wallet model and the role of the wallet SDK | Accepted |
| [0002](0002-loan-requested-on-chain.md) | Loan requests are on-chain events | Accepted |
| [0003](0003-test-stablecoin.md) | Own mock ERC-20 as the test stablecoin | Accepted |
| [0004](0004-repayment-installment-model.md) | Repayment in equal installments | Accepted (amended 2026-10-30) |
| [0005](0005-gas-funding-for-borrowers.md) | Gas funding for non-crypto borrowers | Accepted |
| [0006](0006-api-hosting.md) | API hosting on the team's Dokploy VPS | Accepted |
