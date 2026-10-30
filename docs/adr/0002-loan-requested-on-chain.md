# ADR-0002: Loan requests are on-chain events

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

Chapter IV left one point open: whether `LoanRequested` is an on-chain event or a record that lives in the API and reaches the chain only at funding time. The lender feed lists open requests, so where a request lives decides where the feed gets its data.

## Decision

A request is stored on-chain and the contract emits `LoanRequested`. The feed is built only from chain events through the indexer. No loan state lives off-chain, which keeps the contract as the single source of truth (DR-01, TC-05).

The event fields are defined in [docs/EVENTS.md](https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-contracts/blob/develop/docs/EVENTS.md) in `latifi-contracts`: `loanId`, `borrower`, `amount`, `interestRateBps`, `termDays` and `installments`. No event carries a price or an exchange rate.

## Consequences

- The indexer never has to reconcile a request that exists in the database but not on the chain.
- Reputation and the feed read the same source, so they cannot disagree about whether a request exists.
- A borrower pays a network fee to publish a request. ADR-0005 covers how non-crypto borrowers get funds for that fee.
- Cancelling or expiring a request is a contract matter for Phase 3 and needs its own event if it ships.

## Reversibility

Costly. Moving requests off-chain after the Phase 3 deployment on Amoy means redeploying the contracts and rewriting the indexer and the feed.

## Source

ROADMAP decision 6.
