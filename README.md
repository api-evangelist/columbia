# Columbia University (columbia)

Columbia University is a private Ivy League research university in New York City, ranked #18 in the QS World University Rankings 2025. This repository catalogs Columbia's public developer and API footprint as an [APIs.json](https://apisjson.org) profile. That footprint is modest and largely gated: the central Open Data Service publishes JSON/XML data feeds behind a UNI login, the Libraries offer the CLIO catalog as open MARCXML bulk data, and CUIT documents CAS/Shibboleth identity integration.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/columbia/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=columbia-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Open Data, Library, Identity, United States

## APIs

- **Columbia Open Data Service** — JSON/XML data feeds (course directory, CLIO, building access) gated behind a Columbia UNI login. Docs: https://opendataservice.columbia.edu/about
- **CLIO Library Catalog Open Data** — Open MARCXML bulk extracts of the Libraries catalog, monthly, CC0. Docs: https://library.columbia.edu/bts/clio-data.html · Base: https://lito.cul.columbia.edu/extracts/ColumbiaLibraryCatalog/full/
- **CU Directory of Classes** — Public web class directory; no official API (unofficial JSON/CSV crawl at soid/columbia-catalog-data). Docs: https://doc.sis.columbia.edu/
- **Columbia Identity (CAS / Shibboleth SAML)** — UNI-based web authentication and SAML 2.0 federation (InCommon). Docs: https://www.cuit.columbia.edu/web-authentication-federation

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/columbia-plans-pricing.yml](plans/columbia-plans-pricing.yml)
- Rate Limits: [rate-limits/columbia-rate-limits.yml](rate-limits/columbia-rate-limits.yml)
- FinOps: [finops/columbia-finops.yml](finops/columbia-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.columbia.edu/
- Developer Portal: https://opendataservice.columbia.edu/
- GitHub (Libraries): https://github.com/cul
- GitHub (IT): https://github.com/columbia-it
- Authentication: https://www.cuit.columbia.edu/web-authentication-federation
- LinkedIn: https://www.linkedin.com/school/columbia-university/
- Review: [review.yml](review.yml)

## Notes

- All entries reflect only what could be publicly confirmed; no endpoints were fabricated. The Open Data Service feeds require a Columbia UNI and could not be exercised anonymously.
- Several Columbia URLs return HTTP 403 to non-browser clients (bot blocking) but resolve normally in a browser.
- The `columbia.developer.azure-api.net` portal that appears in search results belongs to Columbia Sportswear (apparel company), not Columbia University, and was deliberately excluded.

## Maintainers

- Kin Lane — kin@apievangelist.com
