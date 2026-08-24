# Governance

Boing Network is an independent Layer 1. This file describes **organization** governance on GitHub. On-chain parameter and upgrade control is specified in the protocol repository ([boing-governance](https://github.com/Boing-Network/boing.network/tree/main/crates/boing-governance), [TECHNICAL-SPECIFICATION.md](https://github.com/Boing-Network/boing.network/blob/main/docs/TECHNICAL-SPECIFICATION.md)).

## Official product surface

The organization publishes four official repositories:

1. **boing.network** — protocol, node, SDK, website
2. **boing.observer** — explorer
3. **boing.express** — wallet
4. **boing.finance** — DeFi

The **.github** repository is metadata only (profile README and default community files).

## Roles

| Role | Responsibility |
|---|---|
| Organization owners | Org settings, billing, teams, pinning, security defaults |
| Core team | Maintain the four official repositories and this profile |
| Contributors | Issues, discussions, and pull requests under the Code of Conduct |

Decisions that change a public API, chain ID, RPC contract, or canonical deploy artifact should land in **boing.network** docs first, then flow to observer, express, and finance per [THREE-CODEBASE-ALIGNMENT.md](https://github.com/Boing-Network/boing.network/blob/main/docs/THREE-CODEBASE-ALIGNMENT.md).

## Decision making

- Day-to-day product changes: maintainers of the owning repository.
- Cross-repo contracts: documented in `boing.network` and mirrored by dependent apps.
- On-chain governance: phased proposal → cooling → execution, as implemented in the protocol.

## Conduct and security

Participation follows [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md). Vulnerabilities follow [SECURITY.md](SECURITY.md).
