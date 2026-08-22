# Arcade (arcade)

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

Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Context Protocol tools that agent frameworks like LangChain, OpenAI Agents, CrewAI, AG2, Google ADK, Vercel AI, Mastra, and TanStack AI can call. This profile catalogs the public Arcade Engine API (39 endpoints across Admin, Authorization, Tools, LLM, Operations, Hooks, Gateways, and Plugins), the ArcadeAI GitHub org's SDKs, the arcade-mcp framework, and the public schemas repo.

**APIs.json:** [https://github.com/api-evangelist/arcade](https://github.com/api-evangelist/arcade)

## Scope

- **Type:** Index

## Tags

- Agents
- MCP
- AI Agents
- Authorization
- OAuth
- Tool Calling
- Agent Infrastructure
- LLM
- Integrations

## Timestamps

- **Created:** 2026-05-22
- **Modified:** 2026-05-22

## APIs

### Arcade Engine API

The Arcade Engine HTTP API — the control plane for tool catalogs, user authorization flows, tool execution, scheduled tools, MCP gateways, workers, hooks, plugins, and admin operations. Tagged surfaces are Admin, Authorization, Tools, LLM, Operations, Hooks, Gateways, and Plugins.

- **Human URL:** [https://docs.arcade.dev/en/references/api](https://docs.arcade.dev/en/references/api)
- **Base URL:** `https://api.arcade.dev`

#### Tags

- Engine
- Tool Calling
- Authorization
- MCP Runtime

#### Properties

- [Documentation](https://docs.arcade.dev)
- [API Reference](https://docs.arcade.dev/en/references/api)
- [OpenAPI](openapi/arcade-engine-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/arcade-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcade-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://api.arcade.dev/v1/swagger) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](rules/arcade-engine-rules.yml)
- [Authentication](https://docs.arcade.dev/guides/tool-calling/custom-apps/auth-tool-calling)
- [Quickstart](https://docs.arcade.dev/en/get-started/quickstarts/call-tool-agent)
- [Quickstart](https://docs.arcade.dev/en/get-started/quickstarts/mcp-server-quickstart)
- [SDK](https://github.com/ArcadeAI/arcade-py)
- [SDK](https://github.com/ArcadeAI/arcade-js)
- [SDK](https://github.com/ArcadeAI/arcade-go)
- [SDK](https://github.com/ArcadeAI/arcade-java)
- [SDK](https://github.com/ArcadeAI/arcade-dotnet)
- [C L I](https://docs.arcade.dev/en/references/arcade-cli)
- [Changelog](https://docs.arcade.dev/en/references/changelog)
- [JSON Schema](json-schema/arcade-engine-tool-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-tool-execution-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-execute-tool-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-execute-tool-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-authorize-tool-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-authorization-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-auth-provider-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-worker-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-hook-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-gateway-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-plugin-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-engine-secret-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/arcade-engine-tool-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-tool-execution-detail-structure.json)
- [JSON Structure](json-structure/arcade-engine-execute-tool-request-structure.json)
- [JSON Structure](json-structure/arcade-engine-execute-tool-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-authorize-tool-request-structure.json)
- [JSON Structure](json-structure/arcade-engine-authorization-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-auth-provider-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-worker-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-hook-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-gateway-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-plugin-response-structure.json)
- [JSON Structure](json-structure/arcade-engine-secret-response-structure.json)

### Arcade Public Schemas

The ArcadeAI/schemas repo on GitHub publishes versioned JSON Schemas for the Arcade engine configuration (1.0 and 2.0) and the worker HTTP contracts (1.0) — tool_definition, execute_tool_request, and execute_tool_response — used by every Arcade worker.

- **Human URL:** [https://github.com/ArcadeAI/schemas](https://github.com/ArcadeAI/schemas)
- **Base URL:** `https://github.com/ArcadeAI/schemas`

#### Tags

- Schemas
- JSON Schema
- Worker Protocol

#### Properties

- [Documentation](https://github.com/ArcadeAI/schemas)
- [GitHub Repository](https://github.com/ArcadeAI/schemas)
- [JSON Schema](json-schema/arcade-tool-definition-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-execute-tool-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/arcade-execute-tool-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/ArcadeAI/schemas/main/worker/http/1.0/tool_definition.schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/ArcadeAI/schemas/main/engine/config/1.0/schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/ArcadeAI/schemas/main/engine/config/2.0/schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/arcade-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcade-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arcade MCP Framework

The arcade-mcp open-source Python framework — "MCP Server Framework and Tool Development library for building custom capabilities into agents." Provides the `arcade` CLI (login, new, show, evals, mcp, deploy, configure, server, secret) and the Python building blocks for writing custom MCP servers and tools. MIT-licensed, 898 stars at profile time.

- **Human URL:** [https://github.com/ArcadeAI/arcade-mcp](https://github.com/ArcadeAI/arcade-mcp)
- **Base URL:** `https://github.com/ArcadeAI/arcade-mcp`

#### Tags

- MCP Server
- Framework
- Python
- Open Source

#### Properties

- [GitHub Repository](https://github.com/ArcadeAI/arcade-mcp)
- [Documentation](https://docs.arcade.dev/en/references/mcp/python)
- [SDK](https://pypi.org/project/arcade-mcp/)
- [C L I](https://docs.arcade.dev/en/references/arcade-cli)
- [Postman Collection](collections/arcade-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcade-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Arcade Integration Catalog

The Arcade integration catalog — 145 MCP servers across Arcade Optimized, Arcade Unoptimized, Verified, Community, and Auth Provider designations, with 37 additional "Coming Soon" integrations including Shopify, Snowflake, and QuickBooks. Categories include Productivity & Docs, Social & Communication, Developer Tools, Payments & Finance, Search, Sales, Databases, and Customer Support.

- **Human URL:** [https://docs.arcade.dev/en/resources/integrations](https://docs.arcade.dev/en/resources/integrations)

#### Tags

- Integrations
- Toolkits
- MCP Servers

#### Properties

- [Documentation](https://docs.arcade.dev/en/resources/integrations)
- [Resources](https://docs.arcade.dev/en/resources/tools)
- [Resources](https://docs.arcade.dev/en/resources/examples)
- [Postman Collection](collections/arcade-engine.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/arcade-engine.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://arcade.dev)
- [Developer Portal](https://docs.arcade.dev)
- [Sign Up](https://api.arcade.dev/dashboard)
- [Console](https://api.arcade.dev/dashboard)
- [Pricing](https://arcade.dev/pricing)
- [Plans](plans/arcade-plans-pricing.yml)
- [Rate Limits](rate-limits/arcade-rate-limits.yml)
- [Fin Ops](finops/arcade-finops.yml)
- [Terms of Service](https://arcade.dev/terms-of-service)
- [Privacy Policy](https://arcade.dev/privacy-policy)
- [Blog](https://arcade.dev/blog)
- [Status Page](https://status.arcade.dev)
- [Changelog](https://docs.arcade.dev/en/references/changelog)
- [GitHub Organization](https://github.com/ArcadeAI)
- [Support](mailto:contact@arcade.dev)
- [Vocabulary](vocabulary/arcade-vocabulary.yml)
- [JSON-LD](json-ld/arcade-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/arcade-engine-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [L L Ms Txt](https://docs.arcade.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
