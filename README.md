# Paytronix (paytronix)

Paytronix is a cloud-based digital guest engagement platform for restaurants and convenience stores, providing loyalty programs, gift and stored-value cards, online ordering, branded mobile apps, messaging, and analytics to more than 1,800 brands. Paytronix publishes extensive public integration documentation describing a REST-based Server API with 40-plus services spanning guests, enrollment, transactions, checks, payments, gift, messaging, campaigns, stores, and mobile wallet passes. Authentication supports OAuth, client credentials (integration identifier and secret via HTTP Basic), and B2B flows. A separate Online Ordering API is documented for ordering integrations, making Paytronix a developer-friendly guest engagement provider.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paytronix/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paytronix/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Restaurant
- Loyalty
- Gift Cards
- Online Ordering
- Guest Engagement
- Payments
- Messaging

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Paytronix Server API

The Paytronix Server (PXS) REST API exposes 40-plus services for guest engagement, including Guest, Enrollment, Transaction, Check, Sale, Payment, Gift, Message, Campaign Feedback, Store, and mobile wallet services. Authentication is handled through the OAuth Service, with client credentials supplied via HTTP Basic, plus email and B2B authentication options. Start with the API Primer covering authentication, formatting, and versioning.

- **Human URL:** [https://developers.paytronix.com/pxs_api_reference/index.html](https://developers.paytronix.com/pxs_api_reference/index.html)
- **Base URL:** `https://m{merchantId}.api.paytronix.com/rest/26.6`

#### Tags

- Loyalty
- Transactions
- Payments
- Gift Cards
- Messaging

#### Properties

- [Documentation](https://developers.paytronix.com/pxs_api_reference/index.html)
- [Authentication](https://developers.paytronix.com/pxs_api_reference/oauth.html)
- [Getting Started](https://developers.paytronix.com/welcome/index.html)
- [OpenAPI](openapi/paytronix-server-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paytronix-server-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytronix-server-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/server-api-account-information-reply-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/server-api-account-information-reply-structure.json)
- [Example](examples/server-api-account-information-reply-example.json)
- [J S O N- L D](json-ld/paytronix-server-api-context.jsonld)

### Paytronix Online Ordering API

The Paytronix Online Ordering API supports building and integrating ordering experiences across order methods including in store, online web, online app, call in, call center, and drive through. It connects ordering systems with the broader Paytronix loyalty and guest engagement platform.

- **Human URL:** [http://docs.opendining.net/](http://docs.opendining.net/)
- **Base URL:** `https://api.opendining.net`

#### Tags

- Online Ordering
- Restaurant

#### Properties

- [Documentation](http://docs.opendining.net/)
- [OpenAPI](openapi/paytronix-online-ordering-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/paytronix-online-ordering-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/paytronix-online-ordering-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/online-ordering-api-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/online-ordering-api-order-structure.json)
- [Example](examples/online-ordering-api-order-example.json)
- [J S O N- L D](json-ld/paytronix-online-ordering-api-context.jsonld)

## Common Properties

- [Website](https://www.paytronix.com/)
- [Documentation](https://developers.paytronix.com/)
- [API Reference](https://developers.paytronix.com/pxs_api_reference/index.html)
- [Pricing](https://www.paytronix.com/pricing/)
- [Support](https://www.paytronix.com/support/)
- [Blog](https://www.paytronix.com/blog)
- [LinkedIn](https://www.linkedin.com/company/paytronix-systems)
- [GitHub Organization](https://github.com/paytronix)
- [Spectral Rules](rules/paytronix-spectral-rules.yml)
- [Vocabulary](vocabulary/paytronix-vocabulary.yml)
- [Plans](plans/paytronix-plans-pricing.yml)
- [Rate Limits](rate-limits/paytronix-rate-limits.yml)
- [Fin Ops](finops/paytronix-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
