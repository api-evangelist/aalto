# Aalto University (aalto)

Aalto University is a multidisciplinary public research university in Espoo, Finland, ranked #113 in the QS World University Rankings 2025. This repository catalogs Aalto's public developer and API footprint as an [APIs.json](http://apisjson.org) profile. That footprint is modest and research-oriented: an authentication-gated Aalto API Gateway (3scale) carrying course/student-system APIs, a Linked Open Aalto Data SPARQL service, and the Aaltodoc institutional repository with OAI-PMH and REST access.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/aalto/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=aalto-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Linked Data, Finland

## APIs

- **Aalto API Gateway** — 3scale gateway exposing interfaces about Aalto and its operations (Oodi, ASIO); Aalto account / VPN required. Docs: https://www.aalto.fi/en/services/api-gateway-application-programming-interface
- **Open Courses API (SISU)** — course/realization data from the SISU student information system; Swagger published but spec and calls are gated. Docs: https://3scale.apps.ocp4.aalto.fi/docs/swagger/open_courses_sisu
- **Linked Open Aalto Data (SPARQL)** — public SPARQL endpoint, Linked Data browser, and dataset downloads. Docs: https://data.aalto.fi/ — endpoint: http://ldf.fi/loa/sparql
- **Aaltodoc Repository (OAI-PMH and REST)** — DSpace institutional repository with OAI-PMH 2.0 and REST API. Docs: https://www.aalto.fi/en/open-science-and-research/aaltodoc-publication-archive

## Plans

- [plans/aalto-plans-pricing.yml](plans/aalto-plans-pricing.yml)

## Rate Limits

- [rate-limits/aalto-rate-limits.yml](rate-limits/aalto-rate-limits.yml)

## FinOps

- [finops/aalto-finops.yml](finops/aalto-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.aalto.fi/en
- Developer Portal: https://apiportal.aalto.fi/
- GitHub: https://github.com/AaltoSciComp
- LinkedIn: https://www.linkedin.com/school/aalto-university/
- Review: [review.yml](review.yml)

## Notes

All URLs were probed on 2026-06-03. The API Gateway and Open Courses (SISU) API resolve but require an Aalto account to view specifications or make calls — no anonymous endpoints were confirmed. The Linked Open Aalto Data SPARQL endpoint, the Aaltodoc OAI-PMH endpoint, and the Aaltodoc DSpace REST API are publicly reachable and were verified live. The `AaltoUniversity` GitHub org exists but has no public repositories, so `AaltoSciComp` (169 public repos) is listed as the active public org. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
