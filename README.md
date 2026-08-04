# Mercado Pago (mercado-pago)

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

Mercado Pago is the payments and financial-services arm of Mercado Libre, Latin America's largest e-commerce and fintech platform. Founded in 2003, it processes a substantial share of LatAm digital payments across Brazil (PIX, Boleto, cards), Argentina, Mexico (SPEI, OXXO), Chile, Colombia, Peru, and Uruguay, with consumer wallet, merchant acquiring, card issuing, lending, and crypto products layered on top. The developer portal at developers.mercadopago.com exposes a deep payments stack — Checkout Pro (hosted), Checkout Bricks (composable web components), Checkout API (full server-side control), Orders API (next-gen checkout), Subscriptions, Payment Links, Point (in-person card readers), and QR payments — backed by REST APIs and official SDKs in Node.js / TypeScript, Python, PHP, Ruby, Java, .NET, Go, iOS, and Android, plus a CLI, an MCP server for AI agents, e-commerce plugins (WooCommerce, VTEX, Tiendanube, Shopify), and an n8n integration. Regional developer portals (.com.ar, .com.br, .com.mx, .com.cl, .com.co, .com.pe, .com.uy) localise docs and pricing per LATAM market.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- Payments
- Checkout
- Subscriptions
- POS
- QR
- PIX
- SDKs
- Wallet
- Acquiring
- Lending
- Issuing
- Latin America
- Brazil
- Argentina
- Mexico
- Chile
- Colombia
- Peru
- Uruguay
- Fintech

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Mercado Pago Payments API

Core REST API for creating and managing payments across cards, account money, bank transfer (PIX in Brazil, SPEI in Mexico, PSE in Colombia), boleto, OXXO cash, and other LATAM local methods. Supports authorisation, capture, refund, partial refund, cancellation, and status retrieval.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/payments/_payments/post](https://www.mercadopago.com.br/developers/en/reference/payments/_payments/post)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Payments
- Cards
- PIX
- Refunds
- Captures

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/reference/payments/_payments/post)
- [API Reference](https://www.mercadopago.com.br/developers/en/reference)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/openapi/mercado-pago-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout Pro

Hosted, pre-configured checkout experience. Merchants create a preference via API, then redirect the buyer to a Mercado Pago hosted page that handles UI, payment-method selection, 3DS, and returns to a callback URL on completion. Lowest PCI scope and fastest time-to-market.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/checkout-pro/landing](https://www.mercadopago.com.br/developers/en/docs/checkout-pro/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Hosted
- Preferences

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/checkout-pro/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout Bricks

Composable web components ("bricks") merchants embed in their own UI — card form, wallet, payment-method picker, status screen, security code. Lets merchants assemble a branded checkout while Mercado Pago handles PCI scope and tokenisation.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/checkout-bricks/landing](https://www.mercadopago.com.br/developers/en/docs/checkout-bricks/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Web Components
- Bricks
- Tokenization

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/checkout-bricks/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Checkout API

Full server-side checkout control. Tokenise cards client-side, create a payment server-side, manage 3DS challenges, handle capture, refund, and installments — all without redirecting the buyer.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/checkout-api/landing](https://www.mercadopago.com.br/developers/en/docs/checkout-api/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Checkout
- Card Payments
- 3DS
- Installments

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/checkout-api/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Orders API

Next-generation unified Orders API consolidating payments, captures, refunds, and transactions under a single resource. Supports multi-method orders, partial captures, partial refunds, and async processing.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/order/online-payments/create/post](https://www.mercadopago.com.br/developers/en/reference/order/online-payments/create/post)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Orders
- Payments
- Transactions
- Unified API

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/checkout-api/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Subscriptions API

Recurring payment subscriptions (preapproval) with scheduling, shared plans, free trial, proration, and pause / resume / cancel. Supports both subscription plans (preapproval_plan) and per-customer pre-approved schedules (preapproval).

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/subscriptions/landing](https://www.mercadopago.com.br/developers/en/docs/subscriptions/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Subscriptions
- Recurring
- Plans
- Preapproval

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/subscriptions/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Payment Links API

No-code / low-code link generation for collecting a one-off or recurring payment via shareable URL or button — SMS, WhatsApp, email, social.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/payment-link/landing](https://www.mercadopago.com.br/developers/en/docs/payment-link/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Payment Links
- Collection
- No Code

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/payment-link/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Customers & Cards API

Manage stored customers and tokenised cards for one-click and recurring payments. CRUD for customers, addresses, and card tokens.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/customers/_customers/post](https://www.mercadopago.com.br/developers/en/reference/customers/_customers/post)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Customers
- Cards
- Tokenization
- Vault

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/reference/customers/_customers/post)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Merchant Orders API

Aggregate a preference + its payments into a single merchant_order resource for reconciliation, multi-payment handling, and order lifecycle.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/merchant_orders/_merchant_orders/post](https://www.mercadopago.com.br/developers/en/reference/merchant_orders/_merchant_orders/post)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Orders
- Reconciliation

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/reference/merchant_orders/_merchant_orders/post)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Point API (POS)

