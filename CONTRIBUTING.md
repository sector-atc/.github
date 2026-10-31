# Contributing to SECTOR

Discuss substantial changes in the main repository first. Use focused pull requests with a problem statement, relevant issue, verification steps, and limitations. Distinguish implemented behavior from design proposals.

Do not submit code or datasets without publication rights. Record dependency and data provenance. Original software contributions must be submitted under AGPL-3.0-only. Identify third-party code and check compatibility before importing it. Prose and datasets need separate licensing decisions. No copyright transfer, CLA, or additional relicensing permission is established by this document.

For the main monorepo, run `pnpm --dir apps/desktop typecheck`, `pnpm build:desktop`, `cargo test --workspace`, and `cargo fmt --all -- --check`. Companion and renderer modules are planned.
