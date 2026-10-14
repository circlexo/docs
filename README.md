<div align="center">

<img src="assets/logo.svg" alt="CircleXO" width="120" />

# CircleXO Docs

**Documentation for CircleXO, the open-source, AI-native platform for building, composing, deploying and operating products, capabilities and autonomous agents.**

[![CI](https://github.com/circlexo/docs/actions/workflows/ci.yml/badge.svg)](https://github.com/circlexo/docs/actions/workflows/ci.yml)
[![License: AGPL-3.0](https://img.shields.io/badge/license-AGPL--3.0-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/circlexo/docs?style=social)](https://github.com/circlexo/docs/stargazers)

[Website](https://circlexo.com) · [Code](https://github.com/circlexo/apps) · [Discussions](https://github.com/circlexo/docs/discussions) · [Issues](https://github.com/circlexo/docs/issues)

</div>

> **Status:** early. The architecture (v1.1) is agreed and Phase 0 is in progress. These docs
> describe released behaviour only, so most sections are still empty. The design record lives
> next to the code in [circlexo/apps](https://github.com/circlexo/apps).

## What lives here

| Area | Contents |
|---|---|
| **Architecture** | Platform, Products, Capabilities and Agents, and how they compose |
| **Plans and decisions** | Approved decisions, the delivery sequence and, later, per-product migration notes |
| **Contracts** | Platform, product and capability contracts: manifests, entitlements, events, provisioning, MCP tools |
| **Build and deploy** | How each product is built, versioned and deployed independently |
| **Products** | One section per product: Mahaam, Zekra, Orchestra, Moharrik, Hosbah, SeatFor, Nasaq Studio and the business apps |
| **Third-party App Contract** | The public contract for external developers, once it is decided |

## Using the docs

- **Hosted:** [circlexo.com](https://circlexo.com) is the running platform.
- **Self-host or develop:** the code, with a Docker Compose setup and a quick start, is in
  [circlexo/apps](https://github.com/circlexo/apps). That repository includes these docs as a git
  submodule at `docs/`.

## Contributing

Corrections and new pages are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for the
conventions and the DCO sign-off, then look for a
[`good first issue`](https://github.com/circlexo/docs/labels/good%20first%20issue). AI coding
agents should start with [AGENTS.md](AGENTS.md).

## Community

- [GitHub Discussions](https://github.com/circlexo/docs/discussions): questions, ideas, show and tell
- [Issues](https://github.com/circlexo/docs/issues/new/choose): wrong or missing docs
- Security reports: see [SECURITY.md](SECURITY.md)

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Related

- [circlexo/apps](https://github.com/circlexo/apps): the CircleXO code
- [circlexo/circlexo](https://github.com/circlexo/circlexo): the earlier (v1) hub, live at circlexo.com
- [circlexo/circlexo-go](https://github.com/circlexo/circlexo-go): the Go SDK for CircleXO apps

## License

Copyright (C) 2026 Fady Mondy. CircleXO is free software, licensed under the
[GNU Affero General Public License v3.0](LICENSE). Third-party components keep their own licenses.

**Commercial licensing available:** for a license without the AGPL obligations, contact
[info@3x1.io](mailto:info@3x1.io).
