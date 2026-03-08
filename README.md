# Turbin3 Accelerated Builders — Q1 2026

> _"It will become cleaner with time."_ — Devwraithe

A cohort-based intensive program building production-grade programs on Solana. Projects span solo challenges, group collaborations, and weekly homework assignments — covering the full stack of modern Solana development.

---

### [Whitelist Transfer Hook](https://github.com/devwraithe/whitelist-transfer-hook)

A Solana Transfer Hook program that enforces whitelist-based access control on SPL token transfers. Uses the Token-2022 extension interface to intercept transfers and validate sender/receiver eligibility on-chain.

### [Escrow LiteSVM](https://github.com/devwraithe/escrow-litesvm)

A token escrow program developed and tested using [LiteSVM](https://github.com/LiteSVM/litesvm) — a fast, lightweight Solana VM for unit testing. Demonstrates safe atomic token swaps without requiring a full validator.

### [Transfer Hook Vault](https://github.com/devwraithe/magicblock-er-accel) _(Week 1 Group Challenge)_

A collaborative group project combining Transfer Hook mechanics with a vault program. Tokens deposited into the vault are gated by a hook layer, enabling composable access control over locked assets.

### [MagicBlock ER Accel (VRF)]()

Integration with MagicBlock's Ephemeral Rollup infrastructure to implement a Verifiable Random Function (VRF) on Solana. Explores high-throughput, low-latency randomness for on-chain games and probabilistic programs.

### [Escrow TukTuk](https://github.com/devwraithe/escrow-tuktuk)

A reimplementation of the escrow pattern using the TukTuk framework — exploring alternative program execution models and comparing DX and performance against Anchor-based approaches.

### [Solana GPT TukTuk](https://github.com/devwraithe/solana-gpt-tuktuk) _(Week 2 Solo Challenge)_

A solo-built AI-powered assistant that wraps Solana program interactions with a GPT interface via TukTuk. Enables natural language interaction with on-chain programs, bridging LLM tooling with the Solana runtime.

### [Rust Generic Storage](https://github.com/devwraithe/genstore)

A low-level Rust program exploring generic, reusable account storage patterns on Solana — without Anchor abstractions. Focuses on manual account serialization, discriminators, and trait-based design for composable program state.

### [Freya File Compressor](https://github.com/inspi-writer001/freya) _(Group Homework)_

A group homework project implementing file compression utilities in Rust, named after the Freya framework. Explores efficient data encoding and storage strategies relevant to on-chain and off-chain Solana data management.

### [Pinocchio Escrow](https://github.com/devwraithe/accel-pinocchio-escrow)

An escrow program built using [Pinocchio](https://github.com/febo/pinocchio) — a minimal, zero-dependency Solana program framework. Demonstrates how to write lean, highly optimised on-chain logic with full control over CPI and account handling.

### [Pinocchio Fundraiser](https://github.com/devwraithe/pinocchio-fundraiser) _(Week 3 Solo Challenge)_

A solo-built fundraising program written in Pinocchio. Implements contribution tracking, goal thresholds, and refund logic entirely in low-level Rust — no Anchor, no macros, maximum control.

### [Metaplex NFT Staking Core](https://github.com/devwraithe/nft-staking-core)

A full NFT staking protocol built on [Metaplex Core](https://developers.metaplex.com/core). Users stake NFTs into a vault and accrue rewards over time, with on-chain state tracking emission rates, lock periods, and claim logic.

## Program Summary

| Project                   | Type            | Framework        |
| ------------------------- | --------------- | ---------------- |
| Whitelist Transfer Hook   | Solo            | Token-2022       |
| Escrow LiteSVM            | Solo            | Anchor + LiteSVM |
| Transfer Hook Vault       | Group Challenge | Token-2022       |
| MagicBlock ER Accel (VRF) | Solo            | MagicBlock       |
| Escrow TukTuk             | Solo            | TukTuk           |
| Solana GPT TukTuk         | Solo Challenge  | TukTuk + GPT     |
| Rust Generic Storage      | Solo            | Native Rust      |
| Freya File Compressor     | Group Homework  | Freya / Rust     |
| Pinocchio Escrow          | Solo            | Pinocchio        |
| Pinocchio Fundraiser      | Solo Challenge  | Pinocchio        |
| Metaplex NFT Staking Core | Solo            | Metaplex Core    |

---

_Built during the [Turbin3](https://turbin3.com) Accelerated Builders cohort, Q1 2026._
