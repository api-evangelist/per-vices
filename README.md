# Per Vices

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

Per Vices Corporation is a Toronto-based company that designs and manufactures high-performance software defined radio (SDR) platforms, where signal tuning is handled in hardware while the remaining radio functionality runs in software so a single application-agnostic platform can serve many markets. Its product line includes Cyan (up to 16 independent radio chains, near-DC to 18 GHz), Crimson TNG (4 Rx / 4 Tx, near-DC to 6 GHz), Chestnut (near-DC to 9 GHz on an Intel Stratix 10 FPGA), and Calamine (receive-only, near-DC to 40 GHz). Per Vices ships open-source host software and firmware built on the UHD (USRP Hardware Driver) framework rather than a public web API; developers program the radios through the UHD C++ driver, GNU Radio integration, and example applications published on its GitHub org, with full integration support provided directly to customers. Control of the radio is device-local rather than internet-facing: an on-device web UI and socket.io channel on the SDR management port, plus the UHD state tree read and written with the uhd_manual_get / uhd_manual_set utilities. Unusually for its market, Per Vices publishes list prices for every platform configuration on a public pricing page. It publishes no public REST/OpenAPI web API surface, no MCP server and no A2A agent card; every /.well-known/ path returned 404 on both hosts on 2026-08-14.

**Areas:** Company · Software Defined Radio · SDR · Radio Frequency · Wireless · Hardware · FPGA · Telecommunications · Embedded Systems

## Per Vices on APIs.io

Everything profiled for Per Vices is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/per-vices/](https://apis.io/providers/per-vices/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Per Vices Domain Security](https://apis.io/security/per-vices/per-vices-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Per Vices Plans Pricing](https://apis.io/plans/per-vices/per-vices-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Per Vices Rate Limits](https://apis.io/rate-limits/per-vices/per-vices-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.pervices.com)
- [Documentation](https://support.pervices.com/)
- [Getting started](https://support.pervices.com/how-to/pvht-1-physicalsetup/)
- [Pricing](https://www.pervices.com/pricing/)
- [Support](https://support.pervices.com)
- [Blog](https://www.pervices.com/blog)
- [Terms of service](https://www.pervices.com/terms-conditions/)
- [GitHub](https://github.com/pervices)

## API Evangelist rating

**Kin Score 25.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 55.4 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 18.4 |
| Developer ergonomics | 42.9 |
| Access clarity | 52.6 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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

**Regulatory alignment 8.3** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/per-vices/](https://apis.io/providers/per-vices/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Per Vices: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/per-vices/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
