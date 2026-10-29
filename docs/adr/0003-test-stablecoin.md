# ADR-0003: Own mock ERC-20 as the test stablecoin

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

Loans are denominated in a stablecoin on Polygon Amoy. Public testnet faucets for existing test stablecoins have rate limits, and a live demo that waits on a faucet can fail on the day. Mainnet is out of scope (TC-01).

## Decision

LatiFi deploys its own mock ERC-20 token with 6 decimals, matching the decimals of the stablecoins it stands in for. The token has a public mint function with a cap, so any demo wallet can fund itself without a faucet.

The lending contracts take the token address as a constructor argument. They hold no hard-coded token. Phase 3 sets the per-call cap and the per-address cap.

All amounts in the event interface are in base units of this token, so `1000000` is one token.

## Consequences

- Demos do not depend on third-party faucets for the stablecoin. They still need testnet POL for network fees, covered by ADR-0005.
- The token has no real value, and the mint cap stops one wallet from distorting a demo.
- Moving to another token later means passing a different address at deployment, with no contract change.
- The token must never be deployed or listed on a mainnet. The testnet-only guard in `latifi-contracts` CI backs this up.

## Reversibility

Reversible. Swapping the token means redeploying with another constructor argument and updating the address in the API and app configuration.

## Source

ROADMAP decision 7.
