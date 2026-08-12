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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Cubby is a New York City based software company building an AI-native facility management
platform for self-storage operators. It replaces legacy FMS systems with facility operations,
tenant management, revenue management, e-commerce storefronts, embedded payment processing and
AI-driven tenant communications, and serves 400+ operators across 2,000+ facilities. Founded in
2022 by Matt Engfer and Adam Fleming; raised a $63M Series A led by Growth Equity at Goldman
Sachs Alternatives in January 2026.

## API surface

- **Cubby Operator API** — a JSON HTTP API (explicitly not RESTful), ~70 action-oriented POST
  endpoints across facilities, units, leases, customers, leads, payments, coverage, auctions,
  locks, messaging and reporting. Base `https://api.cubbystorage.com/v1`.
- **Cubby Storefront API** — the tenant-facing rental slice powering embedded storefronts.
- **Cubby MCP Server** — a live, OAuth-protected Model Context Protocol endpoint at
  `https://api.cubbystorage.com/mcp`, discoverable via RFC 8414 / RFC 9728 metadata.
- **Storefront web components** — Lit-based embeddable checkout and facility components.
- **Make.com webhooks** — six lease-lifecycle events.
- **Analytics data warehouse** — a documented BigQuery `analytics` dataset.

Developer documentation: <https://cubbystorage.github.io/docs/>

## Links

- <https://www.cubbystorage.com/>
- <https://cubbystorage.github.io/docs/>
- <https://github.com/cubbystorage>
- <https://forgeglobal.com/cubby_stock/>
