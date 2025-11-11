# TestCrux Actions Library

This repository houses vendored GitHub Actions that InfraCrux and sibling repos can consume without fetching
many upstream dependencies individually. Each action lives under `actions/vendor/<name>` and tracks the upstream
commit it was cloned from. Repos reference these actions via `uses: CueCrux/TestCrux/actions/vendor/<name>@main`
(or a pinned commit SHA) while keeping local fallbacks for `act` runs.
