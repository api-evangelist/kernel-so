# Kernel (kernel-so)

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
