# University of Reading (university-of-reading)

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
