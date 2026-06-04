# United Arab Emirates University (united-arab-emirates-university)

United Arab Emirates University (UAEU) is a public research university in Al Ain, United Arab Emirates, ranked #262 in the QS World University Rankings 2025. This repository catalogs UAEU's public, machine-readable developer/API footprint as an APIs.json provider profile. UAEU's footprint is research- and open-data-oriented: the UAEU Library runs the Scholarworks@UAEU institutional repository with an OAI-PMH endpoint, and UAEU publishes open datasets via the UAE national CKAN open data portal. No self-service developer portal was found.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/united-arab-emirates-university/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=united-arab-emirates-university-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Institutional Repository, OAI-PMH, CKAN, United Arab Emirates, Middle East

## APIs

- **Scholarworks@UAEU OAI-PMH Repository API** — OAI-PMH 2.0 metadata harvesting endpoint for the university's open-access institutional repository (bepress Digital Commons). Verified live. Docs: https://scholarworks.uaeu.ac.ae/about.html — Base: https://scholarworks.uaeu.ac.ae/do/oai/
- **UAEU Open Data on UAE National Portal (CKAN)** — UAEU datasets published on the FCSC national open data portal, which exposes a CKAN Action API (Cloudflare-gated for scripts). Docs: https://opendata.fcsc.gov.ae/@united-arab-emirates-university-uaeu — Base: https://opendata.fcsc.gov.ae/api/3/action/

## Plans / Rate Limits / FinOps

- Plans: [plans/united-arab-emirates-university-plans-pricing.yml](plans/united-arab-emirates-university-plans-pricing.yml)
- Rate Limits: [rate-limits/united-arab-emirates-university-rate-limits.yml](rate-limits/united-arab-emirates-university-rate-limits.yml)
- FinOps: [finops/united-arab-emirates-university-finops.yml](finops/united-arab-emirates-university-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uaeu.ac.ae/en/
- GitHub: https://github.com/uitsws (UAEU-DOIT / Division of IT; zero public repos)
- LinkedIn: https://www.linkedin.com/school/united-arab-emirates-university/
- Library: https://www.uaeu.ac.ae/en/library/
- Research: https://research.uaeu.ac.ae/

## Notes

- All cataloged endpoints were probed directly. The Scholarworks OAI-PMH endpoint returned a valid OAI-PMH 2.0 `Identify` response (HTTP 200).
- The FCSC CKAN Action API exists and is documented, but scripted requests return HTTP 403 due to Cloudflare bot mitigation; a browser session or API arrangement may be required.
- The UAEU Division of IT GitHub org (uitsws) exists but currently has no public repositories.
- No self-service developer portal, documented student-information / course-catalog / timetable API, or public mobile-app backend was found. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
