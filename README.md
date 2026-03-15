# TestCrux

> Vendored GitHub Actions library for CI pipelines.

Part of [CueCrux](../README.md) — shared CI actions consumed by InfraCrux and sibling repos.

This repository houses vendored GitHub Actions that InfraCrux and sibling repos can consume without fetching
many upstream dependencies individually. Each action lives under `actions/vendor/<name>` and tracks the upstream
commit it was cloned from. Repos reference these actions via `uses: CueCrux/TestCrux/actions/vendor/<name>@main`
(or a pinned commit SHA) while keeping local fallbacks for `act` runs.

## Key Links

- Platform overview: [CueCrux README](../README.md)
- Related repos: [InfraCrux](../InfraCrux/README.md) (primary consumer), [PlanCrux](../PlanCrux/README.md) (CI workflows)
