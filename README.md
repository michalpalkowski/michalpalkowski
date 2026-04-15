# Michał Pałkowski

Rust systems engineer specializing in blockchain infrastructure, zero-knowledge proofs, and trusted execution environments (TEE). I build low-level protocol software — proof systems, state management, on-chain verification — in the Starknet ecosystem.
## Highlights

**[dojoengine/katana](https://github.com/dojoengine/katana)** — High-performance Starknet sequencer (Dojo core infra)
> Enabled ZK provability on forked chain state, allowing sharded game worlds to generate validity proofs. [#473](https://github.com/dojoengine/katana/pull/473)

**[cartridge-gg/solana-verifier](https://github.com/cartridge-gg/solana-verifier)** — STARK proof verification on Solana
> Ported core verification logic from Ethereum/Starknet to Solana — implemented FRI verification, Pedersen hashing, commitment schemes, and proof batching across 18 merged PRs.

**[cartridge-gg/sharding-operator](https://github.com/cartridge-gg/sharding-operator)** — Game state sharding with TEE attestation
> Core contributor (24 merged PRs). Built the settlement pipeline, TEE integration, multi-shard orchestration, Dojo framework integration, and API authentication layer.

## More Contributions

| Project | Area | What I built |
|---|---|---|
| [dojoengine/bonsai-trie](https://github.com/dojoengine/bonsai-trie) | State management | Provable forking — partial Merkle trie and multi-proof extraction for Starknet storage [#3](https://github.com/dojoengine/bonsai-trie/pull/3) |
| [neotheprogramist/sharding_proxy](https://github.com/neotheprogramist/sharding_proxy) | Smart contracts (Cairo) | On-chain sharding protocol — storage commitment verification, access control, shard lifecycle (10 PRs) |
| [amd-sev-snp-attestation-sdk](https://github.com/michalpalkowski/amd-sev-snp-attestation-sdk) | TEE / Hardware security | Extended AMD SEV-SNP attestation SDK with sharding-specific remote attestation flows |
| [swiftness-prover](https://github.com/michalpalkowski/swiftness-prover) | ZK proofs | Contributed FRI and last-layer implementations to a Cairo-VM STARK prover |
| Sybilla (trading platform) | Backend (Rust) | Built matching engine, settlement pipeline, proof generation, and real-time balance system (20+ PRs) |
| [chudkowsky/chessformer](https://github.com/chudkowsky/chessformer) | ML / Python | Transformer + MCTS self-play architecture, GPU training pipeline |

## Own Projects

[**evm-stark-verifier**](https://github.com/michalpalkowski/evm-stark-verifier) — PoC exploring how STARK proving works on EVM. Built from verifier contracts pulled from Ethereum mainnet, with my modifications, deployed to Sepolia. Solidity + Rust tooling.

[**KsefPay**](https://github.com/michalpalkowski/KsefPay) — Polish e-invoice (KSeF) integration in Rust. Full FA3 schema support, multi-tenant auth, Axum web dashboard for small businesses.

## Tech

Rust · Cairo · Solidity · Python · Starknet · Dojo · AMD SEV-SNP · ZK-STARKs · SP1 · Axum · PostgreSQL
