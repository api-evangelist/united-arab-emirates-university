# United Arab Emirates University (united-arab-emirates-university)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
