# University of Reading (university-of-reading)

The University of Reading is a public research university in Reading, England, ranked #172 in the QS World University Rankings 2025. This repository catalogs the university's public, machine-readable developer/API footprint as an APIs.json profile. That footprint is centered on open scholarly and research-data metadata — two EPrints repositories (CentAUR and the Research Data Archive) expose live OAI-PMH endpoints — rather than a formal developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-reading/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-reading-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Access, Repository, Metadata, United Kingdom

## APIs

- **CentAUR OAI-PMH Metadata API** — OAI-PMH 2.0 harvesting interface for the Central Archive University of Reading institutional repository (EPrints). Docs: https://centaur.reading.ac.uk/information.html — Endpoint: https://centaur.reading.ac.uk/cgi/oai2
- **Research Data Archive OAI-PMH Metadata API** — OAI-PMH harvesting interface for the University of Reading Research Data Archive (EPrints). Docs: https://researchdata.reading.ac.uk/ — Endpoint: https://researchdata.reading.ac.uk/cgi/oai2

## Plans

- [plans/university-of-reading-plans-pricing.yml](plans/university-of-reading-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-reading-rate-limits.yml](rate-limits/university-of-reading-rate-limits.yml)

## FinOps

- [finops/university-of-reading-finops.yml](finops/university-of-reading-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.reading.ac.uk/
- LinkedIn: https://uk.linkedin.com/school/university-of-reading/
- Plans: plans/university-of-reading-plans-pricing.yml
- Rate Limits: rate-limits/university-of-reading-rate-limits.yml
- FinOps: finops/university-of-reading-finops.yml
- Review: review.yml

## Notes

All listed APIs were verified live on 2026-06-03 (both OAI-PMH Identify endpoints returned HTTP 200; CentAUR reported repositoryName "CentAUR" and protocol version 2.0). No public self-service developer portal, REST API catalog, sign-up flow, or official GitHub organization could be confirmed (candidate GitHub org names returned 404). Administrative, identity (Shibboleth/SAML), and student-information interfaces are gated behind institutional affiliation and were not publicly documented. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
