# GLEIF (gleif)

Global Legal Entity Identifier Foundation REST API for searching, retrieving, and validating Legal Entity Identifiers (LEIs) and associated organization reference data. GLEIF provides a free, open API that requires no authentication or registration, built on the GLEIF Golden Copy dataset and updated three times daily.

APIs.json: https://raw.githubusercontent.com/api-evangelist/gleif/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=gleif-api-evangelist&utm_content=repo

## Tags

- Legal Entity Identifier
- LEI
- vLEI
- Financial Data
- Corporate Identity
- Entity Verification
- Reference Data
- Open Data

## APIs

### GLEIF LEI API

The GLEIF LEI API provides programmatic access to the Global LEI System's full data pool. Supports searches by entity name, LEI code, BIC code, ISIN code, and corporate relationship structures. Free, open, and requires no authentication.

- **Base URL:** https://api.gleif.org/api/v1
- **Documentation:** https://www.gleif.org/en/lei-data/gleif-api
- **Postman Documentation:** https://documenter.getpostman.com/view/7679680/SVYrrxuU

## Plans / Rate Limits / FinOps

- **Plans:** [plans/gleif-plans-pricing.yml](plans/gleif-plans-pricing.yml) — Single free public access tier, no API key or registration required, unlimited use.
- **Rate Limits:** [rate-limits/gleif-rate-limits.yml](rate-limits/gleif-rate-limits.yml) — No publicly documented rate limits; bulk data via Golden Copy files recommended for high-volume use.
- **FinOps:** [finops/gleif-finops.yml](finops/gleif-finops.yml) — Zero direct cost; primary considerations are integration engineering time and data freshness strategy.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.gleif.org |
| Documentation | https://www.gleif.org/en/lei-data/gleif-api |
| GitHub Org | https://github.com/GLEIF-IT |
| LinkedIn | https://www.linkedin.com/company/global-legal-entity-identifier-foundation-gleif- |
| Blog | https://www.gleif.org/en/newsroom/blog |
| Pricing | https://www.gleif.org/en/lei-data/access-and-use-lei-data |
| Status Page | https://www.gleif.org/en/about/gleif-services/daily-service-availability |
| X | https://twitter.com/gleif |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
