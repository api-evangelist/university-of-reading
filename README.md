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

The University of Reading is a public research university in Reading, England, founded in 1926. This repository catalogs the university's public, machine-readable footprint as an APIs.json profile, and it settles WHO OPERATES each surface before crediting it. Two institution-operated APIs are real and open — the OAI-PMH 2.0 endpoints for CentAUR (64,458 research outputs) and the Research Data Archive — alongside read-only EPrints dataset listings, a UK Access Management Federation SAML identity entity, a public Entra ID OpenID Connect discovery document, DataCite membership (provider PCLW) and a ROR registration. There is no developer portal and no open-data portal. Library discovery, reading lists, the CRIS and timetabling are vendor tenancies recorded as relationships, never as the university's contracts.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-reading/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-reading-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Research, Research Repository, Research Data, Open Access, OAI-PMH, Metadata, Identity Federation, Course Catalog, Library, Climate Data, United Kingdom, England

## APIs

- **CentAUR OAI-PMH Metadata API** — `x-operator: institution` — OAI-PMH 2.0 metadata harvesting interface for CentAUR, the Central Archive at the University of Reading — the institutional repository of the university's research outputs. Endpoint: https://centaur.reading.ac.uk/cgi/oai2
- **Research Data Archive OAI-PMH Metadata API** — `x-operator: institution` — OAI-PMH 2.0 metadata harvesting interface for the University of Reading Research Data Archive, the institution's multidisciplinary service for registering, preserving and publishing research datasets. Endpoint: https://researchdata.reading.ac.uk/cgi/oai2
- **CentAUR Repository REST Listings** — `x-operator: institution` — The read-only EPrints REST interface on CentAUR. Endpoint: https://centaur.reading.ac.uk/rest/
- **Research Data Archive REST Listings** — `x-operator: institution` — The same read-only EPrints REST interface on the Research Data Archive host. Endpoint: https://researchdata.reading.ac.uk/rest/
- **UK Access Management Federation Identity Provider Entity** — `x-operator: federation` — The University of Reading's own SAML identity provider entity, registered in the UK Access Management Federation and published in eduGAIN. Endpoint: http://mdq.ukfederation.org.uk/entities/%7Bsha1%7D57cf958ecb2c90e4fb339c8cf8a95dcee2d68101
- **Microsoft Entra ID Tenant OpenID Connect Discovery** — `x-operator: federation` — The university's institutional identity plane. Endpoint: https://login.microsoftonline.com/reading.ac.uk/v2.0/.well-known/openid-configuration
- **DataCite Membership and DOI Prefixes** — `x-operator: registry` — The University of Reading is a DataCite member — a fact about the institution, not a contract it operates. Endpoint: https://api.datacite.org/providers/pclw
- **ROR Organization Registration** — `x-operator: registry` — The university's entry in the Research Organization Registry, https://ror.org/05v62cm79 — machine-readable identity for the institution itself. Endpoint: https://api.ror.org/v2/organizations/05v62cm79
- **Module Catalogue** — `x-operator: institution` — The university's public module (course) catalogue, an ASP.NET application the university runs itself at www.reading.ac.uk/modules. Endpoint: https://www.reading.ac.uk/modules/
- **Meteorology Department Climate Data Services** — `x-operator: institution` — The Department of Meteorology's data server, metdata.reading.ac.uk, which publishes observations from the University of Reading Atmospheric Observatory — one of the longest continuous climatological records in the UK. Endpoint: https://metdata.reading.ac.uk/
- **Elsevier Pure Research Information System (tenant)** — `x-operator: tenant` — The University of Reading runs an Elsevier Pure instance at reading.elsevierpure.com, with a staging sibling at reading-staging.elsevierpure.com. Endpoint: https://reading.elsevierpure.com/
- **Talis Aspire Online Reading Lists (tenant)** — `x-operator: tenant` — The university's online reading list service, a Talis Aspire tenant at reading.rl.talis.com whose canonical institution URI is http://readinglists.reading.ac.uk/. Endpoint: https://reading.rl.talis.com/index.json
- **SirsiDynix Enterprise Library Catalogue (tenant)** — `x-operator: tenant` — The library's catalogue, a SirsiDynix Enterprise tenant at rdg.ent.sirsidynix.net.uk/client/en_GB/library (200 on 2026-09-01), linked from the library's own catalogues page. Endpoint: https://rdg.ent.sirsidynix.net.uk/client/en_GB/library
- **CMISGo Timetabling (gated)** — `x-operator: institution` — Student and staff timetabling at timetable.reading.ac.uk, an Advanced CMISGo deployment. Endpoint: https://timetable.reading.ac.uk/

## Plans

- [plans/university-of-reading-plans-pricing.yml](plans/university-of-reading-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-reading-rate-limits.yml](rate-limits/university-of-reading-rate-limits.yml)

## FinOps

- [finops/university-of-reading-finops.yml](finops/university-of-reading-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-09-01

## Common Properties

- Website: https://www.reading.ac.uk/
- ResearchRepository: https://centaur.reading.ac.uk/
- ResearchData: https://researchdata.reading.ac.uk/
- OpenData: https://metdata.reading.ac.uk/
- CourseCatalog: https://www.reading.ac.uk/modules/
- LibraryCatalog: https://www.reading.ac.uk/library/using-the-library/catalogues
- IdentityFederation: http://mdq.ukfederation.org.uk/entities/%7Bsha1%7D57cf958ecb2c90e4fb339c8cf8a95dcee2d68101
- AIPolicy: https://www.reading.ac.uk/cqsd/artificial-intelligence
- AITooling: https://www.reading.ac.uk/digital-technology-services/ai-index-hub
- Documentation: https://centaur.reading.ac.uk/information.html
- Blog: https://blogs.reading.ac.uk/
- Support: https://www.reading.ac.uk/contact-us/
- TermsOfService: https://www.reading.ac.uk/about/terms-of-use
- PrivacyPolicy: https://www.reading.ac.uk/about/privacy
- LinkedIn: https://uk.linkedin.com/school/university-of-reading/
- x-conformance: conformance/university-of-reading-conformance.yml
- Authentication: authentication/university-of-reading-authentication.yml
- VulnerabilityDisclosure: security/university-of-reading-vulnerability-disclosure.yml
- DomainSecurity: security/university-of-reading-domain-security.yml
- Plans: plans/university-of-reading-plans-pricing.yml
- RateLimits: rate-limits/university-of-reading-rate-limits.yml
- FinOps: finops/university-of-reading-finops.yml
- Review: review.yml

## Notes

Every surface here was re-probed live on 2026-09-01 under the API Evangelist university pipeline, which asks who operates a thing before saving its contract. Both OAI-PMH endpoints returned 200 and were exercised across Identify, ListMetadataFormats, ListSets and ListRecords; the EPrints /rest/ listings returned 200 while per-record XML returned 401. The three OpenAPI documents in openapi/ were DERIVED by API Evangelist from those probes and are marked as such — the University of Reading publishes no OpenAPI, AsyncAPI or apis.json of its own. No Figshare tenancy exists: reading.figshare.com returns the same AWS WAF challenge that a nonsense subdomain does, so the host is not evidence. The university runs an Azure API Management gateway on its own domain (esb-prod-api.reading.ac.uk) with no published route. Two measurement traps are recorded in x-coverage: /cgi/search and /cgi/export on centaur.reading.ac.uk answer HTTP 200 with an Anubis bot interstitial, and www.reading.ac.uk serves 404s from /search/404.htm. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
