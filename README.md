# Arcade (arcade)

Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Context Protocol tools that agent frameworks like LangChain, OpenAI Agents, CrewAI, AG2, Google ADK, Vercel AI, Mastra, and TanStack AI can call. This profile catalogs the public Arcade Engine API (39 endpoints across Admin, Authorization, Tools, LLM, Operations, Hooks, Gateways, and Plugins), the ArcadeAI GitHub org's SDKs, the arcade-mcp framework, and the public schemas repo.

**URL:** [Visit APIs.json URL](https://github.com/api-evangelist/arcade)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

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

**Human URL:** [https://docs.arcade.dev/en/references/api](https://docs.arcade.dev/en/references/api)
**Base URL:** `https://api.arcade.dev`

#### Tags

 - Engine
 - Tool Calling
 - Authorization
 - MCP Runtime

#### Properties

- [Documentation](https://docs.arcade.dev) — `Documentation`
- [APIReference](https://docs.arcade.dev/en/references/api) — `APIReference`
- [OpenAPI](openapi/arcade-engine-openapi.yml) — `OpenAPI`
- [Live Arcade Engine OpenAPI 3.0 spec](https://api.arcade.dev/v1/swagger) — `OpenAPI`
- [SpectralRules](rules/arcade-engine-rules.yml) — `SpectralRules`
- [Authentication](https://docs.arcade.dev/guides/tool-calling/custom-apps/auth-tool-calling) — `Authentication`
- [Quickstart](https://docs.arcade.dev/en/get-started/quickstarts/call-tool-agent) — `Quickstart`
- [MCP Server Quickstart](https://docs.arcade.dev/en/get-started/quickstarts/mcp-server-quickstart) — `Quickstart`
- [Official Arcade Python Client (arcade-py)](https://github.com/ArcadeAI/arcade-py) — `SDK`
- [Arcade NodeJS / TypeScript Client (arcade-js)](https://github.com/ArcadeAI/arcade-js) — `SDK`
- [Official Arcade Go Client (arcade-go)](https://github.com/ArcadeAI/arcade-go) — `SDK`
- [Arcade Java/Kotlin Client (arcade-java)](https://github.com/ArcadeAI/arcade-java) — `SDK`
- [Arcade .NET Client (arcade-dotnet)](https://github.com/ArcadeAI/arcade-dotnet) — `SDK`
- [arcade CLI (installed via `uv tool install arcade-mcp` or `pip install arcade-mcp`)](https://docs.arcade.dev/en/references/arcade-cli) — `CLI`
- [ChangeLog](https://docs.arcade.dev/en/references/changelog) — `ChangeLog`
- [NaftikoCapability](capabilities/engine-admin.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-authorization.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-tools.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-llm.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-operations.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-hooks.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-gateways.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-plugins.yaml) — `NaftikoCapability`
- [JSONSchema](json-schema/arcade-engine-tool-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-tool-execution-detail-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-execute-tool-request-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-execute-tool-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-authorize-tool-request-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-authorization-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-auth-provider-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-worker-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-hook-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-gateway-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-plugin-response-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-engine-secret-response-schema.json) — `JSONSchema`
- [JSONStructure](json-structure/arcade-engine-tool-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-tool-execution-detail-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-execute-tool-request-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-execute-tool-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-authorize-tool-request-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-authorization-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-auth-provider-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-worker-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-hook-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-gateway-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-plugin-response-structure.json) — `JSONStructure`
- [JSONStructure](json-structure/arcade-engine-secret-response-structure.json) — `JSONStructure`

### Arcade Public Schemas

The ArcadeAI/schemas repo on GitHub publishes versioned JSON Schemas for the Arcade engine configuration (1.0 and 2.0) and the worker HTTP contracts (1.0) — tool_definition, execute_tool_request, and execute_tool_response — used by every Arcade worker.

**Human URL:** [https://github.com/ArcadeAI/schemas](https://github.com/ArcadeAI/schemas)
**Base URL:** `https://github.com/ArcadeAI/schemas`

#### Tags

 - Schemas
 - JSON Schema
 - Worker Protocol

#### Properties

- [Documentation](https://github.com/ArcadeAI/schemas) — `Documentation`
- [GitHubRepository](https://github.com/ArcadeAI/schemas) — `GitHubRepository`
- [JSONSchema](json-schema/arcade-tool-definition-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-execute-tool-request-schema.json) — `JSONSchema`
- [JSONSchema](json-schema/arcade-execute-tool-response-schema.json) — `JSONSchema`
- [Upstream tool_definition.schema.json](https://raw.githubusercontent.com/ArcadeAI/schemas/main/worker/http/1.0/tool_definition.schema.json) — `JSONSchema`
- [Upstream engine config 1.0 schema](https://raw.githubusercontent.com/ArcadeAI/schemas/main/engine/config/1.0/schema.json) — `JSONSchema`
- [Upstream engine config 2.0 schema](https://raw.githubusercontent.com/ArcadeAI/schemas/main/engine/config/2.0/schema.json) — `JSONSchema`

### Arcade MCP Framework

The arcade-mcp open-source Python framework — "MCP Server Framework and Tool Development library for building custom capabilities into agents." Provides the `arcade` CLI (login, new, show, evals, mcp, deploy, configure, server, secret) and the Python building blocks for writing custom MCP servers and tools. MIT-licensed, 898 stars at profile time.

**Human URL:** [https://github.com/ArcadeAI/arcade-mcp](https://github.com/ArcadeAI/arcade-mcp)
**Base URL:** `https://github.com/ArcadeAI/arcade-mcp`

#### Tags

 - MCP Server
 - Framework
 - Python
 - Open Source

#### Properties

- [GitHubRepository](https://github.com/ArcadeAI/arcade-mcp) — `GitHubRepository`
- [Documentation](https://docs.arcade.dev/en/references/mcp/python) — `Documentation`
- [arcade-mcp on PyPI](https://pypi.org/project/arcade-mcp/) — `SDK`
- [CLI](https://docs.arcade.dev/en/references/arcade-cli) — `CLI`

### Arcade Integration Catalog

The Arcade integration catalog — 145 MCP servers across Arcade Optimized, Arcade Unoptimized, Verified, Community, and Auth Provider designations, with 37 additional "Coming Soon" integrations including Shopify, Snowflake, and QuickBooks. Categories include Productivity & Docs, Social & Communication, Developer Tools, Payments & Finance, Search, Sales, Databases, and Customer Support.

**Human URL:** [https://docs.arcade.dev/en/resources/integrations](https://docs.arcade.dev/en/resources/integrations)

#### Tags

 - Integrations
 - Toolkits
 - MCP Servers

#### Properties

- [Documentation](https://docs.arcade.dev/en/resources/integrations) — `Documentation`
- [Resources](https://docs.arcade.dev/en/resources/tools) — `Resources`
- [Resources](https://docs.arcade.dev/en/resources/examples) — `Resources`

## Common Properties

- [Portal](https://arcade.dev) — `Portal`
- [DeveloperPortal](https://docs.arcade.dev) — `DeveloperPortal`
- [SignUp](https://api.arcade.dev/dashboard) — `SignUp`
- [Console](https://api.arcade.dev/dashboard) — `Console`
- [Pricing](https://arcade.dev/pricing) — `Pricing`
- [Plans](plans/arcade-plans-pricing.yml) — `Plans`
- [RateLimits](rate-limits/arcade-rate-limits.yml) — `RateLimits`
- [FinOps](finops/arcade-finops.yml) — `FinOps`
- [TermsOfService](https://arcade.dev/terms-of-service) — `TermsOfService`
- [PrivacyPolicy](https://arcade.dev/privacy-policy) — `PrivacyPolicy`
- [Blog](https://arcade.dev/blog) — `Blog`
- [StatusPage](https://status.arcade.dev) — `StatusPage`
- [ChangeLog](https://docs.arcade.dev/en/references/changelog) — `ChangeLog`
- [GitHubOrganization](https://github.com/ArcadeAI) — `GitHubOrganization`
- [Support](mailto:contact@arcade.dev) — `Support`
- [Vocabulary](vocabulary/arcade-vocabulary.yml) — `Vocabulary`
- [JSONLD](json-ld/arcade-context.jsonld) — `JSONLD`
- [SpectralRules](rules/arcade-engine-rules.yml) — `SpectralRules`
- [NaftikoCapability](capabilities/engine-admin.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-authorization.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-tools.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-llm.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-operations.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-hooks.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-gateways.yaml) — `NaftikoCapability`
- [NaftikoCapability](capabilities/engine-plugins.yaml) — `NaftikoCapability`

## Features

| Name | Description |
|------|-------------|
| MCP Runtime | Hosted and self-hostable Model Context Protocol runtime that turns tool definitions into multi-user, authorized invocations for agents. |
| Managed OAuth Authorization | Built-in OAuth and identity-provider flows across 30+ named auth providers plus a generic OAuth 2.0 provider; per-user tokens managed without service-account workarounds. |
| Tool Catalog | 145 MCP servers across Arcade Optimized, Unoptimized, Verified, Community, and Auth Provider designations, with 37 more 'Coming Soon'. |
| Agent-Framework Integrations | First-class adapters for LangChain, OpenAI Agents, CrewAI, AG2, Google ADK, Vercel AI, Mastra, and TanStack AI. |
| Evaluations | `arcade evals` CLI runs scripted tool-calling evals to gate releases on behavior, not just compile-time checks. |
| Observability | Per-execution logs across the Engine plus dashboards; audit logs and compliance reporting are part of the Enterprise tier. |
| Hooks and Plugins | Pre- and post-call hooks plus pluggable verifiers and policy modules under /v1/hooks and /v1/plugins. |
| Custom User Verifiers | Customer-owned verification flows (e.g. Stytch, Supabase) gating tool execution via /v1/auth/validate_custom_verifier. |
| Scheduled Tools | Tools can be registered to fire on a schedule via /v1/scheduled_tools instead of synchronously from an agent. |
| Deployment Flexibility | Cloud, VPC, on-premises, or air-gapped — explicitly called out on the homepage. |
| Arcade Registry (beta) | Marketplace for publishing and monetizing agent-ready tools. |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-User AI Assistant | Agents that act on behalf of distinct end users — Gmail/Calendar/Slack/Salesforce assistants — without shared service credentials. |
| Production Agent Deployment | Moving agents from prototype to production with governed OAuth, evals, and observability per the May 2026 CISO governance post. |
| Enterprise MCP Gateway | An ingress in front of one or more workers within a project applying routing, headers, and policies. |
| Agent SRE | On-call reliability and runbook automation per Arcade's 'AI SRE with Claude Code' blog series. |
| Sales and Productivity Automation | Multi-step workflows across Salesforce, HubSpot, Attio, Slack, Linear, Jira, Asana, ClickUp, Notion, Google Workspace, and Microsoft Office. |
| Voice and Chat Assistants | WhatsApp / Telegram / Slack assistants powered by the toolkits and the Arcade Engine. |

## Integrations

| Name | Description |
|------|-------------|
| LangChain | First-class LangChain integration; partnership extended via LangSmith Fleet announcement on 2026-04-07. |
| OpenAI Agents | Python adapter via openai-agents-arcade for using Arcade tools inside the OpenAI Agents SDK. |
| CrewAI | Documented framework integration in docs.arcade.dev. |
| AG2 | Framework support added in the 2026-04-10 changelog. |
| Google ADK | Adapter via google-adk-arcade Python library. |
| Vercel AI | arcade-vercel-ai-template demonstrating Arcade tools inside Vercel AI SDK chatbots. |
| Mastra | Documented framework integration. |
| TanStack AI | Documented framework integration. |
| Anthropic Claude Code | Multiple Claude Code routines and on-call workflows shipped from the Arcade blog through April–May 2026. |
| Auth Providers | Asana, Atlassian, Discord, Dropbox, GitHub, Google, HubSpot, Linear, LinkedIn, Microsoft, Notion, Reddit, Slack, Spotify, Twitch, X, Zoom, Airtable, Attio, Calendly, ClickUp, Figma, Mailchimp, Miro, PagerDuty, Salesforce, Square, TickTick, Zendesk, Zoho, plus a generic OAuth 2.0 provider. |

## Solutions

| Name | Description |
|------|-------------|
| Cloud Deployment | Arcade-hosted MCP servers, metered on the Growth plan at $0.05 per server-hour. |
| VPC Deployment | Deploy the Engine inside the customer's VPC — called out on the homepage as a supported topology. |
| On-Premises Deployment | Self-hosted Engine and workers for regulated environments. |
| Air-Gapped Deployment | Disconnected deployments for the highest-control environments. |
| Startup Program | Custom pricing for companies under 100 employees, nonprofits, and educational institutions via contact@arcade.dev. |

## Artifacts

Machine-readable API specifications and supporting artifacts produced by the API Evangelist pipeline.

### OpenAPI

- [arcade-engine-openapi.yml](openapi/arcade-engine-openapi.yml)

### JSON Schema

- [arcade-engine-auth-provider-response-schema.json](json-schema/arcade-engine-auth-provider-response-schema.json)
- [arcade-engine-authorization-response-schema.json](json-schema/arcade-engine-authorization-response-schema.json)
- [arcade-engine-authorize-tool-request-schema.json](json-schema/arcade-engine-authorize-tool-request-schema.json)
- [arcade-engine-execute-tool-request-schema.json](json-schema/arcade-engine-execute-tool-request-schema.json)
- [arcade-engine-execute-tool-response-schema.json](json-schema/arcade-engine-execute-tool-response-schema.json)
- [arcade-engine-gateway-response-schema.json](json-schema/arcade-engine-gateway-response-schema.json)
- [arcade-engine-hook-response-schema.json](json-schema/arcade-engine-hook-response-schema.json)
- [arcade-engine-plugin-response-schema.json](json-schema/arcade-engine-plugin-response-schema.json)
- [arcade-engine-secret-response-schema.json](json-schema/arcade-engine-secret-response-schema.json)
- [arcade-engine-tool-execution-detail-schema.json](json-schema/arcade-engine-tool-execution-detail-schema.json)
- [arcade-engine-tool-response-schema.json](json-schema/arcade-engine-tool-response-schema.json)
- [arcade-engine-worker-response-schema.json](json-schema/arcade-engine-worker-response-schema.json)
- [arcade-execute-tool-request-schema.json](json-schema/arcade-execute-tool-request-schema.json)
- [arcade-execute-tool-response-schema.json](json-schema/arcade-execute-tool-response-schema.json)
- [arcade-tool-definition-schema.json](json-schema/arcade-tool-definition-schema.json)

### JSON Structure

- [arcade-engine-auth-provider-response-structure.json](json-structure/arcade-engine-auth-provider-response-structure.json)
- [arcade-engine-authorization-response-structure.json](json-structure/arcade-engine-authorization-response-structure.json)
- [arcade-engine-authorize-tool-request-structure.json](json-structure/arcade-engine-authorize-tool-request-structure.json)
- [arcade-engine-execute-tool-request-structure.json](json-structure/arcade-engine-execute-tool-request-structure.json)
- [arcade-engine-execute-tool-response-structure.json](json-structure/arcade-engine-execute-tool-response-structure.json)
- [arcade-engine-gateway-response-structure.json](json-structure/arcade-engine-gateway-response-structure.json)
- [arcade-engine-hook-response-structure.json](json-structure/arcade-engine-hook-response-structure.json)
- [arcade-engine-plugin-response-structure.json](json-structure/arcade-engine-plugin-response-structure.json)
- [arcade-engine-secret-response-structure.json](json-structure/arcade-engine-secret-response-structure.json)
- [arcade-engine-tool-execution-detail-structure.json](json-structure/arcade-engine-tool-execution-detail-structure.json)
- [arcade-engine-tool-response-structure.json](json-structure/arcade-engine-tool-response-structure.json)
- [arcade-engine-worker-response-structure.json](json-structure/arcade-engine-worker-response-structure.json)

### JSON-LD

- [arcade-context.jsonld](json-ld/arcade-context.jsonld)

### Examples

- [arcade-engine-arcade-health-example.json](examples/arcade-engine-arcade-health-example.json)
- [arcade-engine-auth-connections-delete-example.json](examples/arcade-engine-auth-connections-delete-example.json)
- [arcade-engine-auth-connections-list-example.json](examples/arcade-engine-auth-connections-list-example.json)
- [arcade-engine-auth-providers-create-example.json](examples/arcade-engine-auth-providers-create-example.json)
- [arcade-engine-auth-providers-delete-example.json](examples/arcade-engine-auth-providers-delete-example.json)
- [arcade-engine-auth-providers-get-example.json](examples/arcade-engine-auth-providers-get-example.json)
- [arcade-engine-auth-providers-list-example.json](examples/arcade-engine-auth-providers-list-example.json)
- [arcade-engine-auth-providers-update-example.json](examples/arcade-engine-auth-providers-update-example.json)
- [arcade-engine-auth-status-example.json](examples/arcade-engine-auth-status-example.json)
- [arcade-engine-confirm-user-auth-flow-example.json](examples/arcade-engine-confirm-user-auth-flow-example.json)
- [arcade-engine-engine-config-example.json](examples/arcade-engine-engine-config-example.json)
- [arcade-engine-hooks-bulk-upsert-example.json](examples/arcade-engine-hooks-bulk-upsert-example.json)
- [arcade-engine-hooks-create-example.json](examples/arcade-engine-hooks-create-example.json)
- [arcade-engine-hooks-delete-example.json](examples/arcade-engine-hooks-delete-example.json)
- [arcade-engine-hooks-get-example.json](examples/arcade-engine-hooks-get-example.json)
- [arcade-engine-hooks-list-example.json](examples/arcade-engine-hooks-list-example.json)
- [arcade-engine-hooks-update-example.json](examples/arcade-engine-hooks-update-example.json)
- [arcade-engine-initiate-authorization-example.json](examples/arcade-engine-initiate-authorization-example.json)
- [arcade-engine-llm-chat-example.json](examples/arcade-engine-llm-chat-example.json)
- [arcade-engine-plugins-create-example.json](examples/arcade-engine-plugins-create-example.json)
- [arcade-engine-plugins-delete-example.json](examples/arcade-engine-plugins-delete-example.json)
- [arcade-engine-plugins-get-example.json](examples/arcade-engine-plugins-get-example.json)
- [arcade-engine-plugins-list-example.json](examples/arcade-engine-plugins-list-example.json)
- [arcade-engine-plugins-update-example.json](examples/arcade-engine-plugins-update-example.json)
- [arcade-engine-project-gateways-create-example.json](examples/arcade-engine-project-gateways-create-example.json)
- [arcade-engine-project-gateways-delete-example.json](examples/arcade-engine-project-gateways-delete-example.json)
- [arcade-engine-project-gateways-get-example.json](examples/arcade-engine-project-gateways-get-example.json)
- [arcade-engine-project-gateways-list-example.json](examples/arcade-engine-project-gateways-list-example.json)
- [arcade-engine-project-gateways-patch-example.json](examples/arcade-engine-project-gateways-patch-example.json)
- [arcade-engine-project-gateways-slug-info-example.json](examples/arcade-engine-project-gateways-slug-info-example.json)
- [arcade-engine-project-gateways-update-example.json](examples/arcade-engine-project-gateways-update-example.json)
- [arcade-engine-secrets-delete-example.json](examples/arcade-engine-secrets-delete-example.json)
- [arcade-engine-secrets-list-example.json](examples/arcade-engine-secrets-list-example.json)
- [arcade-engine-secrets-upsert-example.json](examples/arcade-engine-secrets-upsert-example.json)
- [arcade-engine-session-verification-settings-get-example.json](examples/arcade-engine-session-verification-settings-get-example.json)
- [arcade-engine-session-verification-settings-update-example.json](examples/arcade-engine-session-verification-settings-update-example.json)
- [arcade-engine-swagger-example.json](examples/arcade-engine-swagger-example.json)
- [arcade-engine-test-authorization-flow-example.json](examples/arcade-engine-test-authorization-flow-example.json)
- [arcade-engine-tool-authorize-example.json](examples/arcade-engine-tool-authorize-example.json)
- [arcade-engine-tool-execute-example.json](examples/arcade-engine-tool-execute-example.json)
- [arcade-engine-tool-requirements-example.json](examples/arcade-engine-tool-requirements-example.json)
- [arcade-engine-tool-scheduled-get-example.json](examples/arcade-engine-tool-scheduled-get-example.json)
- [arcade-engine-tool-scheduled-list-example.json](examples/arcade-engine-tool-scheduled-list-example.json)
- [arcade-engine-tool-spec-example.json](examples/arcade-engine-tool-spec-example.json)
- [arcade-engine-tool-spec-formatted-example.json](examples/arcade-engine-tool-spec-formatted-example.json)
- [arcade-engine-tools-list-example.json](examples/arcade-engine-tools-list-example.json)
- [arcade-engine-tools-list-formatted-example.json](examples/arcade-engine-tools-list-formatted-example.json)
- [arcade-engine-tools-list-static-example.json](examples/arcade-engine-tools-list-static-example.json)
- [arcade-engine-workers-authorize-example.json](examples/arcade-engine-workers-authorize-example.json)
- [arcade-engine-workers-create-example.json](examples/arcade-engine-workers-create-example.json)
- [arcade-engine-workers-delete-example.json](examples/arcade-engine-workers-delete-example.json)
- [arcade-engine-workers-get-example.json](examples/arcade-engine-workers-get-example.json)
- [arcade-engine-workers-health-example.json](examples/arcade-engine-workers-health-example.json)
- [arcade-engine-workers-list-example.json](examples/arcade-engine-workers-list-example.json)
- [arcade-engine-workers-test-example.json](examples/arcade-engine-workers-test-example.json)
- [arcade-engine-workers-update-example.json](examples/arcade-engine-workers-update-example.json)

### Spectral Rules

- [arcade-engine-rules.yml](rules/arcade-engine-rules.yml)

### Naftiko Capabilities

- [engine-admin.yaml](capabilities/engine-admin.yaml)
- [engine-authorization.yaml](capabilities/engine-authorization.yaml)
- [engine-gateways.yaml](capabilities/engine-gateways.yaml)
- [engine-hooks.yaml](capabilities/engine-hooks.yaml)
- [engine-llm.yaml](capabilities/engine-llm.yaml)
- [engine-operations.yaml](capabilities/engine-operations.yaml)
- [engine-plugins.yaml](capabilities/engine-plugins.yaml)
- [engine-tools.yaml](capabilities/engine-tools.yaml)

### Vocabulary

- [arcade-vocabulary.yml](vocabulary/arcade-vocabulary.yml)

### Plans & Pricing

- [arcade-plans-pricing.yml](plans/arcade-plans-pricing.yml)

### Rate Limits

- [arcade-rate-limits.yml](rate-limits/arcade-rate-limits.yml)

### FinOps

- [arcade-finops.yml](finops/arcade-finops.yml)

## Maintainers

- Kin Lane — info@apievangelist.com — https://apievangelist.com

---

_Generated by the API Evangelist `run-pipeline` skill on 2026-05-22 against arcade.dev._