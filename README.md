# Traceloop (traceloop)

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

Traceloop is an LLM reliability and observability platform built on OpenTelemetry that provides full visibility into every prompt, response, and failure across AI pipelines. The platform enables teams to monitor LLM quality in production, detect model drift and hallucinations, run automated evaluations via LLM-as-a-judge, and enforce quality gates in CI/CD workflows. Traceloop exposes a REST API for managing auto-monitor setups, running 40+ built-in evaluators (safety, faithfulness, PII, toxicity, structural validation), querying metrics and span warehouse data, and administering organizations and environments. The open-source OpenLLMetry SDK integrates in one line of code across Python, TypeScript, Go, and Ruby with support for 20+ LLM providers and major orchestration frameworks including LangChain, LlamaIndex, and CrewAI. Traceloop was acquired by ServiceNow in March 2026.

APIs.json: https://raw.githubusercontent.com/api-evangelist/traceloop/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=traceloop-api-evangelist&utm_content=repo

## Tags

- LLM Observability
- OpenTelemetry
- AI Monitoring
- Tracing
- Evaluation
- LLM Gateway
- Prompt Management
- Machine Learning

## APIs

### Traceloop REST API

REST API for managing LLM observability infrastructure including auto-monitor setups, evaluators, metrics, organizations, tracing privacy controls, cost reporting, and span warehouse queries. Authenticated with Bearer tokens generated from the Traceloop dashboard. Base URL: `https://api.traceloop.com`.

- Documentation: https://www.traceloop.com/docs/api-reference/introduction
- OpenAPI: https://www.traceloop.com/docs/openapi.json

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/traceloop-plans-pricing.yml](plans/traceloop-plans-pricing.yml)
- Rate Limits: [rate-limits/traceloop-rate-limits.yml](rate-limits/traceloop-rate-limits.yml)
- FinOps: [finops/traceloop-finops.yml](finops/traceloop-finops.yml)

**Free Forever:** $0/month — up to 50,000 spans/month, 5 seats, 24-hour data retention, monitoring dashboard, evaluation dashboard, CI/CD integration, prompt management.

**Enterprise:** Custom pricing — unlimited spans and seats, custom data retention (up to 720 hours), SOC 2 compliance, on-premises deployment, dedicated Slack support. Available on AWS, GCP, and Azure Marketplaces. 14-day free trial.

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

| Type | URL |
|------|-----|
| Website | https://www.traceloop.com/ |
| Documentation | https://docs.traceloop.com/ |
| GitHub Org | https://github.com/traceloop |
| LinkedIn | https://www.linkedin.com/company/traceloop |
| Blog | https://www.traceloop.com/blog |
| Pricing | https://www.traceloop.com/pricing |
| Status Page | https://status.traceloop.com/ |
| X (Twitter) | https://twitter.com/traceloopdev |

## Maintainers

- Kin Lane (kin@apievangelist.com)
