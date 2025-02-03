# Sentry port on arm64 architecture

## [Sentry](https://github.com/getsentry) build that fully supports arm64 arch.

> **This build is not intended to be run in production and no support is provided.** It may perform worse than the official version and may fail at any time.

Original tracking issue: https://github.com/getsentry/self-hosted/issues/1585

## How to use

1. Clone [self-hosted](https://github.com/Sentry-ARM/self-hosted) repo.
2. Checkout a version you want to install suffixed by `-arm64`, e.g. `25.1.0-arm64`. You can also checkout the branch `arm64` and update it when necessary.
3. Run `sudo ./install.sh`.
