# ADR-0001: Wallet model and the role of the wallet SDK

- Status: Accepted
- Date: 2026-10-29
- Deciders: Juan Angulo and the team

## Context

First-time users do not know how to connect an external wallet, so the main flow cannot depend on one. The app has to hold its own key, and LatiFi servers must never see it (TC-02, non-custodial).

The chain uses secp256k1 keys. A spike on an Android 14 emulator (API 34) in GitHub Actions tested two things. Android Keystore rejects secp256k1 outright with `Unsupported EC curve name: secp256k1`. An AES-256-GCM key kept in the Keystore can wrap a web3j secp256k1 private key, unwrap it and still sign correctly, with no plaintext key in app storage. Evidence: `latifi-android/docs/spikes/keystore-secp256k1.md`, run https://github.com/Arquitectura-de-Softwares-Emergentes/latifi-android/actions/runs/40944177984. Verdict: the envelope design works.

The same run reported `insideSecureHardware=false`, because the emulator Keystore is software backed. Hardware protection is not shown yet.

## Decision

- On first launch the app creates a secp256k1 key pair with web3j. Android Keystore holds only an AES-256-GCM wrapping key that cannot be exported. The private key is stored wrapped by that key.
- Recovery uses a BIP-39 recovery phrase, shown once with a plain-language backup step. A wrapped key is bound to one device's Keystore and cannot be restored on a new phone, so the phrase is the only way back. Android backup stays disabled.
- Every signature happens inside the wallet module of the app. LatiFi servers never receive a key or a phrase.
- Reown WalletKit and WalletConnect are an optional path to import or connect a wallet the user already owns. They are not the main flow. Whether to use WalletKit or AppKit stays with the Phase 5 spike.

## Consequences

- Onboarding gains a recovery step, which the UX work in Phase 2 has to make readable for people with no crypto background.
- AUTH-01 is restated in the report as "create a wallet, or import one". The wording in REQUIREMENTS.md is for the product owner to amend.
- AUTH-02 holds, because the signing code never leaves the wallet module.
- The bundled BouncyCastle provider must be registered before any web3j call, since Android ships a stripped `BC` provider. The `-android` web3j artifacts publish no transitive metadata, so `web3j-utils` and BouncyCastle are declared by hand.
- Phase 5 must check the security level of the wrapping key on a real device (`KeyInfo.securityLevel`), because the emulator run proves the logic and not the hardware protection.

## Reversibility

Costly. Phase 5 onboarding, the AUTH-01 wording in the report and the Android security design all follow this model, so changing it after Phase 5 starts means reworking those three.

## Source

ROADMAP decision 1 (resolved by the user on 2026-10-08), with the Keystore spike from Phase 1 plan 04.
