# OpenLLMetry (openllmetry)

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
