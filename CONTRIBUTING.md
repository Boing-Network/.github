# Contributing to Boing Network

Thanks for wanting to help. Boing Network is four official repositories plus this organization profile. **Open pull requests against the repository that owns the code you are changing.**

## Choose a repository

| Change | Repository |
|---|---|
| Protocol, `boing-node`, crates, `boing-sdk`, website, workers, tutorial scripts, operator docs | [boing.network](https://github.com/Boing-Network/boing.network) — see its [CONTRIBUTING.md](https://github.com/Boing-Network/boing.network/blob/main/CONTRIBUTING.md) |
| Explorer UI, RPC proxy, DEX/QA explorer tools | [boing.observer](https://github.com/Boing-Network/boing.observer) |
| Wallet web app, extension, `window.boing`, RPC gateway worker | [boing.express](https://github.com/Boing-Network/boing.express) |
| DeFi frontend, Workers API, EVM/Solana contracts | [boing.finance](https://github.com/Boing-Network/boing.finance) |
| Organization profile, default community files, discussion templates | this repository ([Boing-Network/.github](https://github.com/Boing-Network/.github)) |

Cross-repo contracts (RPC URLs, chain IDs, wallet/explorer alignment) live in [THREE-CODEBASE-ALIGNMENT.md](https://github.com/Boing-Network/boing.network/blob/main/docs/THREE-CODEBASE-ALIGNMENT.md) and [HANDOFF-DEPENDENT-PROJECTS.md](https://github.com/Boing-Network/boing.network/blob/main/docs/HANDOFF-DEPENDENT-PROJECTS.md).

## Pull requests

- Keep changes focused and match the style of the files you touch.
- Do not commit secrets, `.env` files, or private keys.
- For protocol work: `cargo fmt` / `cargo clippy` as appropriate; `cargo test` for touched crates.
- For `boing-sdk`: `npm run build` and `npm test` after TypeScript changes.
- For app repos: run that repository's lint and test scripts before opening the PR.

## Issues and discussions

- **Bugs and features:** open an issue on the product repository using the issue form.
- **Security:** do not file a public issue. Follow [SECURITY.md](SECURITY.md).
- **Questions and ideas:** [Discussions](https://github.com/Boing-Network/.github/discussions) or [Discord](https://discord.gg/boing).

By participating, you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).
