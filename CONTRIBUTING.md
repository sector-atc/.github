# Contributing to SECTOR

Discuss substantial changes in the main repository first. Use focused pull requests with a problem statement, relevant issue, verification steps, and limitations. Distinguish implemented behavior from design proposals.

Do not submit code or datasets without publication rights. Record dependency and data provenance. Do not add a license or import third-party code until the maintainer resolves the project license and compatibility. No CLA or license grant is established by this document.

For the main monorepo, run `pnpm --dir apps/desktop typecheck`, `pnpm build:desktop`, `cargo test --workspace`, and `cargo fmt --all -- --check`. Companion and renderer modules are planned.
