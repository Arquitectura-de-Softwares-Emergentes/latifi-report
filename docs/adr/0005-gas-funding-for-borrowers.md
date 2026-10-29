# ADR-0005: Gas funding for non-crypto borrowers

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

Every transaction on Polygon Amoy costs a network fee paid in testnet POL. Borrowers are people without crypto experience and they start with an empty wallet. They need that fee to request a loan (ADR-0002) and to repay it, before they can do anything in the app.

## Decision

Two measures cover the fee:

- An admin top-up script sends small amounts of testnet POL to any wallet that needs them.
- A pool of pre-funded demo wallets is kept ready before every demo gate, with a balance check that runs at least 24 hours ahead.

LatiFi does not use a paymaster or account abstraction. They would add contracts, a relayer and new failure modes, and the scope does not call for them.

The app never shows the word gas. It shows a "network fee", with a short plain explanation and, when the wallet balance is too low, a clear message instead of a failed transaction.

The runbook is `docs/DEMO-WALLETS.md` in `latifi-contracts`, written in Phase 1 plan 07. It covers the wallet roster, the top-up commands, the 24-hour check and key rotation.

## Consequences

- Demos work without asking a user to find a faucet.
- Someone on the team has to keep the pool funded. A low pool is the main risk before a demo.
- The keys of the demo wallets hold worthless testnet POL only. They must never hold real value.
- A paymaster remains possible later if the project leaves the testnet, but it is out of scope now.

## Reversibility

Reversible. The top-up script and the pool are operations tooling, so they can be replaced by a paymaster later without changing the event interface.

## Source

ROADMAP decision 8.
