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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Doceree Inc. is a US healthcare marketing technology company (Short Hills, New Jersey) operating a
global network of physician-only platforms for programmatic messaging and point-of-care advertising
to healthcare professionals. Its channels span HCP programmatic, point-of-care, EHR, email, SMS,
co-pay/affordability and account-based messaging, backed by a proprietary HCP identity-resolution
graph.

## Public API surface

Doceree's public, machine-readable surface is an ad-tech one rather than a general-purpose developer
API. There is **no OpenAPI, AsyncAPI, GraphQL schema, MCP server or A2A agent card** at any host
probed on 2026-08-04. What is public:

| Surface | Where |
|---|---|
| Bidder / ad request API | `https://bidder.doceree.com` — `GET /v1/adrequest` |
| Tracking / beacon API | `https://tracking.doceree.com` — `GET /v1/hbTimeout`, `GET /v1/hbBidWon` |
| Doceree Publisher Tag | https://servedbydoceree.doceree.com/script/render-header.js |
| Prebid.js header-bidding adapter | bidder code `doceree`, IAB Europe GVL ID 1063 |
| iOS ad SDK | CocoaPods `DocereeAdSdk`; sources at https://github.com/doceree/ios-sdk (MIT) |
| Android ad SDK | documented via JitPack; coordinates behind a sign-in-gated support article |

The fullest public parameter reference is the
[Prebid.js bidder documentation](https://docs.prebid.org/dev-docs/bidders/doceree.html).

## Links

- Website — https://doceree.com/
- Publishers / integration — https://doceree.com/publishers
- Support / help center — https://support.doceree.com/hc/en-us
- Trust & compliance — https://doceree.com/trust
- Blog — https://blog.doceree.com/
- GitHub — https://github.com/doceree
- Exchange login — https://exchange.doceree.com/login
- Harvest lead (secondary market) — https://forgeglobal.com/doceree_stock/
