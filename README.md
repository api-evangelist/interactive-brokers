# Interactive Brokers

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Interactive Brokers is an online brokerage firm providing trading access to stocks, options, futures, currencies, bonds, and funds across 150+ markets worldwide. IBKR offers comprehensive REST APIs that enable developers and traders to programmatically access trading, portfolio management, market data, and account management capabilities through the IBKR Web API and Client Portal API.

**Areas:** Brokerage · Market Data · Order · Portfolio · Trading · Real-Time · Investing · Financial Services

## Interactive Brokers on APIs.io

Everything profiled for Interactive Brokers is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/interactive-brokers/](https://apis.io/providers/interactive-brokers/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Interactive Brokers Client Portal API](https://apis.io/apis/interactive-brokers/client-portal-api/) — The Interactive Brokers Client Portal API is a REST API accessed through a locally running Java gateway that routes authenticated requests to IBKR systems.…
- [Interactive Brokers Accounts API](https://apis.io/apis/interactive-brokers/interactive-brokers-accounts-api/) — Account information and management
- [Interactive Brokers Contracts API](https://apis.io/apis/interactive-brokers/interactive-brokers-contracts-api/) — Contract and instrument search
- [Interactive Brokers Market Data API](https://apis.io/apis/interactive-brokers/interactive-brokers-market-data-api/) — Real-time and historical market data
- [Interactive Brokers Orders API](https://apis.io/apis/interactive-brokers/interactive-brokers-orders-api/) — Order placement and management
- [Interactive Brokers Portfolio API](https://apis.io/apis/interactive-brokers/interactive-brokers-portfolio-api/) — Portfolio positions and account summaries
- [Interactive Brokers Sessions API](https://apis.io/apis/interactive-brokers/interactive-brokers-sessions-api/) — Authentication and session management

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Interactive Brokers Client Portal API WebSocket](https://apis.io/asyncapis/interactive-brokers/interactive-brokers-asyncapi/)

#### Event channels (18)

Individual events and webhooks the provider emits.

- [act](https://apis.io/channels/interactive-brokers/act/)
- [blt](https://apis.io/channels/interactive-brokers/blt/)
- [ntf](https://apis.io/channels/interactive-brokers/ntf/)
- [sbd+{acctId}+{conId}+{exchange}](https://apis.io/channels/interactive-brokers/sbd-acctid-conid-exchange/)
- [smd+{conId}](https://apis.io/channels/interactive-brokers/smd-conid/)
- [smh+{conId}](https://apis.io/channels/interactive-brokers/smh-conid/)
- [sor](https://apis.io/channels/interactive-brokers/sor/)
- [spl](https://apis.io/channels/interactive-brokers/spl/)
- [str](https://apis.io/channels/interactive-brokers/str/)
- [sts](https://apis.io/channels/interactive-brokers/sts/)
- [system](https://apis.io/channels/interactive-brokers/system/)
- [tic](https://apis.io/channels/interactive-brokers/tic/)
- [ubd+{acctId}](https://apis.io/channels/interactive-brokers/ubd-acctid/)
- [umd+{conId}](https://apis.io/channels/interactive-brokers/umd-conid/)
- [umh+{serverId}](https://apis.io/channels/interactive-brokers/umh-serverid/)
- [uor](https://apis.io/channels/interactive-brokers/uor/)
- [upl](https://apis.io/channels/interactive-brokers/upl/)
- [utr](https://apis.io/channels/interactive-brokers/utr/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Interactive Brokers Agentic Access](https://apis.io/agentic-access/interactive-brokers/interactive-brokers-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [Interactive Brokers Web Accounts API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-accounts-api/)
- [Interactive Brokers Web Accounts Contracts API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-contracts-api/)
- [Interactive Brokers Web Accounts Market Data API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-market-data-api/)
- [Interactive Brokers Web Accounts Orders API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-orders-api/)
- [Interactive Brokers Web Accounts Portfolio API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-portfolio-api/)
- [Interactive Brokers Web Accounts Sessions API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-sessions-api/)
- [Interactive Brokers Web API](https://apis.io/collections/interactive-brokers/open-interactive-brokers-web-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Interactive Brokers — asyncapi rules](https://apis.io/rules/interactive-brokers/interactive-brokers-asyncapi-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Interactive Brokers Authentication](https://apis.io/security/interactive-brokers/interactive-brokers-authentication/)
- [Interactive Brokers Domain Security](https://apis.io/security/interactive-brokers/interactive-brokers-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Interactive Brokers Scopes](https://apis.io/scopes/interactive-brokers/interactive-brokers-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Interactive Brokers Plans Pricing](https://apis.io/plans/interactive-brokers/interactive-brokers-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Interactive Brokers Rate Limits](https://apis.io/rate-limits/interactive-brokers/interactive-brokers-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Interactive Brokers Finops](https://apis.io/finops/interactive-brokers/interactive-brokers-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.interactivebrokers.com/)
- [Documentation](https://www.interactivebrokers.com/campus/ibkr-api-page/webapi-doc/)

## API Evangelist rating

**Kin Score 30.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 49.1 |
| Contract governance | 13.6 |
| Operational transparency | 13.2 |
| Developer ergonomics | 31.0 |
| Access clarity | 14.5 |

**Agent readiness 24.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 25.9** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/interactive-brokers/](https://apis.io/providers/interactive-brokers/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Interactive Brokers: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/interactive-brokers/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
