# Contributing to Package Broker

Every repository in this organization follows the Code of Conduct in this repository. A repository's own `CONTRIBUTING.md` and `SECURITY.md` take precedence over the files here when it has them.

## Package Broker 2.0

The [broker](https://github.com/package-broker/broker) repository is the 2.0 codebase. Its [CONTRIBUTING.md](https://github.com/package-broker/broker/blob/main/CONTRIBUTING.md) covers local setup for both runtimes (Miniflare needs no Cloudflare account), the checks a pull request must pass, and where architecture decisions live. In short:

- Open an issue first for anything beyond a small fix.
- Run `pnpm check` before you open a pull request.
- Sign off every commit with `git commit -s`. Contributions are accepted under the repository licence (AGPL-3.0-only) and the [Developer Certificate of Origin](https://developercertificate.org/).
- Pull request titles follow [Conventional Commits](https://www.conventionalcommits.org/) with the package directory as scope. Pull requests target `main` and are squash-merged.

## Package Broker 1.x and other repositories

The [server](https://github.com/package-broker/server) repository (1.x) accepts security fixes only. For the other repositories, open a pull request against `main` and describe the problem and the approach; where a repository has its own `CONTRIBUTING.md`, it applies.

## Reporting bugs and requesting features

Use the issue forms of the repository concerned. Do not report security problems in public issues; follow [SECURITY.md](SECURITY.md).
