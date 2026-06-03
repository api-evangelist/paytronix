# Paytronix (paytronix)
Paytronix is a cloud-based digital guest engagement platform for restaurants and convenience stores, providing loyalty programs, gift and stored-value cards, online ordering, branded mobile apps, messaging, and analytics to more than 1,800 brands. Paytronix publishes extensive public integration documentation describing a REST-based Server API with 40-plus services spanning guests, enrollment, transactions, checks, payments, gift, messaging, campaigns, stores, and mobile wallet passes. Authentication supports OAuth, client credentials (integration identifier and secret via HTTP Basic), and B2B flows. A separate Online Ordering API is documented for ordering integrations, making Paytronix a developer-friendly guest engagement provider.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/paytronix/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Loyalty, Gift Cards, Online Ordering, Guest Engagement, Payments, Messaging

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### Paytronix Server API
The Paytronix Server (PXS) REST API exposes 40-plus services for guest engagement, including Guest, Enrollment, Transaction, Check, Sale, Payment, Gift, Message, Campaign Feedback, Store, and mobile wallet services. Authentication is handled through the OAuth Service, with client credentials supplied via HTTP Basic, plus email and B2B authentication options. Start with the API Primer covering authentication, formatting, and versioning.

**Human URL:** [https://developers.paytronix.com/pxs_api_reference/index.html](https://developers.paytronix.com/pxs_api_reference/index.html)

#### Tags:

 - Loyalty, Transactions, Payments, Gift Cards, Messaging

#### Properties

- [Documentation](https://developers.paytronix.com/pxs_api_reference/index.html)
- [Authentication](https://developers.paytronix.com/pxs_api_reference/oauth.html)
- [GettingStarted](https://developers.paytronix.com/welcome/index.html)
- [OpenAPI](openapi/paytronix-server-api-openapi.yml)
- [JSONSchema — Account Information Reply Schema](json-schema/server-api-account-information-reply-schema.json)
- [JSONStructure — Account Information Reply Structure](json-structure/server-api-account-information-reply-structure.json)
- [Example — Account Information Reply Example](examples/server-api-account-information-reply-example.json)
- [JSON-LD](json-ld/paytronix-server-api-context.jsonld)

### Paytronix Online Ordering API
The Paytronix Online Ordering API supports building and integrating ordering experiences across order methods including in store, online web, online app, call in, call center, and drive through. It connects ordering systems with the broader Paytronix loyalty and guest engagement platform.

**Human URL:** [http://docs.opendining.net/](http://docs.opendining.net/)

#### Tags:

 - Online Ordering, Restaurant

#### Properties

- [Documentation](http://docs.opendining.net/)
- [OpenAPI](openapi/paytronix-online-ordering-api-openapi.yml)
- [JSONSchema — Order Schema](json-schema/online-ordering-api-order-schema.json)
- [JSONStructure — Order Structure](json-structure/online-ordering-api-order-structure.json)
- [Example — Order Example](examples/online-ordering-api-order-example.json)
- [JSON-LD](json-ld/paytronix-online-ordering-api-context.jsonld)

## Common Properties

- [Website](https://www.paytronix.com/)
- [Documentation](https://developers.paytronix.com/)
- [APIReference](https://developers.paytronix.com/pxs_api_reference/index.html)
- [Pricing](https://www.paytronix.com/pricing/)
- [Support](https://www.paytronix.com/support/)
- [Blog](https://www.paytronix.com/blog)
- [LinkedIn](https://www.linkedin.com/company/paytronix-systems)
- [GitHubOrganization](https://github.com/paytronix)
- [SpectralRules](rules/paytronix-spectral-rules.yml)
- [Vocabulary](vocabulary/paytronix-vocabulary.yml)
- [Plans](plans/paytronix-plans-pricing.yml)
- [RateLimits](rate-limits/paytronix-rate-limits.yml)
- [FinOps](finops/paytronix-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Loyalty Programs | Points, tiers, rewards, challenges, and referrals managed through the Server API Guest, Transaction, and Check services. |
| Gift And Stored Value | Sell, reload, redeem, balance, and exchange gift and stored-value cards via the Gift and Transaction services. |
| Online Ordering | Restaurant and menu discovery, search, and order creation and submission across six order methods via the Online Ordering API. |
| Payments | Stored-value recharge, saved payment methods, auto recharge, and Stripe/Apple Pay/Spreedly integration via the Payment service. |
| Guest Enrollment | Create, activate, and register virtual and physical cards with configurable enrollment fields via the Enrollment service. |
| Messaging And Campaigns | Guest messaging, campaign feedback, and message-frequency preferences managed through the messaging services. |

## Use Cases

| Name | Description |
|------|-------------|
| Branded Loyalty Mobile App | Authenticate guests with the OAuth Service and surface balances, tiers, and transaction history from the Guest service. |
| Point-Of-Sale Loyalty Integration | Activate cards, accrue points, and redeem rewards at the register using the Transaction and Check services. |
| Gift Card Program | Sell and redeem gift cards online and in store with the Gift service and stored-value recharge via the Payment service. |
| Online And Mobile Ordering | Build ordering experiences with restaurant/menu search and order submission through the Online Ordering API. |

## Integrations

| Name | Description |
|------|-------------|
| Stripe | Payment processing via checkout sessions and payment intents in the Payment service. |
| Apple Pay | Apple Pay merchant validation and domain registration in the Payment service. |
| Spreedly | Card tokenization via Spreedly iframe parameters in the Payment service. |
| Apple Wallet | Mobile wallet passes via the Apple Passbook service. |
| Google Wallet | Mobile wallet passes via the Google Wallet (Android Pay) service. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Paytronix Server API](openapi/paytronix-server-api-openapi.yml)
- [Paytronix Online Ordering API](openapi/paytronix-online-ordering-api-openapi.yml)

### JSON Schema

45 JSON Schema files extracted from the OpenAPI component schemas, in [json-schema/](json-schema/).

### JSON Structure

45 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Paytronix Server API Context](json-ld/paytronix-server-api-context.jsonld)
- [Paytronix Online Ordering API Context](json-ld/paytronix-online-ordering-api-context.jsonld)

### Examples

45 example payloads in [examples/](examples/).

## Capabilities

Naftiko capabilities, one self-contained file per business surface (OpenAPI tag), each exposing a REST and an MCP adapter routed through its own inline consumes block.

| Capability | API | Tools |
|------------|-----|-------|
| [OAuth](capabilities/server-api-oauth.yaml) | Paytronix Server API | 1 |
| [Guest](capabilities/server-api-guest.yaml) | Paytronix Server API | 5 |
| [Enrollment](capabilities/server-api-enrollment.yaml) | Paytronix Server API | 3 |
| [Transaction](capabilities/server-api-transaction.yaml) | Paytronix Server API | 4 |
| [Gift](capabilities/server-api-gift.yaml) | Paytronix Server API | 4 |
| [Payment](capabilities/server-api-payment.yaml) | Paytronix Server API | 2 |
| [Store](capabilities/server-api-store.yaml) | Paytronix Server API | 2 |
| [Check](capabilities/server-api-check.yaml) | Paytronix Server API | 2 |
| [Restaurants](capabilities/online-ordering-api-restaurants.yaml) | Paytronix Online Ordering API | 1 |
| [Menu Items](capabilities/online-ordering-api-menu-items.yaml) | Paytronix Online Ordering API | 1 |
| [Search](capabilities/online-ordering-api-search.yaml) | Paytronix Online Ordering API | 2 |
| [Orders](capabilities/online-ordering-api-orders.yaml) | Paytronix Online Ordering API | 3 |

## Vocabulary

- [Paytronix Vocabulary](vocabulary/paytronix-vocabulary.yml) — Unified taxonomy mapping 12 resources, 15 actions, 12 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Paytronix Spectral Ruleset](rules/paytronix-spectral-rules.yml) — 33 rules across metadata, servers, operations, tags, parameters, request bodies, responses, schemas, security, and HTTP-method categories enforcing Paytronix API conventions.

## Plans, Rate Limits & FinOps

- [Plans & Pricing](plans/paytronix-plans-pricing.yml) — Custom, quote-based platform agreement plus Customer Success Plan service tiers (API Commons Plans 0.1).
- [Rate Limits](rate-limits/paytronix-rate-limits.yml) — No public numeric limits; per-integration scoping (API Commons Rate Limits 0.1).
- [FinOps](finops/paytronix-finops.yml) — FOCUS-aligned subscription + take-rate billing model (FinOps Framework 1.0).

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
