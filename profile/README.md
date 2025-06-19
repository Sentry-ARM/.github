# Sentry supports arm64 officially since 25.6.0!

This fork is no longer maintained since the patches for arm64 support were merged in upstream, use [the official self-hosted repo](https://github.com/getsentry/self-hosted).

In case of any issues you can [post them here](https://github.com/getsentry/self-hosted/issues/1585).

Below is the original README before deprecation.

# [Sentry](https://github.com/getsentry) port for arm64 architecture

> **This build is not intended to be run in production and no support is provided.** It may perform worse than the official version and may fail at any time.

Upstream tracking issue: https://github.com/getsentry/self-hosted/issues/1585

## How to use

1. Clone the [self-hosted](https://github.com/Sentry-ARM/self-hosted) repo.
2. Checkout a tag with a version you want to install suffixed by `-arm64`, e.g. `git checkout 25.1.0-arm64`. You can also checkout the `arm64` branch and pull new changes when necessary.
3. Run `sudo ./install.sh`.

> This project is not affiliated with Arm Ltd or Functional Software Inc and has not been endorsed by them. Arm is a registered trademark of Arm Ltd. Sentry is a registered trademark of Functional Software Inc.
