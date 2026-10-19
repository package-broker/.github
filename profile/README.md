<div align="center">

# Package Broker

**A package registry broker for Composer and npm, self-hosted on Cloudflare Workers or Docker.**

</div>

## What it is

Package Broker 2.0 sits between your projects and the registries they install from. It gives each project its own view of your packages and its own upstream credentials, and puts Composer and npm behind one token policy.

- Per-project isolation by SSO group, with per-project upstream credentials.
- Composer and npm under one token policy.
- Self-hosted on Cloudflare Workers or Docker, licensed under AGPL-3.0.
- OIDC groups mapped to projects, for example from Dex or Cloudflare Access.
- Token hygiene by default: 90-day personal access tokens, read-only single-project CI tokens, and re-authentication before a token is issued.

2.0 is pre-release: no tagged release yet, and the API still changes.

## Repositories

| Repository | Description |
| ---------- | ----------- |
| [**broker**](https://github.com/package-broker/broker) | Package Broker 2.0, in pre-release: no tagged release yet |
| [**server**](https://github.com/package-broker/server) | Package Broker 1.x, security fixes only |
| [**docs**](https://github.com/package-broker/docs) | Documentation website |
| [**cloudflare-deploy-action**](https://github.com/package-broker/cloudflare-deploy-action) | GitHub Action that deploys 1.x to Cloudflare Workers |
| [**cloudflare-template**](https://github.com/package-broker/cloudflare-template) | Template repository for deploying 1.x to Cloudflare Workers |

## Contributing

Contributions to 2.0 are welcome under the Developer Certificate of Origin. Start with the [contributing guidelines](https://github.com/package-broker/broker/blob/main/CONTRIBUTING.md), the [governance notes](https://github.com/package-broker/broker/blob/main/GOVERNANCE.md) and the [Code of Conduct](https://github.com/package-broker/.github/blob/main/CODE_OF_CONDUCT.md). Report vulnerabilities privately, as described in the [security policy](https://github.com/package-broker/.github/blob/main/SECURITY.md).

## Licence

AGPL-3.0, see the [broker licence](https://github.com/package-broker/broker/blob/main/LICENSE).
