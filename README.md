# Kyushu University

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

Kyushu University (九州大学) is a Japanese national research university in Fukuoka, one of the seven former Imperial Universities and a Designated National University, ranked #171 in the QS World University Rankings 2027. Its programmable footprint is small and concentrated in scholarly infrastructure rather than in a developer platform, and this profile says so rather than padding it. Exactly one unambiguously institution-operated API was found and exercised end to end: the OAI-PMH 2.0 metadata interface for the Kyushu University Institutional Repository and the library's digital collections, at catalog.lib.kyushu-u.ac.jp. That endpoint is unusual for this cohort — most Japanese university repositories are tenants on NII's JAIRO Cloud, while Kyushu runs the protocol implementation itself on its own registrable domain, with a kyushu-u.ac.jp administrative contact, four metadata formats and seven collection sets. Everything else is a relationship rather than a contract: the university operates its own SAML 2.0 Shibboleth Identity Provider registered in the GakuNin national federation since 2011 and exported to eduGAIN; it is a DataCite consortium organization under the Japan Link Center and a Crossref member through two units; its research portal is an Elsevier Pure tenant whose live OpenAPI is Elsevier's contract, not Kyushu's, and is deliberately not saved here. There is no central developer portal, no API key issuance, no open-data platform, no llms.txt, no MCP server and no OpenAPI published anywhere on kyushu-u.ac.jp. The public syllabus and the Genkai supercomputer portals are HTML and login walls, not APIs.

**Areas:** University · Higher Education · Education · Research · Japan · National University · Public Research University · Institutional Repository · Research Data · Identity Federation · Library · Course Catalog

## Kyushu University on APIs.io

Everything profiled for Kyushu University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kyushu/](https://apis.io/providers/kyushu/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [QIR / Kyushu University Collections Bulk Metadata (TSV via Handle)](https://apis.io/apis/kyushu/qir-bulk-tsv/) — Quarterly full-metadata TSV exports for the Kyushu University Library digital collections, distributed through the Handle system under the university's own…
- [GakuNin Shibboleth Identity Provider](https://apis.io/apis/kyushu/gakunin-shibboleth-idp/) — Kyushu University's own SAML 2.0 Identity Provider, registered in GakuNin — the Japanese academic access-management federation operated by NII — and…
- [DataCite DOI Registration Membership](https://apis.io/apis/kyushu/datacite-membership/) — Kyushu University is a DataCite consortium organization — provider id `kyushuu`, symbol KYUSHUU, region APAC, country JP, active since 2023-02-28 — inside…
- [Crossref DOI Registration Membership](https://apis.io/apis/kyushu/crossref-membership/) — Two Kyushu University units are Crossref members registering DOIs under their own prefixes, verified against api.crossref.org on 2026-09-01 — member 3044…
- [ROR Organization Record](https://apis.io/apis/kyushu/ror-registration/) — Kyushu University's Research Organization Registry record, ROR ID 00p4k0j84, carrying the English, romanized (Kyūshū Daigaku) and Japanese (九州大学) names. The…
- [Kyushu University Pure Research Portal (Elsevier tenant)](https://apis.io/apis/kyushu/pure-research-portal/) — Kyushu University's research information portal, an Elsevier Pure tenant at kyushu-u.elsevierpure.com. The researchers, publications, organizational units…
- [Genkai Supercomputer System (Research Institute for Information Technology)](https://apis.io/apis/kyushu/genkai-research-computing/) — Kyushu University's research computing service, operated by the Research Institute for Information Technology (RIIT) around the Genkai supercomputer. Three…
- [Kyushu University Repository API](https://apis.io/apis/kyushu/kyushu-repository-api/) — Verbs describing the repository itself — its identity, its metadata formats and its sets.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Kyushu Context](https://apis.io/jsonld/kyushu/kyushu-context/)

#### Examples (4)

Example requests and responses.

- [Kyushu Qir Oai Pmh Getrecord Example](https://apis.io/examples/kyushu/kyushu-qir-oai-pmh-getrecord-example/)
- [Kyushu Qir Oai Pmh Identify Example](https://apis.io/examples/kyushu/kyushu-qir-oai-pmh-identify-example/)
- [Kyushu Qir Oai Pmh Listmetadataformats Example](https://apis.io/examples/kyushu/kyushu-qir-oai-pmh-listmetadataformats-example/)
- [Kyushu Qir Oai Pmh Listsets Example](https://apis.io/examples/kyushu/kyushu-qir-oai-pmh-listsets-example/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Kyushu Authentication](https://apis.io/security/kyushu/kyushu-authentication/)
- [Kyushu Domain Security](https://apis.io/security/kyushu/kyushu-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kyushu Plans Pricing](https://apis.io/plans/kyushu/kyushu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kyushu Rate Limits](https://apis.io/rate-limits/kyushu/kyushu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kyushu Finops](https://apis.io/finops/kyushu/kyushu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kyushu-u.ac.jp/en/)
- [Documentation](https://www.lib.kyushu-u.ac.jp/en/metadata)
- [Support](https://www.kyushu-u.ac.jp/en/contact/)
- [Blog](https://www.kyushu-u.ac.jp/en/news/)
- [Terms of service](https://www.kyushu-u.ac.jp/en/website/sitepolicy)
- [Privacy policy](https://www.kyushu-u.ac.jp/en/website/privacypolicy)
- [GitHub](https://github.com/RIIT-KyushuUniv)

## API Evangelist rating

**Kin Score 27.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 22.3 |
| Contract governance | 19.7 |
| Operational transparency | 7.9 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 20.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kyushu/](https://apis.io/providers/kyushu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kyushu University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kyushu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
