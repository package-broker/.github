<div align="center">
  <img src="https://package.broker/img/logo.svg" alt="Package Broker logo" width="120" height="120">

# Package Broker

Package Broker is a self-hosted, open-source (AGPL-3.0-only) private Composer and npm registry with role-based access control per project. It runs on Cloudflare Workers or your own Node host with Docker.

[package.broker](https://package.broker) · [Quickstart](https://package.broker/docs/getting-started/quickstart-cloudflare) · [Compare](https://package.broker/compare) · [Security](https://package.broker/security)

</div>

Developers and CI install with broker tokens. Marketplace and vendor keys are stored per client project in the broker, encrypted with a master key you hold. Archives installed through the broker are stored by the broker, so deploys keep working when a vendor repository is down.

## Status

2.0 is in development; no tagged release yet. Marketplace sources are built and in final verification. The container image is not published yet: the Docker quickstart builds it from the repository.

To hear about the first release, watch [package-broker/broker](https://github.com/package-broker/broker) with Watch → Custom → Releases, or follow the [releases feed](https://github.com/package-broker/broker/releases.atom).

## Repositories

| Repository | What it is |
|---|---|
| [broker](https://github.com/package-broker/broker) | Package Broker 2.0: runtimes, plugins, web UI and the `pb` CLI |
| [docs](https://github.com/package-broker/docs) | The package.broker website |

PACKAGE.broker 1.x (`server`, `cloudflare-template`, `cloudflare-deploy-action`) is end of life and receives no fixes. The `@package-broker/*` 0.x packages on npm belong to 1.x.

## Getting help

Questions: [GitHub Discussions](https://github.com/package-broker/broker/discussions). Bugs: [issues](https://github.com/package-broker/broker/issues). Security: [package.broker/security](https://package.broker/security) or security@package.broker. Anything else: hi@package.broker.

Maintained by [lbajsarowicz](https://github.com/lbajsarowicz). Contributions are welcome under the Developer Certificate of Origin, see [CONTRIBUTING.md](https://github.com/package-broker/broker/blob/main/CONTRIBUTING.md).
