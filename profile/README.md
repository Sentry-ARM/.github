# Sentry port for arm64 architecture

## [Sentry](https://github.com/getsentry) fork that fully supports running on arm64 architecture (Apple M-series, Ampere Altra, AWS Graviton, etc.).

> **This build is not intended to be run in production and no support is provided.** It may perform worse than the official version and may fail at any time.

Upstream tracking issue: https://github.com/getsentry/self-hosted/issues/1585

## How to use

1. Clone the [self-hosted](https://github.com/Sentry-ARM/self-hosted) repo.
2. Checkout a version you want to install suffixed by `-arm64`, e.g. `25.1.0-arm64`. You can also checkout the branch `arm64` and update it when necessary.
3. Run `sudo ./install.sh`.
