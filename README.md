# OpenLLMetry (openllmetry)

OpenLLMetry is an open-source observability framework for LLM and generative AI applications, built on top of OpenTelemetry. Maintained by Traceloop under the Apache 2.0 license, it provides drop-in instrumentation for 30+ LLM providers, vector databases, and agent frameworks, and emits standardized GenAI traces over OTLP to any observability backend. Its semantic conventions for LLMs have been upstreamed into the OpenTelemetry GenAI semantic conventions.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openllmetry/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=openllmetry-api-evangelist&utm_content=repo)

## Type

- **x-type:** opensource

## Tags

- AI, LLM, Observability, Open Source, OpenTelemetry, Tracing, GenAI

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

| API | Description |
|---|---|
| OpenLLMetry Traceloop SDK | One-call SDK that registers all instrumentations and exports GenAI traces over OTLP. |
| OpenLLMetry Semantic Conventions for AI | Standard span attribute vocabulary for LLM telemetry; upstreamed into OpenTelemetry GenAI semconv. |
| OpenLLMetry LLM Provider Instrumentations | OpenTelemetry instrumentations for OpenAI, Anthropic, Bedrock, Vertex AI, Cohere, Mistral, Ollama, Groq, Together, Replicate, SageMaker, Watsonx, and more. |
| OpenLLMetry Vector Database Instrumentations | Instrumentations for Chroma, Pinecone, Qdrant, Weaviate, LanceDB, Milvus, and Marqo. |
| OpenLLMetry Framework and Agent Instrumentations | Instrumentations for LangChain, LlamaIndex, Haystack, CrewAI, Agno, OpenAI Agents, and MCP. |
| OpenLLMetry OTLP Exporters | Standard OTLP export to Datadog, Grafana, Honeycomb, New Relic, Splunk, Langfuse, LangSmith, Braintrust, Traceloop, and any OTel-compatible backend. |

## Common Properties

- [Website](https://www.traceloop.com/openllmetry)
- [Documentation](https://www.traceloop.com/docs/openllmetry/introduction)
- [GitHub (Python)](https://github.com/traceloop/openllmetry)
- [GitHub (JS/TS)](https://github.com/traceloop/openllmetry-js)
- [License (Apache 2.0)](https://github.com/traceloop/openllmetry/blob/main/LICENSE)
- [Maintainer (Traceloop)](https://www.traceloop.com/)
- [Slack Community](https://traceloop.com/slack)
- [Getting Started (Python)](https://www.traceloop.com/docs/openllmetry/quick-start/python)
- [Integrations](https://www.traceloop.com/docs/openllmetry/integrations)
- [OpenTelemetry GenAI Semantic Conventions](https://opentelemetry.io/docs/specs/semconv/gen-ai/)

## Notes

OpenLLMetry is a client-side instrumentation framework, not a hosted REST API surface. It is delivered as a family of Python and TypeScript packages (`traceloop-sdk`, `@traceloop/node-server-sdk`, and 30+ `opentelemetry-instrumentation-*` packages) that emit OpenTelemetry spans over OTLP. No first-party OpenAPI specification, plans, rate-limit, or FinOps artifacts are generated for this repo — those concerns sit with the downstream observability backend the user exports to (Traceloop, Datadog, Grafana, Honeycomb, etc.).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
