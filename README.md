# Aalto University (aalto)

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

Aalto University is a multidisciplinary public research university in Espoo, Finland. This repository catalogs Aalto's public developer and API footprint as an [APIs.json](http://apisjson.org) profile, profiled under the API Evangelist university pipeline — which settles **who operates each surface** before anything is saved.

Aalto is unusual in this cohort: it runs a real institution-owned API program rather than only a set of vendor tenancies. Its Red Hat 3scale gateway leaves the ActiveDocs index open without credentials, exposing forty-four Aalto-authored Swagger/OpenAPI documents whose servers all sit under `*.api.aalto.fi`. Every gateway endpoint is API-key gated and returns `403` to an anonymous caller — so the contracts are public and the data is not. The genuinely anonymous surfaces are the Aaltodoc repository (OAI-PMH 2.0 + DSpace 9.2 REST) and the Linked Open Aalto Data SPARQL endpoint.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/aalto/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=aalto-api-evangelist&utm_content=repo

## Type

- University / Public Research University / Index / Provider / 1st-Party

## Tags

University, Higher Education, Education, Finland, Europe, Public Research University, Research, Research Data, Open Data, Linked Data, Course Catalog, Identity Federation, Research Computing, Library, API Gateway

## Institution-operated surfaces

These are Aalto's own. The contracts below are saved in `openapi/`, with pristine copies in `openapi/_original/`.

- **Aalto API Gateway** — Red Hat 3scale at `3scale.apps.ocp4.aalto.fi` (front door `apiportal.aalto.fi`); five documented API products, forty-four specs in the public ActiveDocs index. Key issuance requires an Aalto account.
- **Aalto Facilities API** — buildings, opening hours, rooms and reservations. OpenAPI 3.0.1 · `facilities.api.aalto.fi`
- **Aalto Course API (SISU)** — course units and realisations. OpenAPI 3.0.1 · `course.api.aalto.fi`
- **Aalto Research Publications API (Acris gateway)** — Aalto's own four-path wrapper over its Pure data. OpenAPI 3.0.0 · `research.api.aalto.fi`
- **Aalto Projects and Cost Centers API** — cost centres, projects, departments, schools. OpenAPI 3.0.0 · `api.aalto.fi`
- **Aalto People Profile API** — groups and public staff profiles. OpenAPI 3.0.1 · `aaltopeople.api.aalto.fi`
- **Aalto Open API (Course, Oodi)** — *deprecated*; Aalto says "should not be used", superseded by the SISU API. No spec saved.
- **Aaltodoc Repository** — Aalto-hosted DSpace 9.2; OAI-PMH 2.0 and REST, both anonymous and verified live.
- **Shibboleth Identity Provider** — `https://idp.aalto.fi/idp/shibboleth`, scope `aalto.fi`; 41 Aalto entities registered in the Haka federation, onward to eduGAIN.

## Tenant surfaces (Aalto's data, a vendor's contract)

Recorded as relationships. **No vendor specification is saved under Aalto's name.**

- **Acris / research.aalto.fi** — Elsevier Pure research information system and portal.
- **primo.aalto.fi, aalto.alma.exlibrisgroup.com, aalto.finna.fi** — Ex Libris Primo/Alma and the national Finna discovery platform.
- **sisu.aalto.fi** — SISU student information system, built by Funidata.
- **ldf.fi/loa** — Linked Open Aalto Data SPARQL, served on the shared Linked Data Finland platform.

## Domain standard conformance (education regime)

Verified by live probe — see [conformance/aalto-conformance.yml](conformance/aalto-conformance.yml).

- `oai-pmh` 2.0 · `saml` 2.0 · `shibboleth` — conformant, evidenced
- `orcid`, `datacite`, `crossref` — deployed via Aaltodoc's public DSpace integrations
- `scim`, `lti`, `oneroster`, `ed-fi`, `caliper`, `qti` — not found

## Artifacts

- [openapi/](openapi/) + [openapi/_original/](openapi/_original/)
- [json-schema/](json-schema/)
- [authentication/aalto-authentication.yml](authentication/aalto-authentication.yml)
- [conformance/aalto-conformance.yml](conformance/aalto-conformance.yml)
- [errors/aalto-errors.yml](errors/aalto-errors.yml)
- [lifecycle/aalto-lifecycle.yml](lifecycle/aalto-lifecycle.yml)
- [plans/aalto-plans-pricing.yml](plans/aalto-plans-pricing.yml)
- [rate-limits/aalto-rate-limits.yml](rate-limits/aalto-rate-limits.yml)
- [finops/aalto-finops.yml](finops/aalto-finops.yml)
- [security/aalto-domain-security.yml](security/aalto-domain-security.yml)
- [provenance.yml](provenance.yml) — who wrote each file here
- [review.yml](review.yml) — the probe evidence table

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.aalto.fi/en
- Developer Portal: https://3scale.apps.ocp4.aalto.fi/
- API Reference: https://3scale.apps.ocp4.aalto.fi/docs
- Open Data: https://data.aalto.fi/
- Research Repository: https://aaltodoc.aalto.fi/
- Identity Federation: https://idp.aalto.fi/idp/shibboleth
- Research Computing: https://scicomp.aalto.fi/
- AI Policy: https://www.aalto.fi/en/services/ai-in-aalto
- AI Tooling: https://ai.aalto.fi/
- Source Code: https://version.aalto.fi/ (Aalto-operated GitLab)
- GitHub: https://github.com/AaltoSciComp
- Privacy: https://www.aalto.fi/en/aalto-handbook/privacy-notice-for-aaltofi
- LinkedIn: https://www.linkedin.com/school/aalto-university/

## Notes

All URLs were re-probed on 2026-08-30 and the evidence table is in [review.yml](review.yml). Two things a status code alone would have got wrong, both recorded: the Linked Open Aalto Data SPARQL endpoint at `ldf.fi/loa/sparql` is **live over POST only** — a GET times out and its own redirect target 404s — and the historically published Aaltodoc OAI path `/oai/request` now 301s to `/server/oai/request` under DSpace 9.2. `aalto.finna.fi` returns 403 to a bot, which is a finding about that edge and not about Aalto.

Three of Aalto's contracts still carry Swagger sample-project boilerplate (`termsOfService: http://swagger.io/terms/`, `contact: apiteam@swagger.io`) that was never replaced. That is a hygiene finding, not an ownership signal — the servers on all three are Aalto's own hosts.

No endpoints were fabricated, and no vendor contract is attributed to Aalto.

## Maintainers

- Kin Lane — kin@apievangelist.com
