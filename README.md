# University of Reading

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

The University of Reading is a public research university in Reading, England, founded in 1926 and ranked #172 in the QS World University Rankings 2025. Its programmable footprint is small, real, and almost entirely scholarly: two OAI-PMH 2.0 harvesting endpoints on its own hosts — CentAUR (64,458 research outputs) and the Research Data Archive — plus the read-only EPrints dataset listings beside them. Both were probed live on 2026-09-01 and both are fully open, with no key, no registration and no advertised rate limit. There is no developer portal, no api.reading.ac.uk, no open-data portal and no OpenAPI, AsyncAPI or apis.json document published by the university anywhere. The institution does operate an Azure API Management gateway on its own domain (esb-prod-api.reading.ac.uk) but publishes no route through it. Its strongest institution-operated machine-readable surface after the repositories is identity: a SAML entity in the UK Access Management Federation (entityID https://reading.ac.uk/oala/metadata, scoped reading.ac.uk and reading.edu.my) and a Microsoft Entra ID tenant whose OpenID Connect discovery document is public. It is a registered DataCite member (provider PCLW) and holds a ROR identifier. Almost everything else a reader might mistake for a Reading API is a vendor's contract running under the university's name — Elsevier Pure, Talis Aspire, SirsiDynix Enterprise, ProQuest Summon, Springshare LibGuides — and those are recorded here as tenant relationships, not as the university's engineering.

**Areas:** University · Higher Education · Education · Research · Research Repository · Research Data · Open Access · OAI-PMH · Metadata · Identity Federation · Course Catalog · Library

## University of Reading on APIs.io

Everything profiled for University of Reading is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-reading/](https://apis.io/providers/university-of-reading/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [UK Access Management Federation Identity Provider Entity](https://apis.io/apis/university-of-reading/uk-federation-idp/) — The University of Reading's own SAML identity provider entity, registered in the UK Access Management Federation and published in eduGAIN. entityID…
- [Microsoft Entra ID Tenant OpenID Connect Discovery](https://apis.io/apis/university-of-reading/entra-id-tenant/) — The university's institutional identity plane. Tenant 4ffa3bc4-ecfc-48c0-9080-f5e43ff90e5f, whose OpenID Connect discovery document is public and complete…
- [DataCite Membership and DOI Prefixes](https://apis.io/apis/university-of-reading/datacite-membership/) — The University of Reading is a DataCite member — a fact about the institution, not a contract it operates. api.datacite.org/providers/pclw returns provider…
- [ROR Organization Registration](https://apis.io/apis/university-of-reading/ror-registration/) — The university's entry in the Research Organization Registry, https://ror.org/05v62cm79 — machine-readable identity for the institution itself. The record…
- [Module Catalogue](https://apis.io/apis/university-of-reading/module-catalogue/) — The university's public module (course) catalogue, an ASP.NET application the university runs itself at www.reading.ac.uk/modules. Browsable without a login…
- [Meteorology Department Climate Data Services](https://apis.io/apis/university-of-reading/met-climate-data/) — The Department of Meteorology's data server, metdata.reading.ac.uk, which publishes observations from the University of Reading Atmospheric Observatory —…
- [Elsevier Pure Research Information System (tenant)](https://apis.io/apis/university-of-reading/elsevier-pure-cris/) — The University of Reading runs an Elsevier Pure instance at reading.elsevierpure.com, with a staging sibling at reading-staging.elsevierpure.com. Both…
- [Talis Aspire Online Reading Lists (tenant)](https://apis.io/apis/university-of-reading/talis-aspire-reading-lists/) — The university's online reading list service, a Talis Aspire tenant at reading.rl.talis.com whose canonical institution URI is…
- [SirsiDynix Enterprise Library Catalogue (tenant)](https://apis.io/apis/university-of-reading/library-catalogue/) — The library's catalogue, a SirsiDynix Enterprise tenant at rdg.ent.sirsidynix.net.uk/client/en_GB/library (200 on 2026-09-01), linked from the library's own…
- [CMISGo Timetabling (gated)](https://apis.io/apis/university-of-reading/timetable/) — Student and staff timetabling at timetable.reading.ac.uk. Operator is the institution — the host is the university's own registrable domain and the…
- [University of Reading OAI PMH API](https://apis.io/apis/university-of-reading/university-of-reading-oai-pmh-api/) — OAI-PMH 2.0 verbs served by the repository at /cgi/oai2.
- [University of Reading Repository API](https://apis.io/apis/university-of-reading/university-of-reading-repository-api/) — Read-only EPrints REST dataset listings served by the university's repositories.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Reading Context](https://apis.io/jsonld/university-of-reading/university-of-reading-context/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Reading Authentication](https://apis.io/security/university-of-reading/university-of-reading-authentication/)
- [University Of Reading Domain Security](https://apis.io/security/university-of-reading/university-of-reading-domain-security/)
- [University Of Reading Vulnerability Disclosure](https://apis.io/security/university-of-reading/university-of-reading-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Reading Plans Pricing](https://apis.io/plans/university-of-reading/university-of-reading-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Reading Rate Limits](https://apis.io/rate-limits/university-of-reading/university-of-reading-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Reading Finops](https://apis.io/finops/university-of-reading/university-of-reading-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.reading.ac.uk/)
- [Documentation](https://centaur.reading.ac.uk/information.html)
- [Support](https://www.reading.ac.uk/contact-us/)
- [Blog](https://blogs.reading.ac.uk/)
- [Terms of service](https://www.reading.ac.uk/about/terms-of-use)
- [Privacy policy](https://www.reading.ac.uk/about/privacy)

## API Evangelist rating

**Kin Score 35.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 51.7 |
| Contract governance | 4.5 |
| Operational transparency | 5.3 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 24.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
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

**Regulatory alignment 38.2** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-reading/](https://apis.io/providers/university-of-reading/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Reading: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-reading/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
