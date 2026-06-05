# Arcade (arcade)

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
