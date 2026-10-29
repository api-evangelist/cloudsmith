# Cloudsmith

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

Cloudsmith is a cloud-native, universal package management platform providing fully managed, geo-replicated artifact repositories for over 30 package formats (Docker, npm, Maven, NuGet, PyPI, RubyGems, RPM, Deb, Helm, Cargo, Go, Composer, Conan, Conda, Vagrant, Raw, and more). The Cloudsmith REST API (v1) at api.cloudsmith.io exposes operations for organizations, repositories, packages, files, entitlements, vulnerabilities, webhooks, audit logs, metrics, quotas, deny policies, namespaces, distros, formats, recycle bin, storage regions, and broadcasts. Authentication is via API key passed in the Authorization header as "token YOUR_API_KEY".

**Areas:** Artifact Management · Developer Tools · DevOps · DevSecOps · Distribution · Package Management · Registry · Repository · Software Supply Chain · Universal · Vulnerability Scanning

## Cloudsmith on APIs.io

Everything profiled for Cloudsmith is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cloudsmith/](https://apis.io/providers/cloudsmith/)** — or go straight to one of the APIs or properties below.

### APIs (22)

- [Cloudsmith Audit Log API](https://apis.io/apis/cloudsmith/cloudsmith-audit-log-api/) — The audit-log API from Cloudsmith — 2 operation(s) for audit-log.
- [Cloudsmith Badges API](https://apis.io/apis/cloudsmith/cloudsmith-badges-api/) — The badges API from Cloudsmith — 1 operation(s) for badges.
- [Cloudsmith Broadcasts API](https://apis.io/apis/cloudsmith/cloudsmith-broadcasts-api/) — The broadcasts API from Cloudsmith — 1 operation(s) for broadcasts.
- [Cloudsmith Bulk Action API](https://apis.io/apis/cloudsmith/cloudsmith-bulk-action-api/) — The bulk-action API from Cloudsmith — 1 operation(s) for bulk-action.
- [Cloudsmith Distros API](https://apis.io/apis/cloudsmith/cloudsmith-distros-api/) — The distros API from Cloudsmith — 2 operation(s) for distros.
- [Cloudsmith Entitlements API](https://apis.io/apis/cloudsmith/cloudsmith-entitlements-api/) — The entitlements API from Cloudsmith — 8 operation(s) for entitlements.
- [Cloudsmith Files API](https://apis.io/apis/cloudsmith/cloudsmith-files-api/) — The files API from Cloudsmith — 5 operation(s) for files.
- [Cloudsmith Formats API](https://apis.io/apis/cloudsmith/cloudsmith-formats-api/) — The formats API from Cloudsmith — 2 operation(s) for formats.
- [Cloudsmith Metrics API](https://apis.io/apis/cloudsmith/cloudsmith-metrics-api/) — The metrics API from Cloudsmith — 3 operation(s) for metrics.
- [Cloudsmith Namespaces API](https://apis.io/apis/cloudsmith/cloudsmith-namespaces-api/) — The namespaces API from Cloudsmith — 2 operation(s) for namespaces.
- [Cloudsmith Orgs API](https://apis.io/apis/cloudsmith/cloudsmith-orgs-api/) — The orgs API from Cloudsmith — 40 operation(s) for orgs.
- [Cloudsmith Packages API](https://apis.io/apis/cloudsmith/cloudsmith-packages-api/) — The packages API from Cloudsmith — 70 operation(s) for packages.
- [Cloudsmith Quota API](https://apis.io/apis/cloudsmith/cloudsmith-quota-api/) — The quota API from Cloudsmith — 4 operation(s) for quota.
- [Cloudsmith Rates API](https://apis.io/apis/cloudsmith/cloudsmith-rates-api/) — The rates API from Cloudsmith — 1 operation(s) for rates.
- [Cloudsmith Recycle Bin API](https://apis.io/apis/cloudsmith/cloudsmith-recycle-bin-api/) — The recycle-bin API from Cloudsmith — 2 operation(s) for recycle-bin.
- [Cloudsmith Repos API](https://apis.io/apis/cloudsmith/cloudsmith-repos-api/) — The repos API from Cloudsmith — 59 operation(s) for repos.
- [Cloudsmith Status API](https://apis.io/apis/cloudsmith/cloudsmith-status-api/) — The status API from Cloudsmith — 1 operation(s) for status.
- [Cloudsmith Storage Regions API](https://apis.io/apis/cloudsmith/cloudsmith-storage-regions-api/) — The storage-regions API from Cloudsmith — 2 operation(s) for storage-regions.
- [Cloudsmith User API](https://apis.io/apis/cloudsmith/cloudsmith-user-api/) — The user API from Cloudsmith — 4 operation(s) for user.
- [Cloudsmith Users API](https://apis.io/apis/cloudsmith/cloudsmith-users-api/) — The users API from Cloudsmith — 1 operation(s) for users.
- [Cloudsmith Vulnerabilities API](https://apis.io/apis/cloudsmith/cloudsmith-vulnerabilities-api/) — The vulnerabilities API from Cloudsmith — 4 operation(s) for vulnerabilities.
- [Cloudsmith Webhooks API](https://apis.io/apis/cloudsmith/cloudsmith-webhooks-api/) — The webhooks API from Cloudsmith — 2 operation(s) for webhooks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cloudsmith Agentic Access](https://apis.io/agentic-access/cloudsmith/cloudsmith-agentic-access/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cloudsmith Context](https://apis.io/jsonld/cloudsmith/cloudsmith-context/)

#### Collections (23)

Postman and Open Collection request collections.

- [Cloudsmith API (v1)](https://apis.io/collections/cloudsmith/open-cloudsmith/)
- [Cloudsmith API (v1) audit-log API](https://apis.io/collections/cloudsmith/open-cloudsmith-audit-log-api/)
- [Cloudsmith API (v1) audit-log badges API](https://apis.io/collections/cloudsmith/open-cloudsmith-badges-api/)
- [Cloudsmith API (v1) audit-log broadcasts API](https://apis.io/collections/cloudsmith/open-cloudsmith-broadcasts-api/)
- [Cloudsmith API (v1) audit-log bulk-action API](https://apis.io/collections/cloudsmith/open-cloudsmith-bulk-action-api/)
- [Cloudsmith API (v1) audit-log distros API](https://apis.io/collections/cloudsmith/open-cloudsmith-distros-api/)
- [Cloudsmith API (v1) audit-log entitlements API](https://apis.io/collections/cloudsmith/open-cloudsmith-entitlements-api/)
- [Cloudsmith API (v1) audit-log files API](https://apis.io/collections/cloudsmith/open-cloudsmith-files-api/)
- [Cloudsmith API (v1) audit-log formats API](https://apis.io/collections/cloudsmith/open-cloudsmith-formats-api/)
- [Cloudsmith API (v1) audit-log metrics API](https://apis.io/collections/cloudsmith/open-cloudsmith-metrics-api/)
- [Cloudsmith API (v1) audit-log namespaces API](https://apis.io/collections/cloudsmith/open-cloudsmith-namespaces-api/)
- [Cloudsmith API (v1) audit-log orgs API](https://apis.io/collections/cloudsmith/open-cloudsmith-orgs-api/)
- [Cloudsmith API (v1) audit-log packages API](https://apis.io/collections/cloudsmith/open-cloudsmith-packages-api/)
- [Cloudsmith API (v1) audit-log quota API](https://apis.io/collections/cloudsmith/open-cloudsmith-quota-api/)
- [Cloudsmith API (v1) audit-log rates API](https://apis.io/collections/cloudsmith/open-cloudsmith-rates-api/)
- [Cloudsmith API (v1) audit-log recycle-bin API](https://apis.io/collections/cloudsmith/open-cloudsmith-recycle-bin-api/)
- [Cloudsmith API (v1) audit-log repos API](https://apis.io/collections/cloudsmith/open-cloudsmith-repos-api/)
- [Cloudsmith API (v1) audit-log status API](https://apis.io/collections/cloudsmith/open-cloudsmith-status-api/)
- [Cloudsmith API (v1) audit-log storage-regions API](https://apis.io/collections/cloudsmith/open-cloudsmith-storage-regions-api/)
- [Cloudsmith API (v1) audit-log user API](https://apis.io/collections/cloudsmith/open-cloudsmith-user-api/)
- [Cloudsmith API (v1) audit-log users API](https://apis.io/collections/cloudsmith/open-cloudsmith-users-api/)
- [Cloudsmith API (v1) audit-log vulnerabilities API](https://apis.io/collections/cloudsmith/open-cloudsmith-vulnerabilities-api/)
- [Cloudsmith API (v1) audit-log webhooks API](https://apis.io/collections/cloudsmith/open-cloudsmith-webhooks-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Cloudsmith API Rules](https://apis.io/rules/cloudsmith/cloudsmith-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cloudsmith Authentication](https://apis.io/security/cloudsmith/cloudsmith-authentication/)
- [Cloudsmith Domain Security](https://apis.io/security/cloudsmith/cloudsmith-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cloudsmith Plans Pricing](https://apis.io/plans/cloudsmith/cloudsmith-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cloudsmith Rate Limits](https://apis.io/rate-limits/cloudsmith/cloudsmith-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cloudsmith Finops](https://apis.io/finops/cloudsmith/cloudsmith-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cloudsmith.com/)
- [Documentation](https://docs.cloudsmith.com/)
- [Getting started](https://help.cloudsmith.io/reference/getting-started-with-the-api)
- [API reference](https://docs.cloudsmith.com/api)
- [Blog](https://cloudsmith.com/blog)
- [Privacy policy](https://cloudsmith.com/legal/privacy-notice/)
- [Status](https://status.cloudsmith.io/)

## API Evangelist rating

**Kin Score 32.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 50.1 |
| Contract governance | 13.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 31.0 |
| Access clarity | 10.5 |

**Agent readiness 23.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cloudsmith/](https://apis.io/providers/cloudsmith/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Cloudsmith: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cloudsmith/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
