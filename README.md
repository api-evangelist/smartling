# Smartling

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

**Areas:** Localization · Translation · TMS · LinguisticAI · Neural MT · Enterprise · REST

## Smartling on APIs.io

Everything profiled for Smartling is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/smartling/](https://apis.io/providers/smartling/)** — or go straight to one of the APIs or properties below.

### APIs (19)

- [Smartling REST API](https://apis.io/apis/smartling/api-v2/) — Smartling's REST API for the translation management platform. Resource groups include Authentication, Accounts, Projects, Source Files, Strings,…
- [Smartling Account & Projects API](https://apis.io/apis/smartling/smartling-account-projects-api/) — Each client within Smartling is given their own account with a designated `accountUid`. Within each account is any number of projects. All files, content,…
- [Smartling Attachments API](https://apis.io/apis/smartling/smartling-attachments-api/) — The Attachments API allows for file attachment upload, download and checking linked attachments for an entity. Attachment entities can be from three…
- [Smartling Authentication API](https://apis.io/apis/smartling/smartling-authentication-api/) — Smartling uses OAuth2 for [authentication](https://help.smartling.com/hc/en-us/articles/1260805176849). To access the Smartling APIs, you'll first need to…
- [Smartling Content Search API](https://apis.io/apis/smartling/smartling-content-search-api/) — The Content Search API allows you to search for strings within a Smartling project. You can filter by string text, hashcode, namespace, or any combination…
- [Smartling Context API](https://apis.io/apis/smartling/smartling-context-api/) — [Visual context](https://help.smartling.com/hc/en-us/articles/360057484273) helps Translators make linguistic, layout, and spacing decisions based on where…
- [Smartling Estimates API](https://apis.io/apis/smartling/smartling-estimates-api/) — The Estimates API from Smartling — 6 operation(s) for estimates.
- [Smartling Files API](https://apis.io/apis/smartling/smartling-files-api/) — Files are typically how you can exchange your content with Smartling to get translations. Smartling supports a wide variety of [file…
- [Smartling GDN url management API](https://apis.io/apis/smartling/smartling-gdn-url-management-api/) — The GDN url management API from Smartling — 4 operation(s) for gdn url management.
- [Smartling Jobs API](https://apis.io/apis/smartling/smartling-jobs-api/) — A Smartling project (such as a mobile, web, files, or connector project) may contain one or more…
- [Smartling Language Detection API](https://apis.io/apis/smartling/smartling-language-detection-api/) — The Language Detection API from Smartling — 1 operation(s) for language detection.
- [Smartling Locales API](https://apis.io/apis/smartling/smartling-locales-api/) — Locales are the language and country pairs that are used to identify the source content and the desired target locale for your translated content.
- [Smartling Machine Translation (MT) API](https://apis.io/apis/smartling/smartling-machine-translation-mt-api/) — The Smartling platform offers state-of-the-art [Machine Translation capabilities](https://www.smartling.com/software/neural-machine-translation-hub/)…
- [Smartling People API](https://apis.io/apis/smartling/smartling-people-api/) — Smartling users, who process and translate content with the Smartling platform.
- [Smartling Reports API](https://apis.io/apis/smartling/smartling-reports-api/) — The Reports API allows to request various reports available on Smartling platform and specify additional filtering criteria to narrow down data returned by…
- [Smartling Strings API](https://apis.io/apis/smartling/smartling-strings-api/) — A string is a piece of translation. Based on the source content, strings can be parsed differently. A string is then broken down further, into one or more…
- [Smartling Tags API](https://apis.io/apis/smartling/smartling-tags-api/) — Tags can help you manage your strings. The Tags API allows you to add/remove string tags, and search for tags in a project.
- [Smartling Vendors API](https://apis.io/apis/smartling/smartling-vendors-api/) — The Vendors API is for Language Service Providers to view work that's available in Smartling.
- [Smartling Workflow Assignment API](https://apis.io/apis/smartling/smartling-workflow-assignment-api/) — The Workflow Assignment API handles workflow step assignments for non agency users.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/smartling/](https://apis.io/graphqls/smartling/smartling-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [smartling](https://apis.io/servers/smartling/smartling/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Smartling Agentic Access](https://apis.io/agentic-access/smartling/smartling-agentic-access/)

#### Collections (19)

Postman and Open Collection request collections.

- [Smartling REST API Reference](https://apis.io/collections/smartling/open-smartling/)
- [Smartling REST API Reference Account & Projects API](https://apis.io/collections/smartling/open-smartling-account-projects-api/)
- [Smartling REST API Reference Account & Projects Attachments API](https://apis.io/collections/smartling/open-smartling-attachments-api/)
- [Smartling REST API Reference Account & Projects Authentication API](https://apis.io/collections/smartling/open-smartling-authentication-api/)
- [Smartling REST API Reference Account & Projects Content Search API](https://apis.io/collections/smartling/open-smartling-content-search-api/)
- [Smartling REST API Reference Account & Projects Context API](https://apis.io/collections/smartling/open-smartling-context-api/)
- [Smartling REST API Reference Account & Projects Estimates API](https://apis.io/collections/smartling/open-smartling-estimates-api/)
- [Smartling REST API Reference Account & Projects Files API](https://apis.io/collections/smartling/open-smartling-files-api/)
- [Smartling REST API Reference Account & Projects GDN url management API](https://apis.io/collections/smartling/open-smartling-gdn-url-management-api/)
- [Smartling REST API Reference Account & Projects Jobs API](https://apis.io/collections/smartling/open-smartling-jobs-api/)
- [Smartling REST API Reference Account & Projects Language Detection API](https://apis.io/collections/smartling/open-smartling-language-detection-api/)
- [Smartling REST API Reference Account & Projects Locales API](https://apis.io/collections/smartling/open-smartling-locales-api/)
- [Smartling REST API Reference Account & Projects Machine Translation (MT) API](https://apis.io/collections/smartling/open-smartling-machine-translation-mt-api/)
- [Smartling REST API Reference Account & Projects People API](https://apis.io/collections/smartling/open-smartling-people-api/)
- [Smartling REST API Reference Account & Projects Reports API](https://apis.io/collections/smartling/open-smartling-reports-api/)
- [Smartling REST API Reference Account & Projects Strings API](https://apis.io/collections/smartling/open-smartling-strings-api/)
- [Smartling REST API Reference Account & Projects Tags API](https://apis.io/collections/smartling/open-smartling-tags-api/)
- [Smartling REST API Reference Account & Projects Vendors API](https://apis.io/collections/smartling/open-smartling-vendors-api/)
- [Smartling REST API Reference Account & Projects Workflow Assignment API](https://apis.io/collections/smartling/open-smartling-workflow-assignment-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Smartling Domain Security](https://apis.io/security/smartling/smartling-domain-security/)
- [Smartling Trust Center](https://apis.io/security/smartling/smartling-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Smartling Plans Pricing](https://apis.io/plans/smartling/smartling-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Smartling Rate Limits](https://apis.io/rate-limits/smartling/smartling-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Smartling Finops](https://apis.io/finops/smartling/smartling-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.smartling.com/)
- [Documentation](https://api-reference.smartling.com/)
- [Blog](https://www.smartling.com/blog/rss.xml)

## API Evangelist rating

**Kin Score 33.2** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 48.9 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 47.6 |
| Access clarity | 13.2 |

**Agent readiness 56.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/smartling/](https://apis.io/providers/smartling/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Smartling: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/smartling/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
