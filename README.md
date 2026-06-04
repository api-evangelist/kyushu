# Kyushu University (kyushu)

Kyushu University (九州大学) is a national research university in Fukuoka, Japan, ranked #167 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. The verifiable public surface is concentrated in the Kyushu University Library, which exposes scholarly metadata from its institutional repository (QIR) over a live OAI-PMH 2.0 interface and via bulk TSV downloads. There is no central, institution-wide developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/kyushu/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=kyushu-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Research, Library, Institutional Repository, OAI-PMH, Open Access, Japan

## APIs

- **Kyushu University Institutional Repository (QIR) OAI-PMH** — Live OAI-PMH 2.0 metadata harvesting interface for QIR, run by the Kyushu University Library. Returns JPCOAR-schema metadata; supports Identify, GetRecord and ListRecords with date filtering and resumptionToken pagination.
  - Docs: https://www.lib.kyushu-u.ac.jp/ja/metadata
  - Base URL: https://catalog.lib.kyushu-u.ac.jp/mmd/mmd_api/oai-pmh/
- **QIR / Kyushu University Collections Bulk Metadata (TSV via Handle)** — Quarterly full-metadata TSV exports for the library's digital collections (repository, rare materials, seal images, coal images), distributed through the Handle system.
  - Docs: https://www.lib.kyushu-u.ac.jp/ja/metadata
  - Download: https://hdl.handle.net/2324/6625737

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/kyushu-plans-pricing.yml](plans/kyushu-plans-pricing.yml)
- Rate Limits: [rate-limits/kyushu-rate-limits.yml](rate-limits/kyushu-rate-limits.yml)
- FinOps: [finops/kyushu-finops.yml](finops/kyushu-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.kyushu-u.ac.jp/en/
- Developer Portal (library metadata): https://www.lib.kyushu-u.ac.jp/ja/metadata
- GitHub (RIIT, institute-level): https://github.com/RIIT-KyushuUniv
- LinkedIn: https://www.linkedin.com/school/kyushu-university/
- Review: [review.yml](review.yml)

## Notes

- Verification discipline: only endpoints confirmed live are cataloged as APIs. The QIR OAI-PMH endpoint returned a valid OAI-PMH 2.0 Identify response (repositoryName "Kyushu University Institutional Repository (QIR)", JPCOAR schema, adminEmail qir@jimu.kyushu-u.ac.jp).
- A legacy DSpace OAI endpoint (`qir.kyushu-u.ac.jp/dspace-oai`) no longer resolves; QIR has migrated to the WEKO-based `catalog.lib.kyushu-u.ac.jp` platform.
- The Elsevier Pure research portal and the Academic Staff researcher database are public for browsing but document no open/public API.
- `RIIT-KyushuUniv` is an institute-level GitHub org (Research Institute for Information Technology), not a central university account; no official university-wide GitHub org was confirmed.
- The LinkedIn school page returns an anti-bot 999 status to automated fetches; the URL uses the standard school slug.

## Maintainers

- Kin Lane — kin@apievangelist.com