Integrates merchant systems with Mercado Pago Point card readers for in-person payments. Push an amount to a paired terminal, manage stores, points-of-sale, and terminals, and reconcile via the same payment APIs.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/mp-point/landing](https://www.mercadopago.com.br/developers/en/docs/mp-point/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- POS
- In Person
- Card Reader
- Terminals

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/mp-point/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago QR API

Static and dynamic QR code APIs for in-person collection, with order-linked status retrieval and webhook callbacks. Underpins the Mercado Pago wallet QR pay flow.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/qr-payments/landing](https://www.mercadopago.com.br/developers/en/docs/qr-payments/landing)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- QR
- In Person
- Collections
- Wallet

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/qr-payments/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Chargebacks API

Retrieve and respond to chargebacks, including dispute reason codes and lifecycle states.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/chargebacks/_chargebacks_id/get](https://www.mercadopago.com.br/developers/en/reference/chargebacks/_chargebacks_id/get)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Chargebacks
- Disputes

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/reference/chargebacks/_chargebacks_id/get)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Claims & Disputes API

Post-sale claims, mediations, evidence upload, messages, and notification retrieval for resolving buyer disputes.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/reference/claims/_claims_id/get](https://www.mercadopago.com.br/developers/en/reference/claims/_claims_id/get)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Claims
- Mediation
- Disputes
- Post Sale

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/reference/claims/_claims_id/get)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Reports API

Generate, configure, and download release / settlement / account-money reports for reconciliation and accounting.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/your-integrations/reports/release-report](https://www.mercadopago.com.br/developers/en/docs/your-integrations/reports/release-report)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- Reports
- Settlement
- Reconciliation
- Accounting

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/your-integrations/reports/release-report)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago OAuth 2.0 API

OAuth 2.0 authorisation-code flow for platform integrations: marketplaces and partners obtain delegated access tokens on behalf of merchants.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/security/oauth/introduction](https://www.mercadopago.com.br/developers/en/docs/security/oauth/introduction)
- **Base URL:** `https://api.mercadopago.com`

#### Tags

- OAuth
- Authentication
- Marketplace
- Platform

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/security/oauth/introduction)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Webhooks / Notifications

Event-driven notifications for payments, refunds, chargebacks, subscriptions, merchant orders, and account changes. Webhooks are signed with an x-signature header so receivers can verify authenticity.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/your-integrations/notifications/webhooks](https://www.mercadopago.com.br/developers/en/docs/your-integrations/notifications/webhooks)
- **Base URL:** `customer-configured`

#### Tags

- Webhooks
- Events
- Notifications
- Signed

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/your-integrations/notifications/webhooks)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/asyncapi/mercado-pago-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Node.js SDK

Official Node.js / TypeScript SDK wrapping the Mercado Pago REST APIs for payments, preferences, subscriptions, customers, cards, and merchant orders.

