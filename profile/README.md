# Cloud Architecture

**Secure your Microsoft cloud, properly.**

> 🚧 **Under construction.** An active work in progress: I'm building the baselines, writing the guides, and refining what's already here as I go, so expect it to keep changing.

Hands-on Microsoft 365 and Azure security: the portal steps, the reasoning behind them, and the PowerShell to automate it — every control mapped to CIS, NIST, ISO 27001, NCSC and NIS2. Open, auditable security baselines for each Microsoft licence, free to read and fork. Not a black box you take on trust; a baseline you can check.

### What I'm building

A complete toolkit to **build a Microsoft 365 tenant from scratch and run it for its whole life** — not just harden one that already exists. It's organised as four pillars, each usable on its own or together:

- **Provision** — stand the tenant up from a declarative definition: domains, licensing, users, groups, mailboxes, sites and teams.
- **Configure** — enable and set up every product and feature, from Exchange and Teams through Purview, Defender, Power Platform and Copilot.
- **Secure** — the mature core: around 90 idempotent PowerShell scripts that harden the tenant to the CIS Microsoft 365 Foundations Benchmark, NIST and CISA SCuBA, across a Tier 0–3 licence ladder.
- **Operate** — keep it healthy after go-live: posture reporting, drift detection, and identity and device lifecycle.

Everything runs dry-run first — nothing changes without you asking — reads raw Microsoft Graph, and is built à la carte, so you can run a single product, a single pillar, or the whole thing. Every control carries the standard it satisfies, so you can evidence Cyber Essentials, CIS or SCuBA rather than take my word for it.

### The site

The guides, blog and framework mappings are launching soon at [cloud-architecture.co.uk](https://www.cloud-architecture.co.uk). It's behind a holding page for now while I finish the first wave of content.

### Open source

Public now:

- [iac-cloud-architecture](https://github.com/Cloud-Architecture-UK/iac-cloud-architecture) — Terraform and PowerShell to stand up the Azure hosting for an Astro blog, the same way this site is built.
- [docs-standards](https://github.com/Cloud-Architecture-UK/docs-standards) — how the repositories here are named and run, in one place.

The tenant toolkit is private while I finish and test it; each pillar opens up as it's ready.

I'm [Mark Hughes](https://github.com/markdhughes), a Microsoft-certified solutions consultant and cloud architect. Cloud Architecture is a solo project — I write, test and document everything here myself.
