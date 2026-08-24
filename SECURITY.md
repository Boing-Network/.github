# Security policy

Boing Network treats security as the first pillar. Please report vulnerabilities **privately**. Do not open a public issue, pull request, or discussion for a security-sensitive finding.

## How to report

Use **GitHub Security Advisories** on the repository that contains the affected code:

| Surface | Private advisory |
|---|---|
| Protocol, node, SDK, website, workers | [boing.network advisories](https://github.com/Boing-Network/boing.network/security/advisories/new) |
| Explorer | [boing.observer advisories](https://github.com/Boing-Network/boing.observer/security/advisories/new) |
| Wallet / extension | [boing.express advisories](https://github.com/Boing-Network/boing.express/security/advisories/new) |
| DeFi app / contracts | [boing.finance advisories](https://github.com/Boing-Network/boing.finance/security/advisories/new) |

If you are unsure which repo is affected, report against **boing.network**.

Include enough detail to reproduce the issue: affected component, version or commit, environment, and impact. Maintainers will acknowledge privately and coordinate disclosure.

## Scope

In scope: consensus and execution, RPC, wallet key handling, explorer data integrity, DeFi contracts and Workers, and operational paths that could steal funds, forge state, or take the network down.

Out of scope for this policy: public testnet faucet abuse, issues that require already-compromised local keys, and theoretical findings with no practical path.

## After a report

1. We confirm receipt and triage severity.
2. We work on a fix in private when needed.
3. We disclose through a GitHub security advisory once users can upgrade.

Protocol security posture and contacts: [SECURITY-STANDARDS.md](https://github.com/Boing-Network/boing.network/blob/main/docs/SECURITY-STANDARDS.md). Incident handling for operators: [RUNBOOK.md](https://github.com/Boing-Network/boing.network/blob/main/docs/RUNBOOK.md).

A public bug-bounty program is planned with incentivized testnet; until then, responsible disclosure via advisories is the supported path.
