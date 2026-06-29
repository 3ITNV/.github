# 3-IT Github

Internal tooling, automation and documentation for 3-IT — Networking, Service Desk tools, Microsoft 365, Intune, Entra ID, Azure and on-premises infrastructure across our managed customer tenants.

Repositories are private by default and organised under four technology pillars. This page is a living index — update it whenever a repo is added, renamed or archived.

## Naming convention

`pillar-category-toolname`, all lowercase, hyphen-separated.

| Pillar | Prefix | Team |
|---|---|---|
| Network | `net-` | `Network` |
| Modern Workplace | `mw-` | `Modern-Workplace` |
| Infrastructure | `infra-` | `Infrastructure` |
| Service Desk | `sd-` | `Service-Desk` |

## Repositories

### 🌐 Network (`net-`)
- [ ] `net-...`

### 💻 Modern Workplace (`mw-`)
- [x] [`mw-m365-reporting`](https://github.com/3ITNV/mw-M365-reporting) — Entra/Intune health & anomaly reporting suite, orchestrated via Azure Automation. Used to fill up m365dashboard.3-it.be

### 🖥️ Infrastructure (`infra-`)
- [ ] `infra-...`

### 🎧 Service Desk (`sd-`)
- [ ] `sd-...`

> Replace the placeholder lines above as repos get created, and tick the box once a repo is live and in regular use.

## How we work

- No mandatory pull-request review — every engineer tests and merges their own changes. PRs stay available for anyone who wants a second opinion on something bigger.
- No secrets, customer data or tenant-specific configuration ever get committed — see each repo's own README for its specific no-secrets policy and setup.
- Repo access is granted per team, not per person — see the table above for which team maps to which pillar.

---
*Questions about access or naming? Ping Tim Pass.*
