# Hyperbrowser (hyperbrowser)

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

Hyperbrowser provides cloud browser infrastructure tailored for AI agents, bundling managed Chromium sessions with web scraping, crawling, and data-extraction APIs. The platform ships the open-source HyperAgent framework and first-class integrations for Browser-Use, Claude Computer Use, Gemini Computer Use, and OpenAI's CUA, so teams can deploy general-purpose web agents quickly. Customers include AI startups, data teams, and enterprises that need stealthy, multi-region browsers with CAPTCHA solving, proxies, and session profiles. Python and Node SDKs cover sessions, scrape/crawl/extract jobs, agent task management, and an MCP server lets any Model Context Protocol client (Claude Desktop, Cursor, Windsurf, etc.) drive Hyperbrowser tools. Pricing is usage-based via the hyperbrowser.ai pricing page.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hyperbrowser/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hyperbrowser/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Headless Browser
- Browser Infrastructure
- Web Scraping
- Web Crawling
- Data Extraction
- AI Agents
- Browser Automation
- Computer Use
- Stealth
- Proxies
- CAPTCHA Solving
- MCP
- HyperAgent
- X402

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Hyperbrowser Sessions API

Manage cloud Chromium browser sessions: create, list, inspect, update, and stop sessions; retrieve recording, video, and downloads URLs; and run manual CAPTCHA evaluation. Sessions expose a WebSocket CDP endpoint and an optional live-view URL.

- **Human URL:** [https://docs.hyperbrowser.ai/sessions/overview](https://docs.hyperbrowser.ai/sessions/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Sessions
- Browser Infrastructure
- Stealth
- Proxies

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/sessions/overview)
- [API Reference](https://docs.hyperbrowser.ai/api-reference/sessions)
- [OpenAPI](openapi/hyperbrowser-sessions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-sessions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-sessions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hyperbrowser-session-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/hyperbrowser-session-structure.json)
- [Example](examples/hyperbrowser-create-session-example.json)

### Hyperbrowser Profiles API

Create, list, fetch, and delete persistent browser profiles that retain cookies, local storage, and authenticated state across sessions.

- **Human URL:** [https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/profiles](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/profiles)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Profiles
- Sessions

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/profiles)
- [OpenAPI](openapi/hyperbrowser-profiles-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-profiles-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-profiles-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperbrowser Scrape API

Single-page and batch scrape jobs returning HTML, Markdown, links, and screenshots with asynchronous status polling.

- **Human URL:** [https://docs.hyperbrowser.ai/scrape/overview](https://docs.hyperbrowser.ai/scrape/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Scrape
- Web Scraping
- Batch

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/scrape/overview)
- [OpenAPI](openapi/hyperbrowser-scrape-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-scrape-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-scrape-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hyperbrowser-scrape-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/hyperbrowser-scrape-example.json)

### Hyperbrowser Crawl API

Recursive crawl jobs across many pages with structured page-by-page results and status polling.

- **Human URL:** [https://docs.hyperbrowser.ai/crawl/overview](https://docs.hyperbrowser.ai/crawl/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Crawl
- Web Crawling

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/crawl/overview)
- [OpenAPI](openapi/hyperbrowser-crawl-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-crawl-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-crawl-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hyperbrowser-crawl-job-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Hyperbrowser Extract API

Structured data extraction jobs that pull typed records from one or more pages using prompts and JSON schemas.

- **Human URL:** [https://docs.hyperbrowser.ai/extract/overview](https://docs.hyperbrowser.ai/extract/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Extract
- Structured Extraction
- Data Extraction

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/extract/overview)
- [OpenAPI](openapi/hyperbrowser-extract-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-extract-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-extract-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hyperbrowser-extract-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/hyperbrowser-extract-example.json)

### Hyperbrowser Agents API

Start, stop, and monitor agentic browser tasks across HyperAgent, Browser-Use, Claude Computer Use, Gemini Computer Use, and OpenAI's CUA. Each task runs inside a stealth Hyperbrowser session with live-view URL, proxy support, and CAPTCHA solving.

- **Human URL:** [https://docs.hyperbrowser.ai/agents/overview](https://docs.hyperbrowser.ai/agents/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Agents
- Computer Use
- HyperAgent
- Browser-Use
- Claude
- Gemini
- OpenAI CUA

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/agents/overview)
- [OpenAPI](openapi/hyperbrowser-agents-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-agents-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-agents-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hyperbrowser-agent-task-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Example](examples/hyperbrowser-claude-computer-use-example.json)

### Hyperbrowser Extensions API

Upload and list custom Chrome extensions that can be attached to browser sessions for advanced automation, custom UI, or workflow tooling.

- **Human URL:** [https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/uploading-extensions](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/uploading-extensions)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Extensions
- Sessions

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/sessions/advanced-privacy-and-anti-detection/uploading-extensions)
- [OpenAPI](openapi/hyperbrowser-extensions-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-extensions-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-extensions-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hyperbrowser Web API

Stateless web utilities: fetch a single page, run a web search, or start a crawl. Includes `/x402` micropayment-gated variants of fetch and search for permissionless, pay-per-call usage.

- **Human URL:** [https://docs.hyperbrowser.ai/web/overview](https://docs.hyperbrowser.ai/web/overview)
- **Base URL:** `https://api.hyperbrowser.ai`

#### Tags

- Web
- Fetch
- Search
- X402

#### Properties

- [Documentation](https://docs.hyperbrowser.ai/web/overview)
- [OpenAPI](openapi/hyperbrowser-web-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hyperbrowser-web-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hyperbrowser-web-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Example](examples/hyperbrowser-web-search-example.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://hyperbrowser.ai)
- [Documentation](https://docs.hyperbrowser.ai)
- [API Reference](https://docs.hyperbrowser.ai/api-reference)
- [Getting Started](https://docs.hyperbrowser.ai/quickstart)
- [Blog](https://hyperbrowser.ai/blog)
- [GitHub Organization](https://github.com/hyperbrowserai)
- [Pricing](https://hyperbrowser.ai/pricing)
- [Sign Up](https://app.hyperbrowser.ai/signup)
- [Terms of Service](https://hyperbrowser.ai/terms)
- [Privacy Policy](https://hyperbrowser.ai/privacy)
- [L L Ms Txt](https://hyperbrowser.ai/llms.txt)
- [SDK](https://github.com/hyperbrowserai/python-sdk)
- [SDK](https://github.com/hyperbrowserai/node-sdk)
- [SDK](https://pypi.org/project/hyperbrowser/)
- [SDK](https://www.npmjs.com/package/@hyperbrowser/sdk)
- [Tool](https://github.com/hyperbrowserai/mcp)
- [Tool](https://github.com/hyperbrowserai/HyperAgent)
- [Tool](https://github.com/hyperbrowserai/n8n-node)
- [Code Examples](https://github.com/hyperbrowserai/examples)
- [Code Examples](https://github.com/hyperbrowserai/hyperbrowser-app-examples)
- [Code Examples](https://github.com/hyperbrowserai/cua-as-a-tool)
- [Plans](plans/hyperbrowser-plans-pricing.yml)
- [Rate Limits](rate-limits/hyperbrowser-rate-limits.yml)
- [Fin Ops](finops/hyperbrowser-finops.yml)
- [Vocabulary](vocabulary/hyperbrowser-vocabulary.yml)
- [JSON-LD](json-ld/hyperbrowser-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/hyperbrowser-rules.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
