# Cubby

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

Cubby is a New York City based software company building an AI-native facility management platform for self-storage operators, replacing legacy FMS systems with facility operations, tenant management, revenue management, e-commerce storefronts, embedded payment processing and AI-driven tenant communications. Cubby publishes a public developer documentation site covering a JSON HTTP Operator API of roughly 70 action-oriented endpoints across facilities, units, leases, customers, leads, payments, coverage, auctions and reporting, a BigQuery analytics data warehouse, Make.com outbound webhooks, embeddable Lit storefront web components, and an OAuth-protected Model Context Protocol server. The company was founded in 2022 by Matt Engfer and Adam Fleming and raised a $63M Series A led by Growth Equity at Goldman Sachs Alternatives in January 2026.

**Areas:** Company · Self Storage · Property Management · Facility Management · Real Estate · Payments · Software-as-a-Service · Artificial Intelligence · Revenue Management · E-Commerce

## Cubby on APIs.io

Everything profiled for Cubby is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cubby/](https://apis.io/providers/cubby/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Cubby Operator API](https://apis.io/apis/cubby/cubby-operator-api/) — The Cubby Operator API is a JSON HTTP API — explicitly not RESTful — oriented around actions performed on system entities rather than transfer of state.…
- [Cubby Storefront API](https://apis.io/apis/cubby/cubby-storefront-api/) — The Cubby Storefront API is the public, unauthenticated-tenant-facing slice of the Cubby platform used to power online rental storefronts — facility search…
- [Cubby MCP Server](https://apis.io/apis/cubby/cubby-mcp-server/) — Cubby operates a hosted Model Context Protocol server at api.cubbystorage.com/mcp. The endpoint is live and OAuth-protected: an unauthenticated JSON-RPC…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Cubby Webhooks](https://apis.io/asyncapis/cubby/cubby-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Cubby MCP Server](https://apis.io/servers/cubby/cubby-mcp-server/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cubby Authentication](https://apis.io/security/cubby/cubby-authentication/)
- [Cubby Domain Security](https://apis.io/security/cubby/cubby-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Cubby Scopes](https://apis.io/scopes/cubby/cubby-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cubby Plans Pricing](https://apis.io/plans/cubby/cubby-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cubby Rate Limits](https://apis.io/rate-limits/cubby/cubby-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.cubbystorage.com/)
- [Documentation](https://cubbystorage.github.io/docs/)
- [API reference](https://cubbystorage.github.io/docs/api/)
- [Sign up](https://app.cubbystorage.com/signin)
- [Support](https://help.cubbystorage.com/en/)
- [Blog](https://www.cubbystorage.com/blog)
- [Terms of service](https://www.cubbystorage.com/api-terms-of-service)
- [Privacy policy](https://www.cubbystorage.com/privacy-policy)
- [GitHub](https://github.com/cubbystorage)

## API Evangelist rating

**Kin Score 40.7** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 45.3 |
| Contract governance | 18.2 |
| Operational transparency | 34.2 |
| Developer ergonomics | 45.2 |
| Access clarity | 21.1 |

**Agent readiness 51.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 29.2** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cubby/](https://apis.io/providers/cubby/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cubby: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cubby/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
