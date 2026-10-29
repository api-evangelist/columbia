# Columbia University

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

Columbia University is a private Ivy League research university in New York City, ranked seventeenth in the QS World University Rankings. Its programmable footprint is small, real, and almost entirely invisible from the outside. Columbia operates exactly one publicly consumable, unauthenticated API of its own: the Columbia University Libraries Hours API at hours.library.columbia.edu, two read operations returning JSON with CORS enabled, built on Columbia's own openly published Rails codebase and documented by nobody. Alongside it the university runs a production Shibboleth Identity Provider that publishes signed SAML 2.0 metadata under the InCommon entityID urn:mace:incommon:columbia.edu, mints DOIs under its own DataCite prefix 10.7916 across 1.1 million registered identifiers, deposits into Crossref as member 6984, and releases the entire CLIO library catalogue as CC0 MARCXML bulk extracts. That is the whole of it. The Open Data Service that Columbia describes as its developer-facing service is gated behind a UNI login, and the IRI/LDEO Climate Data Library now redirects its data paths to a login form. Columbia publishes no OpenAPI, no developer portal reachable without affiliation, no changelog, no llms.txt and no API terms, and it reserves the hostname api.library.columbia.edu while serving nothing but a placeholder there. Most consequentially for machine access, Columbia defends its estate with two different anti-bot products: a Cloudflare managed challenge across the central web estate, and an Anubis proof-of-work challenge in front of the Libraries' entire discovery layer — the CLIO catalogue, Academic Commons and GeoData — which returns HTTP 200 with a bot-check body and made the institution's OAI-PMH endpoint unverifiable. Learning management runs on Instructure's Canvas and the research data platform on Redivis; both are tenant relationships, recorded as such and scored against their vendors.

**Areas:** University · Higher Education · Education · Ivy League · Private Research University · United States · New York · Identity Federation · Library · Open Data · Research Repository · Research Data

## Columbia University on APIs.io

Everything profiled for Columbia University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/columbia/](https://apis.io/providers/columbia/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Columbia Identity — Shibboleth IdP and CAS](https://apis.io/apis/columbia/identity/) — Columbia University Information Technology operates the university's own identity infrastructure: a production Shibboleth Identity Provider publishing…
- [CLIO Library Catalog Open Data](https://apis.io/apis/columbia/clio-opendata/) — Columbia University Libraries publishes its full catalogue — bibliographic and holdings records from the integrated library system behind CLIO — as gzipped…
- [Columbia Open Data Service](https://apis.io/apis/columbia/opendata/) — The central university service publishing data feeds to software developers in programming-friendly formats such as JSON and XML — the course directory, the…
- [CU Directory of Classes](https://apis.io/apis/columbia/directory-of-classes/) — The public web directory of Columbia University class offerings, browsable by subject, department, semester, instruction method, weekday and start time.…
- [Columbia Academic Commons](https://apis.io/apis/columbia/academic-commons/) — Columbia University's institutional research repository, holding the scholarly output, theses and research data of the university. Unusually for this cohort…
- [Digital Library Collections and the 10.7916 DOI namespace](https://apis.io/apis/columbia/dlc/) — Columbia University Libraries' digital collections platform and the resolution target for Columbia's own DOI namespace. Columbia is a registered DataCite…
- [IRI/LDEO Climate Data Library](https://apis.io/apis/columbia/iri-data-library/) — The Climate Data Library run by the International Research Institute for Climate and Society and the Lamont-Doherty Earth Observatory, both Columbia…
- [CourseWorks (Instructure Canvas)](https://apis.io/apis/columbia/courseworks/) — Columbia's learning management system. The REST API is live and returns a well-structured JSON 401 to unauthenticated callers, and the LTI 1.3 tool-platform…
- [Columbia University Data Platform (Redivis)](https://apis.io/apis/columbia/redivis/) — Columbia's research data platform runs on Redivis as an institution-specific tenancy, and the university has registered two distinct DataCite repository…
- [Columbia University Locations API](https://apis.io/apis/columbia/columbia-locations-api/) — Library locations and their posted opening hours.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Columbia Agentic Access](https://apis.io/agentic-access/columbia/columbia-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [Columbia University Libraries Hours API response schemas](https://apis.io/schemas/columbia/columbia-library-hours/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Columbia Context](https://apis.io/jsonld/columbia/columbia-context/)

#### Examples (7)

Example requests and responses.

- [Columbia Crossref Member Example](https://apis.io/examples/columbia/columbia-crossref-member-example/)
- [Columbia Datacite Client Example](https://apis.io/examples/columbia/columbia-datacite-client-example/)
- [Columbia Library Hours Error 400 Example](https://apis.io/examples/columbia/columbia-library-hours-error-400-example/)
- [Columbia Library Hours Error 404 Example](https://apis.io/examples/columbia/columbia-library-hours-error-404-example/)
- [Columbia Library Hours Location Day Example](https://apis.io/examples/columbia/columbia-library-hours-location-day-example/)
- [Columbia Library Hours Location Range Example](https://apis.io/examples/columbia/columbia-library-hours-location-range-example/)
- [Columbia Library Hours Open Now Example](https://apis.io/examples/columbia/columbia-library-hours-open-now-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Columbia University API Rules](https://apis.io/rules/columbia/columbia-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Columbia Authentication](https://apis.io/security/columbia/columbia-authentication/)
- [Columbia Domain Security](https://apis.io/security/columbia/columbia-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Columbia Scopes](https://apis.io/scopes/columbia/columbia-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Columbia Plans Pricing](https://apis.io/plans/columbia/columbia-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Columbia Rate Limits](https://apis.io/rate-limits/columbia/columbia-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Columbia Finops](https://apis.io/finops/columbia/columbia-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.columbia.edu/)
- [Blog](https://neighbors.columbia.edu/news)
- [GitHub](https://github.com/cul)

## API Evangelist rating

**Kin Score 33.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 60.6 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 33.3 |
| Access clarity | 18.4 |

**Agent readiness 39.5** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | yes |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 26.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/columbia/](https://apis.io/providers/columbia/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Columbia University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/columbia/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
