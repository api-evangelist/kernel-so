# Kernel (kernel-so)

Kernel is browser infrastructure for AI agents and web automations. Founded in 2025 by Catherine Jue (CEO) and Rafael Garcia (CTO), based in San Francisco, and backed by Accel and Y Combinator (S25), Kernel runs sandboxed Chromium browsers on a unikernel-based platform with sub-150ms cold starts, built-in stealth mode, residential / ISP / datacenter / custom proxies, automatic CAPTCHA solving, MP4 session replays, live view, persistent profiles, and a serverless app platform that co-locates agent code alongside browsers to minimize control-loop latency. The platform is trusted by Cash App, Rye, Framer, and 1,000+ other teams.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/kernel-so/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

 - Agents, AI, Artificial Intelligence, Browser Automation, Browsers, Computer Use, Headless Browsers, MCP, Playwright, Web Agents

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## Pricing & Limits

| Tier | Base | Included Credits | Browser Concurrency | App Concurrency | Notable |
|---|---|---|---|---|---|
| Developer (Free) | $0/mo | $5/mo | 5 | 5 | No replays, profiles, extensions, proxies, or pools |
| Hobbyist | $30/mo | $10/mo | 10 | 10 | 7-day replays, profiles, managed auth |
| Startup | $200/mo | $50/mo | 50 | 50 | 30-day replays, extensions, custom proxies, GPU, 100 reserved pools |
| Enterprise | Custom | Custom | Custom | Custom | Custom |

Per-second browser metering: headless `$0.0000166667/s`, headful `$0.0001333336/s`, headful + GPU `$0.0008000016/s` (GPU requires Startup tier minimum).

## APIs

### Kernel API

The Kernel REST API at `api.onkernel.com` is the unified control plane for browser infrastructure. It exposes browser session lifecycle, browser pools, profiles, proxies, replays, extensions, computer-use controls (mouse, keyboard, clipboard, screenshots, batch actions), in-browser filesystem and process exec, Playwright execution, log and telemetry streaming, managed auth connections, credentials, credential providers, apps, deployments, invocations, projects, and API keys. Bearer-token authenticated. OpenAPI 3.1 published via Stainless.

**Human URL:** [https://www.kernel.sh/docs/api-reference/](https://www.kernel.sh/docs/api-reference/)
**Base URL:** `https://api.onkernel.com`
**Version:** 0.1.0

- [API Reference](https://www.kernel.sh/docs/api-reference/)
- [Docs](https://www.kernel.sh/docs/)
- [llms.txt](https://www.kernel.sh/docs/llms.txt)
- [OpenAPI (local)](openapi/kernel-openapi.yml)
- [OpenAPI (Stainless)](https://app.stainless.com/api/spec/documented/kernel/openapi.documented.yml)

#### Tagged resource groups in the OpenAPI

`Browsers`, `Browser Pools`, `Browser Computer Controls`, `Browser Filesystem`, `Browser Logs`, `Browser Playwright`, `Browser Processes`, `Browser Replays`, `Browser Telemetry`, `Extensions`, `Profiles`, `Proxies`, `Apps`, `Deployments`, `Invocations`, `Managed Auth`, `Credentials`, `Credential Providers`, `Projects`, `API Keys`.

### Kernel MCP Server

Hosted Model Context Protocol server at `mcp.onkernel.com/mcp` that exposes Kernel resources (browsers, profiles, proxies, apps) as MCP `manage_*` tools and bundles four standalone tools — computer actions, Playwright execution with video replay, shell exec, and documentation search — to Claude, Cursor, VS Code, Zed, and any MCP-compatible agent. OAuth 2.1 or API key.

**Human URL:** [https://www.kernel.sh/docs/reference/mcp-server](https://www.kernel.sh/docs/reference/mcp-server)
**Endpoint:** `https://mcp.onkernel.com/mcp`

- [Docs](https://www.kernel.sh/docs/reference/mcp-server)
- [Source — kernel-mcp-server](https://github.com/onkernel/kernel-mcp-server)

## Common Properties

- [Kernel — Portal](https://www.kernel.sh/)
- [Documentation](https://www.kernel.sh/docs/)
- [API Reference](https://www.kernel.sh/docs/api-reference/)
- [llms.txt](https://www.kernel.sh/docs/llms.txt)
- [Pricing & Limits](https://www.kernel.sh/docs/info/pricing)
- [Changelog](https://www.kernel.sh/changelog)
- [Support](https://www.kernel.sh/docs/info/support)
- [Discord](https://www.kernel.sh/docs/community/discord)
- [GitHub — onkernel](https://github.com/onkernel)
- [kernel-images (Browsers-as-a-service)](https://github.com/onkernel/kernel-images)
- [Python SDK](https://github.com/onkernel/kernel-python-sdk)
- [Node / TypeScript SDK](https://github.com/onkernel/kernel-node-sdk)
- [Go SDK](https://github.com/onkernel/kernel-go-sdk)
- [Kernel CLI](https://github.com/onkernel/cli)
- [Homebrew Tap](https://github.com/onkernel/homebrew-tap) — `brew install onkernel/tap/kernel`
- [Kernel MCP Server (source)](https://github.com/onkernel/kernel-mcp-server)
- [cu-playwright-ts](https://github.com/onkernel/cu-playwright-ts) — map Claude Computer Use to Playwright
- [cu-playwright-python](https://github.com/onkernel/cu-playwright-python)
- [hypeman](https://github.com/onkernel/hypeman) — multi-hypervisor VM runtime (Cloud Hypervisor, Firecracker, QEMU, Apple Virtualization)
- [Integrations Overview](https://www.kernel.sh/docs/integrations/overview)
- [Browser Use](https://www.kernel.sh/docs/integrations/browser-use)
- [Stagehand](https://www.kernel.sh/docs/integrations/stagehand)
- [Magnitude](https://www.kernel.sh/docs/integrations/magnitude)
- [Notte](https://www.kernel.sh/docs/integrations/notte)
- [Claude Agent SDK](https://www.kernel.sh/docs/integrations/claude-agent-sdk)
- [Anthropic Computer Use](https://www.kernel.sh/docs/integrations/computer-use/anthropic)
- [OpenAI Computer Use](https://www.kernel.sh/docs/integrations/computer-use/openai)
- [Gemini Computer Use](https://www.kernel.sh/docs/integrations/computer-use/gemini)
- [Vercel Marketplace](https://www.kernel.sh/docs/integrations/vercel/marketplace)
- [1Password](https://www.kernel.sh/docs/integrations/1password)
- [Migrate from Scrapybara](https://www.kernel.sh/docs/migrations/scrapybara)
- [Y Combinator (S25)](https://www.ycombinator.com/companies/kernel)

## Maintainers

**FN:** API Evangelist

**Email:** [info@apievangelist.com](mailto:info@apievangelist.com)

**URL:** [https://apievangelist.com/](https://apievangelist.com/)
