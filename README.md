# Toni Adreal

Backend, Infrastructure, and Product Engineer building verifiable AI and Web3 systems.

I work across the boundary between product decisions and implementation: TypeScript services, asynchronous jobs, PostgreSQL data models, Redis and BullMQ queues, security controls, API contracts, observability, and full-stack delivery. My current focus is making Tokenta's verification and settlement paths reproducible, testable, and easy to evaluate in public.

Based in Ningbo, China. Open to backend, infrastructure, full-stack, product engineering, and technical product roles.

## Selected Engineering Work

### [Tokenta Cleanverse Terminal](https://github.com/Tokenta/tokenta-cleanverse)

A React and TypeScript terminal backed by an asynchronous verification service and testnet settlement adapters.

- Verification pipeline with provider routing, abuse controls, probe budgets, lock-state transitions, scoring, and evidence records.
- In-process development defaults with opt-in PostgreSQL/Prisma persistence and Redis/BullMQ execution.
- Credential vault adapters, JWT/JWKS validation, request signatures, key zeroization, and audit trails.
- Prometheus metrics, health endpoints, worker topology, queue telemetry, and a Grafana dashboard definition.
- Credential-free unit, integration, end-to-end, database, and queue checks in [GitHub Actions](https://github.com/Tokenta/tokenta-cleanverse/actions).

Review the [architecture map](https://github.com/Tokenta/tokenta-cleanverse/blob/main/ARCHITECTURE.md), [server tests](https://github.com/Tokenta/tokenta-cleanverse/tree/main/server/src), [OpenAPI contracts](https://github.com/Tokenta/tokenta-cleanverse/tree/main/swagger/public/openapi), and [development runbook](https://github.com/Tokenta/tokenta-cleanverse/blob/main/docs/VERIFICATION-DEV-RUNBOOK.md).

### [API Inspector](https://github.com/Tokenta/api-inspector)

A zero-runtime-dependency TypeScript CLI for auditing LLM API endpoints.

- Provider adapters for OpenAI, Anthropic, Gemini, and OpenAI-compatible gateways.
- Reachability, authentication, model discovery, latency, context, fingerprint, and rate-limit evidence checks.
- A fixed, inspectable trust-score model rather than an opaque classifier.
- Deterministic [scoring and CLI tests](https://github.com/Tokenta/api-inspector/tree/main/test) across Node.js 20 and 22.

Review the [pipeline](https://github.com/Tokenta/api-inspector/blob/main/src/pipeline.ts), [scoring contract](https://github.com/Tokenta/api-inspector/blob/main/src/scoring.ts), and [CI workflow](https://github.com/Tokenta/api-inspector/actions/workflows/ci.yml).

## Engineering Evidence

| Area | Public evidence |
| --- | --- |
| Backend systems | Hono APIs, provider adapters, verification orchestration, queue workers, failure normalization |
| Data and jobs | Prisma migrations, PostgreSQL integration checks, Redis/BullMQ smoke tests, worker heartbeats |
| Reliability | Deterministic tests, end-to-end slices, health endpoints, Prometheus metrics, runbooks |
| Security | Credential isolation, encrypted vault paths, JWT/JWKS checks, signatures, zeroization, audit events |
| Full stack | React/Vite terminal, wallet authentication, typed API integration, deployable frontend build |
| Technical product | Architecture decisions, OpenAPI contracts, explicit degraded modes, roadmaps, contribution and security policies |

## Working Principles

- Evidence before claims: code, tests, and operational documentation should support every technical statement.
- Fail closed at trust boundaries: unavailable policy or invalid proof must not silently become approval.
- Keep required tests deterministic: paid APIs and live credentials belong in optional smoke checks.
- Make tradeoffs reviewable: architecture notes and API contracts are part of the product.

## Additional Work

- [Selected product and interface design portfolio](https://toni.tokenta.space/)
- [Design portfolio source](https://github.com/ToniAdreal/Toni_Design_Portfolio_Selected)

## Contact

- Email: [toniadreal11@gmail.com](mailto:toniadreal11@gmail.com)
- LinkedIn: [linkedin.com/in/toniadreal](https://www.linkedin.com/in/toniadreal)
- Portfolio: [toni.tokenta.space](https://toni.tokenta.space/)
