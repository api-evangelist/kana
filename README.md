# Kana

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

Kana is an agentic AI growth and marketing platform that helps brands discover high-precision audiences, optimize acquisition efficiency, and stay visible across AI-driven discovery environments such as LLM answer engines, search copilots, and autonomous agents. Founded by martech veterans Tom Chavez and Vivek Vaidya (previously Rapt, acquired by Microsoft, and Krux, acquired by Salesforce) and incubated in the super{set} startup studio, Kana raised a $15M seed round led by Mayfield in February 2026. The platform orchestrates specialized AI agents that reason over customer data, plan multi-step workflows, and recommend next-best actions across a suite of purpose-built applications: Campaign Orchestrator, Marketing Intelligence, Personalization, Synthetic Data Generation, Media Proposal Generator, Category Intelligence, Audience Builder, OmniChannel Media Planner, and an Agentic Data Platform. Proprietary just-in-time data integration connects to existing CRM, CDP, marketing-automation, and data-warehouse systems without disruptive infrastructure changes, keeping a human-in-the-loop review step. Kana ships no public developer portal, but its application host apps.kana.ai does expose a real callable surface: an OAuth 2.0 authorization server whose RFC 8414 metadata is served anonymously and declares MCP protocol 2025-03-26 with mcp:read / mcp:write / kana:read / kana:write scopes, plus a per-deployment MCP endpoint and an api-key-authenticated Skill API for running pipelines and retrieving their outputs. Everything but the OAuth metadata sits behind a 401, so this profile captures Kana's public identity, legal/compliance posture, authentication and scope model, and the shape of the gated API surface.

**Areas:** Company · Marketing · Artificial Intelligence · AI Agents · Marketing Technology · Audience Intelligence · Customer Data Platform · AI Search Optimization · Growth

## Kana on APIs.io

Everything profiled for Kana is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kana/](https://apis.io/providers/kana/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Kana Skill API](https://apis.io/apis/kana/kana-skill-api/) — The callable surface a deployed Kana pipeline ("skill") exposes on the Kana application host. POST /skill/{pipelineid} starts a run and returns a runid; GET…
- [Kana MCP Server](https://apis.io/apis/kana/kana-mcp-server/) — Kana exposes each deployed agent/orchestrator as a remote MCP server at https://apps.kana.ai/mcp/{public access key}, fronted by the platform's OAuth 2.0…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Kana MCP Server](https://apis.io/servers/kana/kana-mcp-server/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Kana Authentication](https://apis.io/security/kana/kana-authentication/)
- [Kana Domain Security](https://apis.io/security/kana/kana-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Kana Scopes](https://apis.io/scopes/kana/kana-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kana Plans Pricing](https://apis.io/plans/kana/kana-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kana Rate Limits](https://apis.io/rate-limits/kana/kana-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kana.ai)
- [Getting started](https://www.kana.ai/get-started)
- [Pricing](https://www.kana.ai/get-started)
- [Sign up](https://www.kana.ai/get-started)
- [Support](https://www.kana.ai/contact-us)
- [Blog](https://www.kana.ai/blog)
- [Compliance](https://www.kana.ai/legal)
- [Privacy policy](https://www.kana.ai/privacy-policy)

## API Evangelist rating

**Kin Score 32.6** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 0.0 |
| Developer ergonomics | 31.0 |
| Access clarity | 73.7 |

**Agent readiness 23.5** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | templated |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 32.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kana/](https://apis.io/providers/kana/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kana: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kana/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
