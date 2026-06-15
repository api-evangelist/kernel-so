# Kernel (kernel-so)

Kernel is browser infrastructure for AI agents and web automations. Founded in 2025 by Catherine Jue (CEO) and Rafael Garcia (CTO) and backed by Accel and Y Combinator (S25), Kernel runs sandboxed Chromium browsers on a unikernel platform with sub-150ms cold starts, built-in stealth mode, residential proxies, CAPTCHA solving, session recording, live view, persistent profiles, and a serverless app platform that co-locates agent code with browsers. Kernel works with Playwright, Puppeteer, Browser Use, Stagehand, Magnitude, Notte, and the Anthropic/OpenAI/Gemini computer-use loops. The REST API at api.onkernel.com exposes browsers, browser pools, profiles, proxies, replays, extensions, computer controls, filesystem, processes, Playwright execution, managed auth, credentials, apps, deployments, invocations, and projects.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kernel-so/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kernel-so/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Agents
- AI
- Artificial Intelligence
- Browser Automation
- Browsers
- Computer Use
- Headless Browsers
- MCP
- Playwright
- Web Agents

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Kernel API

The Kernel REST API at api.onkernel.com is the unified control plane for browser infrastructure. It exposes browser session lifecycle, browser pools, profiles, proxies, replays, extensions, computer-use controls (mouse, keyboard, clipboard, screenshots, batch actions), in-browser filesystem and process exec, Playwright execution, log and telemetry streaming, managed auth connections, credentials, credential providers, apps, deployments, invocations, projects, and API keys. Bearer-token authenticated; OpenAPI 3.1 published via Stainless.

- **Human URL:** [https://www.kernel.sh/docs/api-reference/](https://www.kernel.sh/docs/api-reference/)
- **Base URL:** `https://api.onkernel.com`

#### Tags

- Agents
- Browser Automation
- Browsers
- Computer Use
- Headless Browsers
- Playwright
- Web Agents

#### Properties

- [Documentation](https://www.kernel.sh/docs/api-reference/)
- [Documentation](https://www.kernel.sh/docs/)
- [L L M S T X T](https://www.kernel.sh/docs/llms.txt)
- [OpenAPI](openapi/kernel-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kernel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kernel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](https://app.stainless.com/api/spec/documented/kernel/openapi.documented.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Kernel MCP Server

Hosted Model Context Protocol server at mcp.onkernel.com that exposes Kernel resources (browsers, profiles, proxies, apps) as MCP tools and bundles four standalone tools — computer actions, Playwright execution with replay, shell exec, and documentation search — to Claude, Cursor, VS Code, Zed, and any MCP-compatible agent. Authenticates via OAuth 2.1 or API key.

- **Human URL:** [https://www.kernel.sh/docs/reference/mcp-server](https://www.kernel.sh/docs/reference/mcp-server)
- **Base URL:** `https://mcp.onkernel.com/mcp`

#### Tags

- Agents
- MCP

#### Properties

- [Documentation](https://www.kernel.sh/docs/reference/mcp-server)
- [Source Code](https://github.com/onkernel/kernel-mcp-server)
- [Postman Collection](collections/kernel.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kernel.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.kernel.sh/)
- [Documentation](https://www.kernel.sh/docs/)
- [Documentation](https://www.kernel.sh/docs/api-reference/)
- [L L M S T X T](https://www.kernel.sh/docs/llms.txt)
- [Pricing](https://www.kernel.sh/docs/info/pricing)
- [Changelog](https://www.kernel.sh/changelog)
- [Support](https://www.kernel.sh/docs/info/support)
- [Community](https://www.kernel.sh/docs/community/discord)
- [Source Code](https://github.com/onkernel)
- [Source Code](https://github.com/onkernel/kernel-images)
- [SDK](https://github.com/onkernel/kernel-python-sdk)
- [SDK](https://github.com/onkernel/kernel-node-sdk)
- [SDK](https://github.com/onkernel/kernel-go-sdk)
- [C L I](https://github.com/onkernel/cli)
- [C L I](https://github.com/onkernel/homebrew-tap)
- [M C P Server](https://github.com/onkernel/kernel-mcp-server)
- [SDK](https://github.com/onkernel/cu-playwright-ts)
- [SDK](https://github.com/onkernel/cu-playwright-python)
- [Source Code](https://github.com/onkernel/hypeman)
- [Integrations](https://www.kernel.sh/docs/integrations/overview)
- [Integrations](https://www.kernel.sh/docs/integrations/browser-use)
- [Integrations](https://www.kernel.sh/docs/integrations/stagehand)
- [Integrations](https://www.kernel.sh/docs/integrations/magnitude)
- [Integrations](https://www.kernel.sh/docs/integrations/notte)
- [Integrations](https://www.kernel.sh/docs/integrations/claude-agent-sdk)
- [Integrations](https://www.kernel.sh/docs/integrations/computer-use/anthropic)
- [Integrations](https://www.kernel.sh/docs/integrations/computer-use/openai)
- [Integrations](https://www.kernel.sh/docs/integrations/computer-use/gemini)
- [Integrations](https://www.kernel.sh/docs/integrations/vercel/marketplace)
- [Integrations](https://www.kernel.sh/docs/integrations/1password)
- [Migration](https://www.kernel.sh/docs/migrations/scrapybara)
- [Funding](https://www.ycombinator.com/companies/kernel)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com/
