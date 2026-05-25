# Hyperbrowser (hyperbrowser)
Hyperbrowser is AI-native browser infrastructure: cloud-hosted Chromium sessions with stealth, residential and datacenter proxies, CAPTCHA solving, persistent profiles, and an `x402` micropayment surface. On top of those sessions the platform exposes scrape, batch scrape, crawl, and structured extract jobs, plus first-party agent endpoints for HyperAgent, Browser-Use, Anthropic Claude Computer Use, Google Gemini Computer Use, and OpenAI's CUA. Hyperbrowser ships Python and Node SDKs, the open-source HyperAgent framework, and an MCP server so any Model Context Protocol client (Claude Desktop, Cursor, Windsurf, etc.) can drive its tools.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/hyperbrowser/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Headless Browser, Browser Infrastructure, Web Scraping, Web Crawling, Data Extraction, AI Agents, Browser Automation, Computer Use, Stealth, Proxies, CAPTCHA Solving, MCP, HyperAgent, X402

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Hyperbrowser Sessions API
Manage cloud Chromium browser sessions: create, list, inspect, update, and stop sessions; retrieve recording, video, and downloads URLs; and run manual CAPTCHA evaluation. Sessions expose a WebSocket CDP endpoint and an optional live-view URL.

**Human URL:** [https://docs.hyperbrowser.ai/sessions/overview](https://docs.hyperbrowser.ai/sessions/overview)

- [OpenAPI](openapi/hyperbrowser-sessions-api-openapi.yml)
- [JSON Schema — Session](json-schema/hyperbrowser-session-schema.json)
- [JSON Structure — Session](json-structure/hyperbrowser-session-structure.json)
- [Naftiko Capability — Session](capabilities/sessions-session.yaml)
- [Naftiko Capability — Sessions List](capabilities/sessions-sessions.yaml)
- [Example — Create Session](examples/hyperbrowser-create-session-example.json)

### Hyperbrowser Profiles API
Create, list, fetch, and delete persistent browser profiles that retain cookies, local storage, and authenticated state across sessions.

**Human URL:** [https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/profiles](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/profiles)

- [OpenAPI](openapi/hyperbrowser-profiles-api-openapi.yml)
- [Naftiko Capability — Profile](capabilities/profiles-profile.yaml)
- [Naftiko Capability — Profiles List](capabilities/profiles-profiles.yaml)

### Hyperbrowser Scrape API
Single-page and batch scrape jobs returning HTML, Markdown, links, and screenshots with asynchronous status polling.

**Human URL:** [https://docs.hyperbrowser.ai/scrape/overview](https://docs.hyperbrowser.ai/scrape/overview)

- [OpenAPI](openapi/hyperbrowser-scrape-api-openapi.yml)
- [JSON Schema — Scrape Job](json-schema/hyperbrowser-scrape-job-schema.json)
- [Naftiko Capability — Scrape](capabilities/scrape-scrape.yaml)
- [Example — Scrape](examples/hyperbrowser-scrape-example.json)

### Hyperbrowser Crawl API
Recursive crawl jobs across many pages with structured page-by-page results and status polling.

**Human URL:** [https://docs.hyperbrowser.ai/crawl/overview](https://docs.hyperbrowser.ai/crawl/overview)

- [OpenAPI](openapi/hyperbrowser-crawl-api-openapi.yml)
- [JSON Schema — Crawl Job](json-schema/hyperbrowser-crawl-job-schema.json)
- [Naftiko Capability — Crawl](capabilities/crawl-crawl.yaml)

### Hyperbrowser Extract API
Structured data extraction jobs that pull typed records from one or more pages using prompts and JSON schemas.

**Human URL:** [https://docs.hyperbrowser.ai/extract/overview](https://docs.hyperbrowser.ai/extract/overview)

- [OpenAPI](openapi/hyperbrowser-extract-api-openapi.yml)
- [JSON Schema — Extract Job](json-schema/hyperbrowser-extract-job-schema.json)
- [Naftiko Capability — Extract](capabilities/extract-extract.yaml)
- [Example — Extract](examples/hyperbrowser-extract-example.json)

### Hyperbrowser Agents API
Start, stop, and monitor agentic browser tasks across HyperAgent, Browser-Use, Claude Computer Use, Gemini Computer Use, and OpenAI's CUA. Each task runs inside a stealth Hyperbrowser session with live-view URL, proxy support, and CAPTCHA solving.

**Human URL:** [https://docs.hyperbrowser.ai/agents/overview](https://docs.hyperbrowser.ai/agents/overview)

- [OpenAPI](openapi/hyperbrowser-agents-api-openapi.yml)
- [JSON Schema — Agent Task](json-schema/hyperbrowser-agent-task-schema.json)
- [Naftiko Capability — HyperAgent](capabilities/agents-hyper-agent.yaml)
- [Naftiko Capability — Browser-Use](capabilities/agents-browser-use.yaml)
- [Naftiko Capability — Claude Computer Use](capabilities/agents-claude-computer-use.yaml)
- [Naftiko Capability — Gemini Computer Use](capabilities/agents-gemini-computer-use.yaml)
- [Naftiko Capability — OpenAI CUA](capabilities/agents-cua.yaml)
- [Example — Claude Computer Use](examples/hyperbrowser-claude-computer-use-example.json)

### Hyperbrowser Extensions API
Upload and list custom Chrome extensions that can be attached to browser sessions for advanced automation, custom UI, or workflow tooling.

**Human URL:** [https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/uploading-extensions](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/uploading-extensions)

- [OpenAPI](openapi/hyperbrowser-extensions-api-openapi.yml)
- [Naftiko Capability — Extensions](capabilities/extensions-extensions.yaml)

### Hyperbrowser Web API
Stateless web utilities: fetch a single page, run a web search, or start a crawl. Includes `/x402` micropayment-gated variants of fetch and search for permissionless, pay-per-call usage.

**Human URL:** [https://docs.hyperbrowser.ai/web/overview](https://docs.hyperbrowser.ai/web/overview)

- [OpenAPI](openapi/hyperbrowser-web-api-openapi.yml)
- [Naftiko Capability — Web](capabilities/web-web.yaml)
- [Naftiko Capability — X402 Web](capabilities/web-x402-web.yaml)
- [Example — Web Search](examples/hyperbrowser-web-search-example.json)

## Common Properties

- [Website — hyperbrowser.ai](https://hyperbrowser.ai)
- [Documentation — docs.hyperbrowser.ai](https://docs.hyperbrowser.ai)
- [API Reference](https://docs.hyperbrowser.ai/api-reference)
- [Getting Started](https://docs.hyperbrowser.ai/quickstart)
- [Blog](https://hyperbrowser.ai/blog)
- [GitHub Organization — hyperbrowserai](https://github.com/hyperbrowserai)
- [Pricing](https://hyperbrowser.ai/pricing)
- [Sign Up](https://app.hyperbrowser.ai/signup)
- [Terms of Service](https://hyperbrowser.ai/terms)
- [Privacy Policy](https://hyperbrowser.ai/privacy)
- [llms.txt](https://hyperbrowser.ai/llms.txt)
- [SDK — Python](https://github.com/hyperbrowserai/python-sdk)
- [SDK — Node](https://github.com/hyperbrowserai/node-sdk)
- [SDK — PyPI `hyperbrowser`](https://pypi.org/project/hyperbrowser/)
- [SDK — npm `@hyperbrowser/sdk`](https://www.npmjs.com/package/@hyperbrowser/sdk)
- [Tool — MCP Server](https://github.com/hyperbrowserai/mcp)
- [Tool — HyperAgent Framework](https://github.com/hyperbrowserai/HyperAgent)
- [Tool — n8n Node](https://github.com/hyperbrowserai/n8n-node)
- [Code Examples — Examples Repo](https://github.com/hyperbrowserai/examples)
- [Code Examples — App Examples](https://github.com/hyperbrowserai/hyperbrowser-app-examples)
- [Code Examples — CUA as a Tool](https://github.com/hyperbrowserai/cua-as-a-tool)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Hyperbrowser Sessions API](openapi/hyperbrowser-sessions-api-openapi.yml)
- [Hyperbrowser Profiles API](openapi/hyperbrowser-profiles-api-openapi.yml)
- [Hyperbrowser Scrape API](openapi/hyperbrowser-scrape-api-openapi.yml)
- [Hyperbrowser Crawl API](openapi/hyperbrowser-crawl-api-openapi.yml)
- [Hyperbrowser Extract API](openapi/hyperbrowser-extract-api-openapi.yml)
- [Hyperbrowser Agents API](openapi/hyperbrowser-agents-api-openapi.yml)
- [Hyperbrowser Extensions API](openapi/hyperbrowser-extensions-api-openapi.yml)
- [Hyperbrowser Web API](openapi/hyperbrowser-web-api-openapi.yml)
- [Source — Upstream OpenAPI mirror](openapi/hyperbrowser-openapi.json)

### JSON Schema

- [Session](json-schema/hyperbrowser-session-schema.json)
- [Scrape Job](json-schema/hyperbrowser-scrape-job-schema.json)
- [Crawl Job](json-schema/hyperbrowser-crawl-job-schema.json)
- [Extract Job](json-schema/hyperbrowser-extract-job-schema.json)
- [Agent Task](json-schema/hyperbrowser-agent-task-schema.json)

### JSON Structure

- [Session Lifecycle](json-structure/hyperbrowser-session-structure.json)

### JSON-LD

- [Hyperbrowser Context](json-ld/hyperbrowser-context.jsonld)

### Capabilities (Naftiko)

- [Sessions — Session](capabilities/sessions-session.yaml)
- [Sessions — List](capabilities/sessions-sessions.yaml)
- [Profiles — Profile](capabilities/profiles-profile.yaml)
- [Profiles — List](capabilities/profiles-profiles.yaml)
- [Scrape](capabilities/scrape-scrape.yaml)
- [Crawl](capabilities/crawl-crawl.yaml)
- [Extract](capabilities/extract-extract.yaml)
- [Agents — HyperAgent](capabilities/agents-hyper-agent.yaml)
- [Agents — Browser-Use](capabilities/agents-browser-use.yaml)
- [Agents — Claude Computer Use](capabilities/agents-claude-computer-use.yaml)
- [Agents — Gemini Computer Use](capabilities/agents-gemini-computer-use.yaml)
- [Agents — OpenAI CUA](capabilities/agents-cua.yaml)
- [Extensions](capabilities/extensions-extensions.yaml)
- [Web](capabilities/web-web.yaml)
- [Web — X402](capabilities/web-x402-web.yaml)

### Examples

- [Create Session](examples/hyperbrowser-create-session-example.json)
- [Scrape](examples/hyperbrowser-scrape-example.json)
- [Extract](examples/hyperbrowser-extract-example.json)
- [Claude Computer Use](examples/hyperbrowser-claude-computer-use-example.json)
- [Web Search](examples/hyperbrowser-web-search-example.json)

### Spectral Rules

- [Hyperbrowser Spectral Ruleset](rules/hyperbrowser-rules.yml)

### Vocabulary

- [Hyperbrowser Vocabulary](vocabulary/hyperbrowser-vocabulary.yml)

### Commercial artifacts

- [Plans / Pricing](plans/hyperbrowser-plans-pricing.yml)
- [Rate Limits](rate-limits/hyperbrowser-rate-limits.yml)
- [FinOps Definition](finops/hyperbrowser-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
