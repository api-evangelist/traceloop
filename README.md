# Traceloop (traceloop)

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
