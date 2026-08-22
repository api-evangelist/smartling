# Smartling (smartling)

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

Smartling is an enterprise translation management platform combining a cloud-based TMS, LinguisticAI, and neural machine translation. The Smartling REST API at api.smartling.com exposes authentication, accounts, projects, source files, strings, translations, jobs, glossary, issues, quality checks, MT, and reports. Authentication uses an OAuth-style userIdentifier + secret pair that returns a short-lived bearer access token (~5-10 minute TTL) with a refresh token.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/smartling/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/smartling/refs/heads/main/apis.yml)

## Tags

- Localization
- Translation
- TMS
- LinguisticAI
- Neural MT
- Enterprise
- REST

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Smartling REST API

Smartling's REST API for the translation management platform. Resource groups include Authentication, Accounts, Projects, Source Files, Strings, Translations, Jobs, Glossary, Issues, Quality Checks, MT, and Reports. Authentication via api.smartling.com/auth-api/v2/authenticate returns a bearer access token used in subsequent requests.

- **Human URL:** [https://api-reference.smartling.com/](https://api-reference.smartling.com/)
- **Base URL:** `https://api.smartling.com`

#### Tags

- REST
- OAuth
- Projects
- Files
- Translations
- Jobs
- Glossary
- Quality
- MT

#### Properties

- [Documentation](https://api-reference.smartling.com/)
- [Help Center](https://help.smartling.com/hc/en-us/articles/1260804843689-Overview-of-the-API)
- [Getting Started](https://help.smartling.com/hc/en-us/articles/1260804661570-Getting-Started-with-the-API)
- [Authentication](https://help.smartling.com/hc/en-us/articles/1260805176849-Authentication)
- [A P I Tokens](https://help.smartling.com/hc/en-us/articles/115004187694-API-Tokens)
- [SDK](https://github.com/Smartling/java-api-sdk)
- [Postman Collection](collections/smartling.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smartling.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.smartling.com/)
- [Documentation](https://api-reference.smartling.com/)
- [Help Center](https://help.smartling.com/)
- [Git Hub](https://github.com/Smartling)
- [LinkedIn](https://www.linkedin.com/company/smartling)
- [Plans](plans/smartling-plans-pricing.yml)
- [Rate Limits](rate-limits/smartling-rate-limits.yml)
- [Fin Ops](finops/smartling-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
