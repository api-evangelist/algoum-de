# Algoum

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

algoum provides a SEC EDGAR API delivering insider trades, 8‑K filings and 13F data in clear, plain‑language JSON. It transforms official company disclosures into easy‑to‑read updates for investors and algorithmic traders, offering free access (currently an open test phase) and no ads; every request needs a free personal API key sent as a bearer token. The service includes real‑time streaming, MCP integration, and comprehensive documentation, aiming to make financial filings transparent and actionable.

**Areas:** Company · Finance · SEC · InsiderTrading · API

## Algoum on APIs.io

Everything profiled for Algoum is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/algoum-de/](https://apis.io/providers/algoum-de/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [algoum-de Common API](https://apis.io/apis/algoum-de/algoum-de-common-api/) — Ticker/CIK resolution and company search, the raw SEC filing behind every record, and the freshness of each data source.
- [algoum-de Events API](https://apis.io/apis/algoum-de/algoum-de-events-api/) — Material events a company has to disclose – leadership changes, mergers, bankruptcies, cyber incidents and more. Available as searchable history, as a…
- [algoum-de Insider API](https://apis.io/apis/algoum-de/algoum-de-insider-api/) — Buys and sells reported by officers, directors and 10% owners, plus the signals derived from them (cluster buys, buy/sell ratio). Source are the SEC forms 4…
- [algoum-de Institutional API](https://apis.io/apis/algoum-de/algoum-de-institutional-api/) — Quarterly portfolios of institutional investors and the aggregated picture per stock. 13F filings are due 45 days after quarter end, so the most recent…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Algoum De Webhooks](https://apis.io/asyncapis/algoum-de/algoum-de-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [algoum-de-mcp.yml](https://apis.io/servers/algoum-de/algoum-de-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Algoum Agentic Access](https://apis.io/agentic-access/algoum-de/algoum-de-agentic-access/)

#### JSON Schema (10)

The data models the API reads and writes.

- [ClusterBuy](https://apis.io/schemas/algoum-de/algoum-de-cluster-buy/)
- [Disclosure](https://apis.io/schemas/algoum-de/algoum-de-disclosure/)
- [Envelope](https://apis.io/schemas/algoum-de/algoum-de-envelope/)
- [Event](https://apis.io/schemas/algoum-de/algoum-de-event/)
- [Filing](https://apis.io/schemas/algoum-de/algoum-de-filing/)
- [Holding](https://apis.io/schemas/algoum-de/algoum-de-holding/)
- [InsiderTransaction](https://apis.io/schemas/algoum-de/algoum-de-insider-transaction/)
- [InstitutionalSentiment](https://apis.io/schemas/algoum-de/algoum-de-institutional-sentiment/)
- [SourceStatus](https://apis.io/schemas/algoum-de/algoum-de-source-status/)
- [TickerEntry](https://apis.io/schemas/algoum-de/algoum-de-ticker-entry/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Algoum De Context](https://apis.io/jsonld/algoum-de/algoum-de-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Algoum API Rules](https://apis.io/rules/algoum-de/algoum-de-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Algoum Authentication](https://apis.io/security/algoum-de/algoum-de-authentication/)
- [Algoum Domain Security](https://apis.io/security/algoum-de/algoum-de-domain-security/)
- [Algoum Vulnerability Disclosure](https://apis.io/security/algoum-de/algoum-de-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Algoum Scopes](https://apis.io/scopes/algoum-de/algoum-de-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Algoum Plans Pricing](https://apis.io/plans/algoum-de/algoum-de-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Algoum Rate Limits](https://apis.io/rate-limits/algoum-de/algoum-de-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://algoum.de/)
- [Documentation](https://algoum.de/docs)
- [Getting started](https://algoum.de/docs/getting-started)
- [API reference](https://algoum.de/docs)
- [Pricing](https://algoum.de/docs/pricing)
- [Sign up](https://algoum.de/signup)
- [Support](https://algoum.de/contact)
- [Changelog](https://algoum.de/docs/changelog)
- [Terms of service](https://algoum.de/legal/terms)
- [Privacy policy](https://algoum.de/legal/privacy)
- [GitHub](https://github.com/fi4all)
- [Status](https://api.algoum.de/v1/status)

## API Evangelist rating

**Kin Score 70.9** — exemplar · rubric 0.27.0 · scored 2026-11-12

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 70.9 |
| Contract governance | 79.1 |
| Operational transparency | 74.2 |
| Developer ergonomics | 51.7 |
| Access clarity | 63.7 |

**Agent readiness 56.7** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | na |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | verified |
| Event Surface Described | unknown |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 43.5** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/algoum-de/](https://apis.io/providers/algoum-de/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Algoum: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/algoum-de/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
