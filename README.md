# CAST AI

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

CAST AI is an Application Performance Automation (APA) platform for Kubernetes that automates cost optimization, autoscaling, workload rightsizing, GPU/LLM workload placement, spot instance selection, and security posture analysis. The platform works across AWS, GCP, Azure, Oracle Cloud, IBM Cloud, AliCloud and on-premises distributions (EKS, GKE, AKS, OpenShift, Rancher, kOps). Everything available in the console UI is also accessible via the REST API at api.cast.ai.

**Areas:** Auto-Scaling · Cloud Infrastructure · Cost Optimization · DevOps · FinOps · Kubernetes · Observability

## CAST AI on APIs.io

Everything profiled for CAST AI is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/cast-ai/](https://apis.io/providers/cast-ai/)** — or go straight to one of the APIs or properties below.

### APIs (17)

- [CAST AI AI Enabler API](https://apis.io/apis/cast-ai/cast-ai-ai-enabler-api/) — Manage LLM provider integrations and AI enabler functionality for intelligent optimization.
- [CAST AI Allocation Groups API](https://apis.io/apis/cast-ai/cast-ai-allocation-groups-api/) — Manage allocation groups and view efficiency metrics for grouped workloads.
- [CAST AI Autoscaler API](https://apis.io/apis/cast-ai/cast-ai-autoscaler-api/) — Autoscaler operations including triggering rebalancing plans and managing cluster scaling behavior.
- [CAST AI Cluster Actions API](https://apis.io/apis/cast-ai/cast-ai-cluster-actions-api/) — Manage cluster controller actions including acknowledging completed actions and ingesting logs.
- [CAST AI Cost Reports API](https://apis.io/apis/cast-ai/cast-ai-cost-reports-api/) — Access cost reporting and efficiency data at the cluster, namespace, and workload levels.
- [CAST AI External Clusters API](https://apis.io/apis/cast-ai/cast-ai-external-clusters-api/) — Manage external Kubernetes clusters connected to CAST AI, including listing nodes, draining nodes, and cluster operations.
- [CAST AI Hibernation Schedules API](https://apis.io/apis/cast-ai/cast-ai-hibernation-schedules-api/) — Create and manage hibernation schedules for clusters to reduce costs during off-peak hours.
- [CAST AI Insights API](https://apis.io/apis/cast-ai/cast-ai-insights-api/) — Access security insights, best practices reports, and container image scanning information.
- [CAST AI Inventory API](https://apis.io/apis/cast-ai/cast-ai-inventory-api/) — Manage inventory resources and blacklists for instance types and regions.
- [CAST AI Node Configuration API](https://apis.io/apis/cast-ai/cast-ai-node-configuration-api/) — Manage node configurations for clusters, which define how nodes are provisioned and configured.
- [CAST AI Node Templates API](https://apis.io/apis/cast-ai/cast-ai-node-templates-api/) — Manage node templates that define instance types, constraints, and configuration for autoscaled nodes.
- [CAST AI Operations API](https://apis.io/apis/cast-ai/cast-ai-operations-api/) — Track and manage long-running operations within CAST AI.
- [CAST AI Policies API](https://apis.io/apis/cast-ai/cast-ai-policies-api/) — Manage autoscaler policies configuration for clusters, including unscheduled pods, node downscaler, and spot instance policies.
- [CAST AI Pricing API](https://apis.io/apis/cast-ai/cast-ai-pricing-api/) — Access pricing information for cloud provider instances and sync billing data.
- [CAST AI Scheduled Rebalancing API](https://apis.io/apis/cast-ai/cast-ai-scheduled-rebalancing-api/) — Create and manage scheduled rebalancing jobs that periodically optimize cluster node allocation.
- [CAST AI Settings API](https://apis.io/apis/cast-ai/cast-ai-settings-api/) — Manage API key settings and organization-level configuration.
- [CAST AI Workload Optimization API](https://apis.io/apis/cast-ai/cast-ai-workload-optimization-api/) — Manage workload optimization settings, view workload recommendations, and configure workload autoscaling.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/cast-ai/](https://apis.io/servers/cast-ai/cast-ai/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Cast Ai Agentic Access](https://apis.io/agentic-access/cast-ai/cast-ai-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [CAST AI Cluster](https://apis.io/schemas/cast-ai/cluster/)
- [CAST AI Cost Report](https://apis.io/schemas/cast-ai/cost-report/)
- [CAST AI Node](https://apis.io/schemas/cast-ai/node/)
- [CAST AI Node Template](https://apis.io/schemas/cast-ai/node-template/)
- [CAST AI Rebalancing Schedule](https://apis.io/schemas/cast-ai/rebalancing-schedule/)
- [CAST AI Workload](https://apis.io/schemas/cast-ai/workload/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Cast Ai Context](https://apis.io/jsonld/cast-ai/cast-ai-context/)

#### Collections (35)

Postman and Open Collection request collections.

- [CAST AI Kubernetes Cost Optimization AI Enabler API](https://apis.io/collections/cast-ai/open-cast-ai-ai-enabler-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Allocation Groups API](https://apis.io/collections/cast-ai/open-cast-ai-allocation-groups-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Autoscaler API](https://apis.io/collections/cast-ai/open-cast-ai-autoscaler-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Cluster Actions API](https://apis.io/collections/cast-ai/open-cast-ai-cluster-actions-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Cost Reports API](https://apis.io/collections/cast-ai/open-cast-ai-cost-reports-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler External Clusters API](https://apis.io/collections/cast-ai/open-cast-ai-external-clusters-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Hibernation Schedules API](https://apis.io/collections/cast-ai/open-cast-ai-hibernation-schedules-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Insights API](https://apis.io/collections/cast-ai/open-cast-ai-insights-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Inventory API](https://apis.io/collections/cast-ai/open-cast-ai-inventory-api/)
- [CAST AI Kubernetes Cost Optimization API](https://apis.io/collections/cast-ai/open-cast-ai-kubernetes-cost-optimization/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Node Configuration API](https://apis.io/collections/cast-ai/open-cast-ai-node-configuration-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Node Templates API](https://apis.io/collections/cast-ai/open-cast-ai-node-templates-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Operations API](https://apis.io/collections/cast-ai/open-cast-ai-operations-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Policies API](https://apis.io/collections/cast-ai/open-cast-ai-policies-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Pricing API](https://apis.io/collections/cast-ai/open-cast-ai-pricing-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Scheduled Rebalancing API](https://apis.io/collections/cast-ai/open-cast-ai-scheduled-rebalancing-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Settings API](https://apis.io/collections/cast-ai/open-cast-ai-settings-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Workload Optimization API](https://apis.io/collections/cast-ai/open-cast-ai-workload-optimization-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler API](https://apis.io/collections/cast-ai/postman-cast-ai-ai-enabler-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Allocation Groups API](https://apis.io/collections/cast-ai/postman-cast-ai-allocation-groups-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Autoscaler API](https://apis.io/collections/cast-ai/postman-cast-ai-autoscaler-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Cluster Actions API](https://apis.io/collections/cast-ai/postman-cast-ai-cluster-actions-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Cost Reports API](https://apis.io/collections/cast-ai/postman-cast-ai-cost-reports-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler External Clusters API](https://apis.io/collections/cast-ai/postman-cast-ai-external-clusters-api/)
- [CAST AI Kubernetes Cost Optimization AI Enabler Hibernation Schedules API](https://apis.io/collections/cast-ai/postman-cast-ai-hibernation-schedules-api/)
- …and 10 more published on APIs.io

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [CAST AI — jsonschema rules](https://apis.io/rules/cast-ai/cast-ai-jsonschema-spectral-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Cast Ai Authentication](https://apis.io/security/cast-ai/cast-ai-authentication/)
- [Cast Ai Domain Security](https://apis.io/security/cast-ai/cast-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Cast Ai Plans Pricing](https://apis.io/plans/cast-ai/cast-ai-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Cast Ai Rate Limits](https://apis.io/rate-limits/cast-ai/cast-ai-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Cast Ai Finops](https://apis.io/finops/cast-ai/cast-ai-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://cast.ai/)
- [Documentation](https://docs.cast.ai/docs/)
- [Getting started](https://docs.cast.ai/docs/getting-started)
- [Pricing](https://cast.ai/pricing/)
- [Support](https://cast.ai/support/)
- [Changelog](https://docs.cast.ai/changelog)
- [Blog](https://cast.ai/blog/)
- [Terms of service](https://cast.ai/terms-of-service/)
- [Privacy policy](https://cast.ai/privacy-policy/)
- [Status](https://status.cast.ai/)

## API Evangelist rating

**Kin Score 45.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 61.1 |
| Contract governance | 9.8 |
| Operational transparency | 47.4 |
| Developer ergonomics | 20.2 |
| Access clarity | 39.5 |

**Agent readiness 30.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/cast-ai/](https://apis.io/providers/cast-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for CAST AI: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/cast-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
