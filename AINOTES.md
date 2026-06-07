# AINOTES.md - AgoraAnon Project

This file is the cloud-safe source of truth for this repository.

> **Local context:** machine paths, the host AINOTES cascade, and local wallet provenance live in `AINOTES.local.md` (gitignored, not in this repo). Read it too when working locally.

## Project Summary

- Repo: `https://github.com/AgoraAnon/AgoraAnon.git`
- Branch: `main`
- Type: docs-only donation/support landing page
- Primary file: `README.md`
- Build/test: none
- Social contact: X/Twitter [@AgoraAnon](https://x.com/AgoraAnon)

## Working Rules

- Changes are normal Markdown edits to `README.md`.
- Do not add a build system unless explicitly requested.
- Donation addresses are sensitive user-provided content; do not invent or alter real addresses without explicit instruction.
- Durable cross-project or system facts go in the host-level AINOTES (see `AINOTES.local.md`), not here.

## Status / Handoff

- **2026-06-03 (Claude Code, Opus):** Donation table in `README.md` **fully populated and live** — committed `bfdde0d`, pushed to `origin/main` (public repo). 11 coins: XMR, WOW, BTC (bech32), LTC (bech32), BCH (CashAddr), ARRR (`zs…` shielded), and one shared `0x` EVM address reused for ETH / BNB / POL / BTC-BEP20 / BCH-BEP20. Removed the DERO, Komodo (KMD), Firo, vARRR rows and consolidated the duplicate BTC/LTC "SegWit" rows.
- Address provenance (where each was generated, for future verification/rotation): WOW from a local Wownero CLI wallet; ARRR from **PirateWallet-Lite**. Wallet paths / host install details are in `AINOTES.local.md`.
- `README.md` is a normal tracked file (gets pushed). This file (`AINOTES.md`) and the `CLAUDE/AGENTS/GEMINI.md` pointers are cloud-safe and tracked; machine-specific notes live in the gitignored `AINOTES.local.md`.
