# Hyperbrowser

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

Hyperbrowser provides cloud browser infrastructure tailored for AI agents, bundling managed Chromium sessions with web scraping, crawling, and data-extraction APIs. The platform ships the open-source HyperAgent framework and first-class integrations for Browser-Use, Claude Computer Use, Gemini Computer Use, and OpenAI's CUA, so teams can deploy general-purpose web agents quickly. Customers include AI startups, data teams, and enterprises that need stealthy, multi-region browsers with CAPTCHA solving, proxies, and session profiles. Python and Node SDKs cover sessions, scrape/crawl/extract jobs, agent task management, and an MCP server lets any Model Context Protocol client (Claude Desktop, Cursor, Windsurf, etc.) drive Hyperbrowser tools. Pricing is usage-based via the hyperbrowser.ai pricing page.

**Areas:** Browser Automation · Browser Infrastructure · Web Scraping · Web Crawling · Data Extraction · AI Agents · Computer Use · Stealth · Proxies · CAPTCHA Solving · MCP · HyperAgent

## Hyperbrowser on APIs.io

Everything profiled for Hyperbrowser is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hyperbrowser/](https://apis.io/providers/hyperbrowser/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Hyperbrowser Sessions API](https://apis.io/apis/hyperbrowser/sessions-api/) — Manage cloud Chromium browser sessions: create, list, inspect, update, and stop sessions; retrieve recording, video, and downloads URLs; and run manual…
- [Hyperbrowser Profiles API](https://apis.io/apis/hyperbrowser/profiles-api/) — Create, list, fetch, and delete persistent browser profiles that retain cookies, local storage, and authenticated state across sessions.
- [Hyperbrowser Scrape API](https://apis.io/apis/hyperbrowser/scrape-api/) — Single-page and batch scrape jobs returning HTML, Markdown, links, and screenshots with asynchronous status polling.
- [Hyperbrowser Crawl API](https://apis.io/apis/hyperbrowser/crawl-api/) — Recursive crawl jobs across many pages with structured page-by-page results and status polling.
- [Hyperbrowser Extract API](https://apis.io/apis/hyperbrowser/extract-api/) — Structured data extraction jobs that pull typed records from one or more pages using prompts and JSON schemas.
- [Hyperbrowser Extensions API](https://apis.io/apis/hyperbrowser/extensions-api/) — Upload and list custom Chrome extensions that can be attached to browser sessions for advanced automation, custom UI, or workflow tooling.
- [Hyperbrowser Web API](https://apis.io/apis/hyperbrowser/web-api/) — Stateless web utilities: fetch a single page, run a web search, or start a crawl. Includes `/x402` micropayment-gated variants of fetch and search for…
- [Hyperbrowser Profile API](https://apis.io/apis/hyperbrowser/hyperbrowser-profile-api/) — The Profile API from Hyperbrowser — 2 operation(s) for profile.
- [Hyperbrowser Session API](https://apis.io/apis/hyperbrowser/hyperbrowser-session-api/) — The Session API from Hyperbrowser — 8 operation(s) for session.
- [Hyperbrowser Task API](https://apis.io/apis/hyperbrowser/hyperbrowser-task-api/) — The Task API from Hyperbrowser — 20 operation(s) for task.
- [Hyperbrowser X402 API](https://apis.io/apis/hyperbrowser/hyperbrowser-x402-api/) — The X402 API from Hyperbrowser — 2 operation(s) for x402.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (11)

Multi-step workflows that chain operations into a business task.

- [Moved to /providers/hyperbrowser/](https://apis.io/arazzos/hyperbrowser/hyperbrowser-batch-scrape-and-retrieve-workflow/)
- [Hyperbrowser Browser Use Task Run](https://apis.io/arazzos/hyperbrowser/hyperbrowser-browser-use-task-run-workflow/)
- [Hyperbrowser Crawl Site and Retrieve](https://apis.io/arazzos/hyperbrowser/hyperbrowser-crawl-site-and-retrieve-workflow/)
- [Hyperbrowser Extract Structured Data](https://apis.io/arazzos/hyperbrowser/hyperbrowser-extract-structured-data-workflow/)
- [Hyperbrowser HyperAgent Task Run](https://apis.io/arazzos/hyperbrowser/hyperbrowser-hyperagent-task-run-workflow/)
- [Hyperbrowser Persistent Profile Session](https://apis.io/arazzos/hyperbrowser/hyperbrowser-persistent-profile-session-workflow/)
- [Moved to /providers/hyperbrowser/](https://apis.io/arazzos/hyperbrowser/hyperbrowser-scrape-and-retrieve-workflow/)
- [Hyperbrowser Session Lifecycle](https://apis.io/arazzos/hyperbrowser/hyperbrowser-session-lifecycle-workflow/)
- [Hyperbrowser Session Recording Retrieval](https://apis.io/arazzos/hyperbrowser/hyperbrowser-session-recording-retrieval-workflow/)
- [Hyperbrowser Web Crawl and Retrieve](https://apis.io/arazzos/hyperbrowser/hyperbrowser-web-crawl-and-retrieve-workflow/)
- [Hyperbrowser Web Search then Fetch](https://apis.io/arazzos/hyperbrowser/hyperbrowser-web-search-then-fetch-workflow/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hyperbrowser Agentic Access](https://apis.io/agentic-access/hyperbrowser/hyperbrowser-agentic-access/)

#### JSON Schema (5)

The data models the API reads and writes.

- [Hyperbrowser Agent Task](https://apis.io/schemas/hyperbrowser/hyperbrowser-agent-task/)
- [Hyperbrowser Crawl Job](https://apis.io/schemas/hyperbrowser/hyperbrowser-crawl-job/)
- [Hyperbrowser Extract Job](https://apis.io/schemas/hyperbrowser/hyperbrowser-extract-job/)
- [Hyperbrowser Scrape Job](https://apis.io/schemas/hyperbrowser/hyperbrowser-scrape-job/)
- [Hyperbrowser Session](https://apis.io/schemas/hyperbrowser/hyperbrowser-session/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Hyperbrowser Session Structure](https://apis.io/json-structure/hyperbrowser/hyperbrowser-session-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hyperbrowser Context](https://apis.io/jsonld/hyperbrowser/hyperbrowser-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Hyperbrowser Vocabulary](https://apis.io/vocabularies/hyperbrowser/hyperbrowser-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Hyperbrowser Claude Computer Use Example](https://apis.io/examples/hyperbrowser/hyperbrowser-claude-computer-use-example/)
- [Hyperbrowser Create Session Example](https://apis.io/examples/hyperbrowser/hyperbrowser-create-session-example/)
- [Hyperbrowser Extract Example](https://apis.io/examples/hyperbrowser/hyperbrowser-extract-example/)
- [Hyperbrowser Scrape Example](https://apis.io/examples/hyperbrowser/hyperbrowser-scrape-example/)
- [Hyperbrowser Web Search Example](https://apis.io/examples/hyperbrowser/hyperbrowser-web-search-example/)

#### Collections (21)

Postman and Open Collection request collections.

- [Hyperbrowser API](https://apis.io/collections/hyperbrowser/open-hyperbrowser/)
- [Hyperbrowser Agents API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-agents-api/)
- [Hyperbrowser Agents Crawl API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-crawl-api/)
- [Hyperbrowser Agents Extensions API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-extensions-api/)
- [Hyperbrowser Agents Extract API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-extract-api/)
- [Hyperbrowser Agents Profile API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-profile-api/)
- [Hyperbrowser Agents Profiles API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-profiles-api/)
- [Hyperbrowser Agents Scrape API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-scrape-api/)
- [Hyperbrowser Agents Session API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-session-api/)
- [Hyperbrowser Agents Sessions API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-sessions-api/)
- [Hyperbrowser Agents Task API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-task-api/)
- [Hyperbrowser Agents Web API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-web-api/)
- [Hyperbrowser Agents X402 API](https://apis.io/collections/hyperbrowser/open-hyperbrowser-x402-api/)
- [Hyperbrowser Agents API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-agents-api/)
- [Hyperbrowser Crawl API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-crawl-api/)
- [Hyperbrowser Extensions API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-extensions-api/)
- [Hyperbrowser Extract API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-extract-api/)
- [Hyperbrowser Profiles API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-profiles-api/)
- [Hyperbrowser Scrape API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-scrape-api/)
- [Hyperbrowser Sessions API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-sessions-api/)
- [Hyperbrowser Web API](https://apis.io/collections/hyperbrowser/postman-hyperbrowser-web-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Hyperbrowser — jsonschema rules](https://apis.io/rules/hyperbrowser/hyperbrowser-jsonschema-spectral-rules/)
- [Hyperbrowser API Rules](https://apis.io/rules/hyperbrowser/hyperbrowser-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hyperbrowser Authentication](https://apis.io/security/hyperbrowser/hyperbrowser-authentication/)
- [Hyperbrowser Domain Security](https://apis.io/security/hyperbrowser/hyperbrowser-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hyperbrowser Plans Pricing](https://apis.io/plans/hyperbrowser/hyperbrowser-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hyperbrowser Rate Limits](https://apis.io/rate-limits/hyperbrowser/hyperbrowser-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hyperbrowser Finops](https://apis.io/finops/hyperbrowser/hyperbrowser-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hyperbrowser.ai)
- [Documentation](https://docs.hyperbrowser.ai)
- [Getting started](https://docs.hyperbrowser.ai/quickstart)
- [API reference](https://docs.hyperbrowser.ai/api-reference)
- [Pricing](https://hyperbrowser.ai/pricing)
- [Blog](https://hyperbrowser.ai/blog)
- [Terms of service](https://hyperbrowser.ai/terms)
- [Privacy policy](https://hyperbrowser.ai/privacy)
- [GitHub](https://github.com/hyperbrowserai)

## API Evangelist rating

**Kin Score 46.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 57.9 |
| Contract governance | 27.3 |
| Operational transparency | 7.9 |
| Developer ergonomics | 60.7 |
| Access clarity | 39.5 |

**Agent readiness 28.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 20.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hyperbrowser/](https://apis.io/providers/hyperbrowser/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hyperbrowser: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hyperbrowser/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
