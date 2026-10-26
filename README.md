# ChartMogul (chartmogul)

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

ChartMogul is a subscription analytics platform for SaaS companies that unifies billing data, customer information, and revenue analytics into one real-time view of MRR, churn, LTV, cohorts, and growth trends. The ChartMogul REST API provides programmatic access to import customers, subscriptions, invoices, transactions, and plans, and to read metrics, customer segments, and forecasts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chartmogul/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chartmogul/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Subscription Analytics
- SaaS Metrics
- Revenue Analytics
- MRR
- Churn
- Cohorts
- Billing

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### ChartMogul REST API

REST API for ChartMogul providing endpoints for importing customers, subscriptions, plans, invoices, and transactions, plus reading SaaS metrics (MRR, ARR, ARPA, churn, LTV), customer attributes, segments, and forecasts. All requests are over HTTPS and authenticate via HTTP Basic Auth using an API key as the username.

- **Human URL:** [https://dev.chartmogul.com/docs/introduction](https://dev.chartmogul.com/docs/introduction)
- **Base URL:** `https://api.chartmogul.com`

#### Tags

- Subscription Analytics
- SaaS Metrics
- Import API
- Metrics API
- Customers
- Subscriptions
- Invoices
- Basic Auth

#### Properties

- [Documentation](https://dev.chartmogul.com/docs/introduction)
- [Authentication](https://dev.chartmogul.com/docs/authentication)
- [Getting Started](https://help.chartmogul.com/hc/en-us/articles/207413269-Getting-started-with-our-API)
- [Git Hub  S D K](https://github.com/chartmogul)
- [Postman Collection](collections/chartmogul.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chartmogul.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ChartMogul Webhooks

Outbound webhook destination for ChartMogul. ChartMogul POSTs JSON event bodies to a subscriber-configured HTTPS endpoint whenever a customer-level MRR movement is recorded. Only the `mrr_movement` event type is documented; movement_type categorizes the event as new_biz, churn, expansion, contraction, or reactivation.

- **Human URL:** [https://dev.chartmogul.com/docs/destinations/webhooks](https://dev.chartmogul.com/docs/destinations/webhooks)

#### Tags

- Webhooks
- Events
- AsyncAPI
- MRR Movement
- Subscription Analytics

#### Properties

- [Documentation](https://dev.chartmogul.com/docs/destinations/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/chartmogul/refs/heads/main/openapi/chartmogul-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/chartmogul.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chartmogul.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/chartmogul)
- [Website](https://chartmogul.com)
- [Documentation](https://dev.chartmogul.com/docs/introduction)
- [Pricing](https://chartmogul.com/pricing)
- [Sign Up](https://app.chartmogul.com/sign_up)
- [GitHub Organization](https://github.com/chartmogul)
- [M C P Server](https://github.com/chartmogul/chartmogul-mcp-server)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
