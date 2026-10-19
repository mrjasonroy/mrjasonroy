# Jason Roy

CTO at [CompareNetworks](https://www.comparenetworks.com) in San Francisco. I still write code every day, mostly agent platforms and data platforms.

Most of my work lives in private company repos, so here's what's behind the contribution graph:

- **Agent framework.** I wrote the framework our company builds AI on: pydantic-ai agents on Temporal, so a long run that fails resumes instead of starting over, plus the skill framework, governed tool access through Keycloak RBAC, and CI and autoscaling on Kubernetes and Knative. An engineer wrote the FastAPI/MCP layer it runs on. It runs 20+ MCP servers and a dozen agents in production, with regression evals on every agent.
- **Agent-based development.** Both engineering teams I oversee build fully with coding agents, locally and in CI. Agents write the code and do the code reviews.
- **Databricks lakehouse.** Lead architect of our company-wide lakehouse: 20+ source systems, governed gold tables, built test-first and shipped through Asset Bundles CI/CD.

Before that I co-founded imSMART, which Bigtincan acquired in 2022.

## Open source

- [**cache-components-cache-handler**](https://github.com/mrjasonroy/cache-components-cache-handler): a cache handler for Next.js 16+ Cache Components and `"use cache"`, with Redis, Valkey and ElastiCache backends and end-to-end tests against each one. About 28K npm downloads a month.

More at [jasonroy.com](https://jasonroy.com).
