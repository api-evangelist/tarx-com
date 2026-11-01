# TARXAN

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

TARXAN Inc (TARX, Austin TX) builds a local-first AI agent runtime: free TARX_OS / TARX Desktop software for Apple Silicon Macs, a shell CLI that installs a local inference daemon and local MCP servers, an optional hosted "Supercomputer" reached through an OpenAI-compatible API (api.tarx.com/v1, model t-supercomputer), and dedicated "Black Box" and humanoid/quadruped hardware. Its public agent surface is a remote MCP server at mcp.tarx.com/mcp (22 anonymous tools, OAuth 2.0 + PKCE for private memory, RFC 8414/9728 metadata) advertised by an A2A 0.3.0 agent card at tarx.com/.well-known/agent-card.json and a prose "cairn" (we.txt, skill.md, courier.md) that tells visiting agents how to register a Soul through plain REST on tarx.com/api. No OpenAPI is published.

**Areas:** Company · AI Agents · Agent Runtime · Local-First AI · Private AI · MCP · A2A · LLM · Inference · Developer Tools · Hardware · Robotics

## TARXAN on APIs.io

Everything profiled for TARXAN is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/tarx-com/](https://apis.io/providers/tarx-com/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [TARX Remote MCP Server](https://apis.io/apis/tarx-com/tarx-remote-mcp-server/) — Streamable-HTTP MCP server (serverInfo tarx 3.18.0, protocol 2025-06-18) exposing 22 tools, 5 prompts and 5 resources anonymously — public TARX context…
- [TARX Supercomputer API](https://apis.io/apis/tarx-com/tarx-supercomputer-api/) — OpenAI-compatible hosted inference API. GET /v1/models lists the single model t-supercomputer (owned_by tarx, OpenRouter slug tarx/t-supercomputer) without…
- [TARX Courier and Souls API](https://apis.io/apis/tarx-com/tarx-courier-and-souls-api/) — Plain REST endpoints on tarx.com documented only for visiting AI agents in we.txt, skill.md and courier.md: GET /api/courier/ping and /api/courier/tick…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [tarx](https://apis.io/servers/tarx-com/tarx/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Tarx Com Agentic Access](https://apis.io/agentic-access/tarx-com/tarx-com-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [TARX Partner Sandbox Fixture](https://apis.io/schemas/tarx-com/tarx-com-partner-sandbox-fixture/)

#### Examples (1)

Example requests and responses.

- [Tarx Com Partner Sandbox Fixture](https://apis.io/examples/tarx-com/tarx-com-partner-sandbox-fixture/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Tarx Com Authentication](https://apis.io/security/tarx-com/tarx-com-authentication/)
- [Tarx Com Domain Security](https://apis.io/security/tarx-com/tarx-com-domain-security/)
- [Tarx Com Vulnerability Disclosure](https://apis.io/security/tarx-com/tarx-com-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Tarx Com Scopes](https://apis.io/scopes/tarx-com/tarx-com-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Tarx Com Plans Pricing](https://apis.io/plans/tarx-com/tarx-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Tarx Com Rate Limits](https://apis.io/rate-limits/tarx-com/tarx-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://tarx.com/)
- [Documentation](https://docs.tarx.com)
- [Getting started](https://docs.tarx.com/start-here/quickstart)
- [Pricing](https://docs.tarx.com/pricing/overview)
- [Sign up](https://tarx.com/join)
- [Support](https://tarx.com/support)
- [Changelog](https://docs.tarx.com/reference/changelog)
- [Blog](https://tarx.com/dispatches)
- [Security](https://tarx.com/security)
- [Terms of service](https://tarx.com/terms)
- [Privacy policy](https://tarx.com/privacy)
- [GitHub](https://github.com/tarx-ai)

## API Evangelist rating

**Kin Score 50.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 6.5 |
| Contract governance | 18.2 |
| Operational transparency | 28.9 |
| Developer ergonomics | 78.6 |
| Access clarity | 76.3 |

**Agent readiness 29.2** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | yes |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 40.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/tarx-com/](https://apis.io/providers/tarx-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for TARXAN: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/tarx-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
