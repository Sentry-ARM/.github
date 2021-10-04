# Sentry-on-ARM64

> **This build is not intended to run in production and no support is provided.** It may preform worse than official x86 version and may fail in any time. However all of the features that were tested personally are functional and working.

## Some of the workarounds that had to be done
1. Official [Clickhouse Docker image](https://hub.docker.com/r/yandex/clickhouse-server/) was replaced with [ARM64 build by lunalabsltd](https://hub.docker.com/r/lunalabsltd/clickhouse-server)
2. Official Confluent images (zookeeper, kafka) were replaced with ARM64 builds [by watershine](https://hub.docker.com/u/watershine)

## Related issues on Github about ARM64 support for Docker images:
1. [ClickHouse](https://github.com/ClickHouse/ClickHouse/issues/22222)
2. [Confluent (e.g. kafka, zookeeper)](https://github.com/confluentinc/common-docker/issues/117)
3. [sentry-cli](https://github.com/getsentry/sentry-cli/issues/908)
4. [Sentry on-premise](https://github.com/getsentry/onpremise/issues/914)
5. [Volta](https://github.com/volta-cli/volta/issues/1006)
