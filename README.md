# Doceree

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

Doceree Inc. is a US healthcare marketing technology company (Short Hills, New Jersey) operating a global network of physician-only platforms for programmatic messaging and point-of-care advertising to healthcare professionals. Its platform spans HCP programmatic, point-of-care, EHR, email, SMS, co-pay/affordability and account-based messaging channels, backed by a proprietary HCP identity-resolution graph. Doceree's public, machine-readable surface is an advertising-technology one rather than a general-purpose developer API: a versioned ad-request/bidder endpoint (bidder.doceree.com/v1/adrequest), a tracking/beacon endpoint (tracking.doceree.com), a hosted publisher tag (the Doceree Publisher Tag, servedbydoceree.doceree.com/script/render-header.js), a first-party Prebid.js header-bidding adapter (bidder code "doceree", IAB Europe GVL ID 1063), and first-party mobile ad SDKs for iOS (CocoaPods) and Android (JitPack). A second, newer ad-serving generation runs concurrently on dai.doceree.com (POST /drs/* and /dop/*, unversioned) and is used by the iOS SDK 6.x; it carries clinical session, patient, prescription and action-event attributes onto the ad request itself. Doceree publishes no OpenAPI, AsyncAPI, GraphQL schema, MCP server or A2A agent card at any probed host as of August 2026, and no /.well-known/ document on any host.

**Areas:** Advertising · Healthcare · Marketing · AdTech · Programmatic · Header Bidding · Life Sciences · Pharmaceuticals · Point of Care · Identity Resolution · Electronic Health Records · Company

## Doceree on APIs.io

Everything profiled for Doceree is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/doceree/](https://apis.io/providers/doceree/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [Doceree Bidder / Ad Request API](https://apis.io/apis/doceree/bidder/) — The ad-request surface Doceree publisher partners call to fetch an HCP-targeted advertisement. It is the endpoint behind the Doceree Publisher Tag, the…
- [Doceree Tracking API](https://apis.io/apis/doceree/tracking/) — Doceree's measurement and beacon endpoint. The Prebid.js adapter fires GET /v1/hbTimeout and GET /v1/hbBidWon with a base64-encoded, URI-encoded JSON…
- [Doceree DAI Mobile Ad + Identity API](https://apis.io/apis/doceree/dai/) — The current mobile ad-serving, identity and clinical-session surface, used by the Doceree iOS SDK 6.x. Discovered 2026-08-12 by reading Doceree's own…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Doceree Authentication](https://apis.io/security/doceree/doceree-authentication/)
- [Doceree Domain Security](https://apis.io/security/doceree/doceree-domain-security/)
- [Doceree Trust Center](https://apis.io/security/doceree/doceree-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Doceree Plans Pricing](https://apis.io/plans/doceree/doceree-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Doceree Rate Limits](https://apis.io/rate-limits/doceree/doceree-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://doceree.com/)
- [Documentation](https://support.doceree.com/hc/en-us)
- [API reference](https://docs.prebid.org/dev-docs/bidders/doceree.html)
- [Support](https://support.doceree.com/hc/en-us)
- [Blog](https://blog.doceree.com/)
- [Compliance](https://doceree.com/trust)
- [Terms of service](https://doceree.com/us-terms-of-service-advertiser)
- [Privacy policy](https://doceree.com/privacy-policy)
- [GitHub](https://github.com/doceree)

## API Evangelist rating

**Kin Score 36.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 59.5 |
| Access clarity | 43.4 |

**Agent readiness 7.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
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

**Regulatory alignment 28.9** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/doceree/](https://apis.io/providers/doceree/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Doceree: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/doceree/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
