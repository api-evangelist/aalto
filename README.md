# Aalto University

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

Aalto University is a multidisciplinary public research university in Espoo, Finland, formed in 2010 from the merger of the Helsinki University of Technology, the Helsinki School of Economics and the University of Art and Design Helsinki. Unusually for this cohort, Aalto operates a real institution-owned API program rather than only a set of vendor tenancies: the Aalto API Gateway (Red Hat 3scale, at 3scale.apps.ocp4.aalto.fi) publishes five documented API products — facilities and room reservations, SISU course data, Acris research publications, projects and cost centres, and a deprecated Oodi-sourced course API — and its ActiveDocs index is publicly readable, exposing forty-four Aalto-authored Swagger/OpenAPI documents whose servers all sit under *.api.aalto.fi. Every one of those endpoints is API-key gated and returns 403 to an anonymous caller, so the contracts are public while the data is not. The genuinely anonymous surfaces are elsewhere: the Aaltodoc institutional repository (Aalto-hosted DSpace 9.2) serves a live OAI-PMH 2.0 endpoint with sixteen metadata formats and an open REST API, and the Linked Open Aalto Data SPARQL endpoint answers real queries — but only over POST, since GET times out. Aalto also runs its own Shibboleth SAML 2.0 identity provider and is registered in the Haka federation with forty-one entities, which is machine-readable institutional infrastructure that almost no university in this cohort catalogues. Its library discovery, research information system and research portal are vendor tenancies (Ex Libris, Elsevier Pure) and are recorded as relationships, not as Aalto's engineering.

**Areas:** University · Higher Education · Education · Finland · Europe · Public Research University · Research · Research Data · Open Data · Linked Data · Course Catalog · Identity Federation

## Aalto University on APIs.io

Everything profiled for Aalto University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aalto/](https://apis.io/providers/aalto/)** — or go straight to one of the APIs or properties below.

### APIs (18)

- [Aalto API Gateway](https://apis.io/apis/aalto/api-gateway/) — Aalto's own Red Hat 3scale API gateway, the front door to every institution-operated API at Aalto. Five API products are documented on the portal; the…
- [Aalto Open API — Course API (Oodi, deprecated)](https://apis.io/apis/aalto/course-oodi-deprecated/) — The Oodi-sourced course API, still published on the portal and explicitly marked deprecated: "This API source is OODI and should not be used." Swagger 2.0,…
- [Aaltodoc Repository — OAI-PMH and DSpace REST](https://apis.io/apis/aalto/aaltodoc/) — Aalto's institutional repository of theses, articles and conference publications, running Aalto-hosted DSpace 9.2 on aaltodoc.aalto.fi. Both read surfaces…
- [Aalto Shibboleth Identity Provider (Haka / eduGAIN)](https://apis.io/apis/aalto/identity-federation/) — Aalto's own Shibboleth SAML 2.0 identity provider, entityID https://idp.aalto.fi/idp/shibboleth, scope aalto.fi, registration authority http://www.aalto.fi…
- [Linked Open Aalto Data (SPARQL)](https://apis.io/apis/aalto/linked-open-data/) — Aalto's open data published as Linked Data — courses, people, publications, places, projects, organisation and events — under data.aalto.fi URIs. The…
- [Acris — Aalto Current Research Information System (Elsevier Pure)](https://apis.io/apis/aalto/acris-pure/) — Aalto's research information system is Elsevier Pure, deployed as Acris at acris.aalto.fi with the Pure Portal at research.aalto.fi. The data and the DOIs…
- [Aalto Learning Centre discovery (Ex Libris Primo / Alma, Finna)](https://apis.io/apis/aalto/library-discovery/) — Library discovery and the library management system are Ex Libris products under Aalto tenancies — primo.aalto.fi resolves to the Primo NDE interface with…
- [SISU student information system (Funidata)](https://apis.io/apis/aalto/sisu-sis/) — sisu.aalto.fi is Aalto's deployment of SISU, the student information system built by Funidata, a company jointly owned by Finnish universities. It is the…
- [Aalto University Buildings API](https://apis.io/apis/aalto/aalto-buildings-api/) — Aalto Building related data
- [Aalto University Groups API](https://apis.io/apis/aalto/aalto-groups-api/) — The Groups API from Aalto University — 1 operation(s) for groups.
- [Aalto University Organisational Data API](https://apis.io/apis/aalto/aalto-organisational-data-api/) — The Organisational Data API from Aalto University — 2 operation(s) for organisational data.
- [Aalto University Profiles API](https://apis.io/apis/aalto/aalto-profiles-api/) — The Profiles API from Aalto University — 1 operation(s) for profiles.
- [Aalto University Projects API](https://apis.io/apis/aalto/aalto-projects-api/) — The Projects API from Aalto University — 1 operation(s) for projects.
- [Aalto University Research Outputs API](https://apis.io/apis/aalto/aalto-research-outputs-api/) — The research-outputs API from Aalto University — 3 operation(s) for research-outputs.
- [Aalto University Research Outputs Enhanced API](https://apis.io/apis/aalto/aalto-research-outputs-enhanced-api/) — The research-outputs-enhanced API from Aalto University — 1 operation(s) for research-outputs-enhanced.
- [Aalto University Reservations API](https://apis.io/apis/aalto/aalto-reservations-api/) — Room reservations.
- [Aalto University SISU Courses API](https://apis.io/apis/aalto/aalto-sisu-courses-api/) — The SISU Courses API from Aalto University — 4 operation(s) for sisu courses.
- [Aalto University Cost Centers API](https://apis.io/apis/aalto/aalto-cost-centers-api/) — The Cost Centers API from Aalto University — 1 operation(s) for cost centers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [Sisu API (replaces /oodiapi) — component schemas](https://apis.io/schemas/aalto/aalto-course-sisu-api/)
- [Aalto facilities api — component schemas](https://apis.io/schemas/aalto/aalto-facilities-api/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Aalto Context](https://apis.io/jsonld/aalto/aalto-context/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Aalto Authentication](https://apis.io/security/aalto/aalto-authentication/)
- [Aalto Domain Security](https://apis.io/security/aalto/aalto-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aalto Plans Pricing](https://apis.io/plans/aalto/aalto-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aalto Rate Limits](https://apis.io/rate-limits/aalto/aalto-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Aalto Finops](https://apis.io/finops/aalto/aalto-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aalto.fi/en)
- [Documentation](https://www.aalto.fi/en/services/api-gateway-application-programming-interface)
- [API reference](https://3scale.apps.ocp4.aalto.fi/docs)
- [Blog](https://www.aalto.fi/en/news)
- [Privacy policy](https://www.aalto.fi/en/aalto-handbook/privacy-notice-for-aaltofi)
- [GitHub](https://github.com/AaltoSciComp)

## API Evangelist rating

**Kin Score 34.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 53.6 |
| Contract quality | 54.9 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 40.5 |
| Access clarity | 28.9 |

**Agent readiness 28.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | verified |
| OpenAPI Examples | partial |
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

**Regulatory alignment 20.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aalto/](https://apis.io/providers/aalto/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Aalto University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aalto/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
