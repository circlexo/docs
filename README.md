# CircleXO Docs

Documentation for **CircleXO v2**: the CircleXO hub and every first-party CircleXO app, rebuilt as
ToGo plugins in one monorepo ([circlexo/apps](https://github.com/circlexo/apps)), with one binary
and one deployment per app.

> **Status:** planning. The v2 plan is being written. Nothing has been ported yet.

## What lives here

| Area | Contents |
|---|---|
| **Architecture** | The v2 target layout, the shared kernel packages and how the hub and apps fit together |
| **The v2 plan** | Decisions, migration order, cutover and rollback per domain, the PgBouncer plan |
| **App-plugin contract** | What every app plugin exports: routes, migrations, manifest, feature-key constants, MCP tools, web routes |
| **Build and deploy** | The per-app build/deploy matrix, generated env and NPM host config, one LXC per product |
| **Apps** | One section per app (hub, Mahaam, Zekra, Orchestra, Moharrik, Hosbah, SeatFor, Nasaq Studio, Health Debug and the business apps) |
| **Third-party App Contract** | The public contract for external developers: manifest, OIDC sign-in, webhooks, the circlexo-go SDK |

## Related

- [circlexo/apps](https://github.com/circlexo/apps): the v2 monorepo (code)
- [circlexo/circlexo](https://github.com/circlexo/circlexo): the current (v1) hub, live at circlexo.com

The earlier GitBook docs (2025) are kept on the `gitbook-2025` branch.