- **Human URL:** [https://github.com/mercadopago/sdk-nodejs](https://github.com/mercadopago/sdk-nodejs)
- **Base URL:** `https://github.com/mercadopago/sdk-nodejs`

#### Tags

- SDK
- Node.js
- TypeScript

#### Properties

- [Repository](https://github.com/mercadopago/sdk-nodejs)
- [SDK](https://www.npmjs.com/package/mercadopago)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Python SDK

Official Python SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-python](https://github.com/mercadopago/sdk-python)
- **Base URL:** `https://github.com/mercadopago/sdk-python`

#### Tags

- SDK
- Python

#### Properties

- [Repository](https://github.com/mercadopago/sdk-python)
- [SDK](https://pypi.org/project/mercadopago/)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago PHP SDK

Official PHP SDK wrapping the Mercado Pago REST APIs. Used by the WooCommerce plugin and most LATAM PHP merchant stacks.

- **Human URL:** [https://github.com/mercadopago/sdk-php](https://github.com/mercadopago/sdk-php)
- **Base URL:** `https://github.com/mercadopago/sdk-php`

#### Tags

- SDK
- PHP

#### Properties

- [Repository](https://github.com/mercadopago/sdk-php)
- [SDK](https://packagist.org/packages/mercadopago/dx-php)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Ruby SDK

Official Ruby SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-ruby](https://github.com/mercadopago/sdk-ruby)
- **Base URL:** `https://github.com/mercadopago/sdk-ruby`

#### Tags

- SDK
- Ruby

#### Properties

- [Repository](https://github.com/mercadopago/sdk-ruby)
- [SDK](https://rubygems.org/gems/mercadopago-sdk)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Java SDK

Official Java SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-java](https://github.com/mercadopago/sdk-java)
- **Base URL:** `https://github.com/mercadopago/sdk-java`

#### Tags

- SDK
- Java

#### Properties

- [Repository](https://github.com/mercadopago/sdk-java)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago .NET SDK

Official .NET / C# SDK wrapping the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-dotnet](https://github.com/mercadopago/sdk-dotnet)
- **Base URL:** `https://github.com/mercadopago/sdk-dotnet`

#### Tags

- SDK
- .NET
- C#

#### Properties

- [Repository](https://github.com/mercadopago/sdk-dotnet)
- [SDK](https://www.nuget.org/packages/mercadopago-sdk)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Go SDK

Official Go SDK for the Mercado Pago REST APIs.

- **Human URL:** [https://github.com/mercadopago/sdk-go](https://github.com/mercadopago/sdk-go)
- **Base URL:** `https://github.com/mercadopago/sdk-go`

#### Tags

- SDK
- Go

#### Properties

- [Repository](https://github.com/mercadopago/sdk-go)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago iOS SDK

Official iOS / Swift mobile SDK providing card tokenisation, hosted payment screens, and Checkout integration for native iOS apps.

- **Human URL:** [https://github.com/mercadopago/sdk-ios](https://github.com/mercadopago/sdk-ios)
- **Base URL:** `https://github.com/mercadopago/sdk-ios`

#### Tags

- SDK
- iOS
- Mobile
- Swift

#### Properties

- [Repository](https://github.com/mercadopago/sdk-ios)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago Android SDK

Official Android / Kotlin mobile SDK for tokenisation, payment screens, and Checkout integration in native Android apps.

- **Human URL:** [https://github.com/mercadopago/sdk-android](https://github.com/mercadopago/sdk-android)
- **Base URL:** `https://github.com/mercadopago/sdk-android`

#### Tags

- SDK
- Android
- Mobile
- Kotlin

#### Properties

- [Repository](https://github.com/mercadopago/sdk-android)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago CLI

Command-line interface for managing Mercado Pago integrations: trigger test events, inspect webhook deliveries, scaffold sample apps, and run local listeners. Distributed via a Homebrew tap.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/cli/landing](https://www.mercadopago.com.br/developers/en/docs/cli/landing)
- **Base URL:** `https://www.mercadopago.com.br/developers/en/docs/cli/landing`

#### Tags

- CLI
- Tooling
- DevEx

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/cli/landing)
- [Repository](https://github.com/mercadopago/homebrew-tap)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago MCP Server

Model Context Protocol server exposing Mercado Pago APIs as tools for AI agents and IDE assistants. Enables agent-driven payment, preference, and checkout workflows from Anthropic, OpenAI, and other MCP-compatible hosts.

- **Human URL:** [https://www.mercadopago.com.br/developers/en/docs/mcp-server/landing](https://www.mercadopago.com.br/developers/en/docs/mcp-server/landing)
- **Base URL:** `https://www.mercadopago.com.br/developers/en/docs/mcp-server/landing`

#### Tags

- MCP
- AI
- Agents
- Anthropic

#### Properties

- [Documentation](https://www.mercadopago.com.br/developers/en/docs/mcp-server/landing)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago WooCommerce Plugin

Official WooCommerce gateway plugin enabling Mercado Pago Checkout Pro, Bricks, and Checkout API payment methods in WordPress stores.

- **Human URL:** [https://github.com/mercadopago/cart-woocommerce](https://github.com/mercadopago/cart-woocommerce)
- **Base URL:** `https://github.com/mercadopago/cart-woocommerce`

#### Tags

- Plugin
- WooCommerce
- WordPress
- E-commerce

#### Properties

- [Repository](https://github.com/mercadopago/cart-woocommerce)
- [Plugin](https://wordpress.org/plugins/woocommerce-mercadopago/)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mercado Pago n8n Node

Official n8n workflow automation node for orchestrating Mercado Pago operations alongside other SaaS apps.

- **Human URL:** [https://github.com/mercadopago/n8n-nodes-mercadopago](https://github.com/mercadopago/n8n-nodes-mercadopago)
- **Base URL:** `https://github.com/mercadopago/n8n-nodes-mercadopago`

#### Tags

- n8n
- Workflow
- Automation
- Integration

#### Properties

- [Repository](https://github.com/mercadopago/n8n-nodes-mercadopago)
- [Postman Collection](collections/mercado-pago.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mercado-pago.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mercadopago.com/)
- [Developers](https://www.mercadopago.com.br/developers/en)
- [Documentation](https://www.mercadopago.com.br/developers/en/docs)
- [API Reference](https://www.mercadopago.com.br/developers/en/reference)
- [Getting Started](https://www.mercadopago.com.br/developers/en/docs/your-integrations/credentials)
- [Status](https://status.mercadopago.com)
- [LinkedIn](https://www.linkedin.com/company/mercadopago)
- [GitHub Organization](https://github.com/mercadopago)
- [Homebrew Tap](https://github.com/mercadopago/homebrew-tap)
- [Discord](https://discord.com/invite/mercadopagodevelopers)
- [Plans](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/plans/mercado-pago-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/rate-limits/mercado-pago-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/finops/mercado-pago-finops.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/vocabulary/mercado-pago-vocabulary.yml)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/json-ld/mercado-pago-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Ruleset](https://raw.githubusercontent.com/api-evangelist/mercado-pago/refs/heads/main/rules/mercado-pago-rules.yml)

## Maintainers

**FN:** API Evangelist
**URL:** https://apievangelist.com
