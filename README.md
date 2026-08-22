# Paytronix (paytronix)

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
