# Chronos — Releases

This repository hosts **release binaries only** for Chronos, a Nonlinear
Delay Engine audio plugin (Standalone, VST3, and AU on macOS).

Source code is closed and lives in a private repository. Nothing here is
built from source committed to this repo: the [release workflow](.github/workflows/release.yml)
is dispatched by the private repo's CI, checks out the private source into
an ephemeral runner workspace at build time, builds it, and publishes only
the resulting binaries here as GitHub Releases. No source code is ever
committed or pushed to this repository.

See the [Releases](../../releases) page for downloads.
