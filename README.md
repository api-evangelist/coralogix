# Coralogix

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

Coralogix is a comprehensive observability platform that delivers real‑time log analytics, metrics, tracing, and AI‑driven insights. It enables developers, DevOps, and SRE teams to monitor applications, infrastructure, and services across cloud, on‑premise, and hybrid environments. Features include infinite data retention, customizable dashboards, alerting, OpenTelemetry support, and integrations with major cloud providers and third‑party tools, helping organizations ensure performance, reliability, and security at scale.

**Areas:** AIOps · Observability · Monitoring · Cloud · DevOps

## Coralogix on APIs.io

Everything profiled for Coralogix is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coralogix/](https://apis.io/providers/coralogix/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Coralogix](https://apis.io/apis/coralogix/coralogix/) — Coralogix is an observability platform providing log analytics, metrics, tracing, and AI-powered insights.
- [Coralogix Dashboards API](https://apis.io/apis/coralogix/coralogix-dashboards-api/) — The Dashboards API from Coralogix — 7 operation(s) for dashboards.
- [Coralogix Dataprime API](https://apis.io/apis/coralogix/coralogix-dataprime-api/) — The Dataprime API from Coralogix — 2 operation(s) for dataprime.
- [Coralogix Mgmt API](https://apis.io/apis/coralogix/coralogix-mgmt-api/) — The Mgmt API from Coralogix — 1 operation(s) for mgmt.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Coralogix Streaming Surfaces](https://apis.io/asyncapis/coralogix/coralogix-asyncapi/)

#### Event channels (5)

Individual events and webhooks the provider emits.

- [otlp/logs](https://apis.io/channels/coralogix/otlp-logs/)
- [otlp/metrics](https://apis.io/channels/coralogix/otlp-metrics/)
- [otlp/traces](https://apis.io/channels/coralogix/otlp-traces/)
- [outbound/alert-webhook](https://apis.io/channels/coralogix/outbound-alert-webhook/)
- [prometheus/v1](https://apis.io/channels/coralogix/prometheus-v1/)

#### JSON Schema (6)

The data models the API reads and writes.

- [GetDashboardsDashboardsV1DashboardidResponse](https://apis.io/schemas/coralogix/coralogix-get-dashboards-dashboards-v1-dashboardid-response/)
- [GetDashboardsDashboardsV1SlugsSlugResponse](https://apis.io/schemas/coralogix/coralogix-get-dashboards-dashboards-v1-slugs-slug-response/)
- [PostDashboardsDashboardsV1Request](https://apis.io/schemas/coralogix/coralogix-post-dashboards-dashboards-v1-request/)
- [PostDashboardsDashboardsV1Response](https://apis.io/schemas/coralogix/coralogix-post-dashboards-dashboards-v1-response/)
- [PostMgmtOpenapi5Request](https://apis.io/schemas/coralogix/coralogix-post-mgmt-openapi5-request/)
- [PutDashboardsDashboardsV1Request](https://apis.io/schemas/coralogix/coralogix-put-dashboards-dashboards-v1-request/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Coralogix Context](https://apis.io/jsonld/coralogix/coralogix-context/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Coralogix — asyncapi rules](https://apis.io/rules/coralogix/coralogix-asyncapi-spectral-rules/)
- [Coralogix API Rules](https://apis.io/rules/coralogix/coralogix-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Coralogix Domain Security](https://apis.io/security/coralogix/coralogix-domain-security/)
- [Coralogix Trust Center](https://apis.io/security/coralogix/coralogix-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coralogix Plans Pricing](https://apis.io/plans/coralogix/coralogix-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Coralogix Rate Limits](https://apis.io/rate-limits/coralogix/coralogix-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Coralogix Finops](https://apis.io/finops/coralogix/coralogix-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://coralogix.com)
- [Documentation](https://coralogix.com/docs)
- [Getting started](https://coralogix.com/docs/user-guides/getting-started/)
- [API reference](https://coralogix.com/docs/api-reference/)
- [Pricing](https://coralogix.com/pricing/)
- [Sign up](https://signup.coralogix.com/)
- [Support](https://coralogix.com/support/)
- [Blog](https://coralogix.com/feed/)
- [Compliance](https://trust.coralogix.com/)
- [Terms of service](https://coralogix.com/terms-conditions/)
- [Privacy policy](https://coralogix.com/privacy-policy/)
- [GitHub](https://github.com/coralogix)

## API Evangelist rating

**Kin Score 56.5** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 66.2 |
| Contract governance | 35.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 52.4 |
| Access clarity | 68.4 |

**Agent readiness 39.0** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coralogix/](https://apis.io/providers/coralogix/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coralogix: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coralogix/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
