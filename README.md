# CAST AI (cast-ai)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cast-ai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Autoscaling
- Cloud Infrastructure
- Cost Optimization
- DevOps
- FinOps
- Kubernetes
- Observability

## Timestamps

- **Created:** 2024-07-02
- **Modified:** 2026-05-19

## APIs

### CAST AI Kubernetes Cost Optimization API

The CAST AI REST API provides comprehensive access to the Kubernetes cost optimization platform: cluster management, autoscaling and Karpenter integration, node configuration and templates, workload rightsizing, scheduled rebalancing, cost reporting, security insights, hibernation schedules, AI enabler / LLM workload optimization, and GPU/OMNI compute features. Authentication uses API keys and the API is served at api.cast.ai.

- **Human URL:** [https://docs.cast.ai/docs/api](https://docs.cast.ai/docs/api)
- **Base URL:** `https://api.cast.ai`

#### Tags

- Autoscaling
- Clusters
- Cost Optimization
- FinOps
- Hibernation
- Karpenter
- Kubernetes
- LLM
- Metrics
- Node Templates
- Nodes
- Policies
- Pricing
- Rebalancing
- Security
- Spot Instances
- Workloads

#### Properties

- [Documentation](https://docs.cast.ai/docs/api)
- [OpenAPI](openapi/cast-ai-kubernetes-cost-optimization-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cast-ai-kubernetes-cost-optimization.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cast-ai-kubernetes-cost-optimization.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Swagger](https://api.cast.ai/v1/spec/)
- [Authentication](https://docs.cast.ai/docs/authentication)
- [Changelog](https://docs.cast.ai/changelog)
- [JSON Schema](json-schema/cluster.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/node.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/node-template.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/workload.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rebalancing-schedule.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/cost-report.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/cast-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Website](https://cast.ai/)
- [Documentation](https://docs.cast.ai/docs/)
- [Getting Started](https://docs.cast.ai/docs/getting-started)
- [Authentication](https://docs.cast.ai/docs/authentication)
- [Changelog](https://docs.cast.ai/changelog)
- [Pricing](https://cast.ai/pricing/)
- [Blog](https://cast.ai/blog/)
- [Case Studies](https://cast.ai/case-studies/)
- [Customers](https://cast.ai/case-studies/)
- [Partners](https://cast.ai/partners/)
- [Support](https://cast.ai/support/)
- [Status Page](https://status.cast.ai/)
- [Security Policy](https://cast.ai/security/)
- [Terms of Service](https://cast.ai/terms-of-service/)
- [Privacy Policy](https://cast.ai/privacy-policy/)
- [Git Hub](https://github.com/castai/)
- [Slack](https://castai-community.slack.com/)
- [X (Twitter)](https://x.com/cast_ai/)
- [LinkedIn](https://www.linkedin.com/company/cast-ai/)
- [YouTube](https://www.youtube.com/@CASTAI)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://cast.ai/integrations/)
- [L L Ms Txt](https://docs.cast.ai/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
