# ChartMogul (chartmogul)

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
