# Mercado Pago

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

Mercado Pago is the payments and financial-services arm of Mercado Libre, Latin America's largest e-commerce and fintech platform. Founded in 2003, it processes a substantial share of LatAm digital payments across Brazil (PIX, Boleto, cards), Argentina, Mexico (SPEI, OXXO), Chile, Colombia, Peru, and Uruguay, with consumer wallet, merchant acquiring, card issuing, lending, and crypto products layered on top. The developer portal at developers.mercadopago.com exposes a deep payments stack — Checkout Pro (hosted), Checkout Bricks (composable web components), Checkout API (full server-side control), Orders API (next-gen checkout), Subscriptions, Payment Links, Point (in-person card readers), and QR payments — backed by REST APIs and official SDKs in Node.js / TypeScript, Python, PHP, Ruby, Java, .NET, Go, iOS, and Android, plus a CLI, an MCP server for AI agents, e-commerce plugins (WooCommerce, VTEX, Tiendanube, Shopify), and an n8n integration. Regional developer portals (.com.ar, .com.br, .com.mx, .com.cl, .com.co, .com.pe, .com.uy) localise docs and pricing per LATAM market.

**Areas:** Payments · Checkout · Subscription · Point-of-Sale · QR · Pix · SDK · Wallets · Acquiring · Lending · Issuing · Latin America

## Mercado Pago on APIs.io

Everything profiled for Mercado Pago is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/mercado-pago/](https://apis.io/providers/mercado-pago/)** — or go straight to one of the APIs or properties below.

### APIs (44)

- [Mercado Pago Checkout Pro](https://apis.io/apis/mercado-pago/checkout-pro/) — Hosted, pre-configured checkout experience. Merchants create a preference via API, then redirect the buyer to a Mercado Pago hosted page that handles UI,…
- [Mercado Pago Checkout Bricks](https://apis.io/apis/mercado-pago/checkout-bricks/) — Composable web components ("bricks") merchants embed in their own UI — card form, wallet, payment-method picker, status screen, security code. Lets…
- [Mercado Pago Checkout API](https://apis.io/apis/mercado-pago/checkout-api/) — Full server-side checkout control. Tokenise cards client-side, create a payment server-side, manage 3DS challenges, handle capture, refund, and installments…
- [Mercado Pago Orders API](https://apis.io/apis/mercado-pago/orders/) — Next-generation unified Orders API consolidating payments, captures, refunds, and transactions under a single resource. Supports multi-method orders,…
- [Mercado Pago Subscriptions API](https://apis.io/apis/mercado-pago/subscriptions/) — Recurring payment subscriptions (preapproval) with scheduling, shared plans, free trial, proration, and pause / resume / cancel. Supports both subscription…
- [Mercado Pago Payment Links API](https://apis.io/apis/mercado-pago/payment-links/) — No-code / low-code link generation for collecting a one-off or recurring payment via shareable URL or button — SMS, WhatsApp, email, social.
- [Mercado Pago Customers & Cards API](https://apis.io/apis/mercado-pago/customers-cards/) — Manage stored customers and tokenised cards for one-click and recurring payments. CRUD for customers, addresses, and card tokens.
- [Mercado Pago Merchant Orders API](https://apis.io/apis/mercado-pago/merchant-orders/) — Aggregate a preference + its payments into a single merchant_order resource for reconciliation, multi-payment handling, and order lifecycle.
- [Mercado Pago Point API (POS)](https://apis.io/apis/mercado-pago/point/) — Integrates merchant systems with Mercado Pago Point card readers for in-person payments. Push an amount to a paired terminal, manage stores, points-of-sale,…
- [Mercado Pago QR API](https://apis.io/apis/mercado-pago/qr/) — Static and dynamic QR code APIs for in-person collection, with order-linked status retrieval and webhook callbacks. Underpins the Mercado Pago wallet QR pay…
- [Mercado Pago Chargebacks API](https://apis.io/apis/mercado-pago/chargebacks/) — Retrieve and respond to chargebacks, including dispute reason codes and lifecycle states.
- [Mercado Pago Claims & Disputes API](https://apis.io/apis/mercado-pago/claims/) — Post-sale claims, mediations, evidence upload, messages, and notification retrieval for resolving buyer disputes.
- [Mercado Pago Reports API](https://apis.io/apis/mercado-pago/reports/) — Generate, configure, and download release / settlement / account-money reports for reconciliation and accounting.
- [Mercado Pago OAuth 2.0 API](https://apis.io/apis/mercado-pago/oauth/) — OAuth 2.0 authorisation-code flow for platform integrations: marketplaces and partners obtain delegated access tokens on behalf of merchants.
- [Mercado Pago Webhooks / Notifications](https://apis.io/apis/mercado-pago/webhooks/) — Event-driven notifications for payments, refunds, chargebacks, subscriptions, merchant orders, and account changes. Webhooks are signed with an x-signature…
- [Mercado Pago Node.js SDK](https://apis.io/apis/mercado-pago/sdk-node/) — Official Node.js / TypeScript SDK wrapping the Mercado Pago REST APIs for payments, preferences, subscriptions, customers, cards, and merchant orders.
- [Mercado Pago Python SDK](https://apis.io/apis/mercado-pago/sdk-python/) — Official Python SDK wrapping the Mercado Pago REST APIs.
- [Mercado Pago PHP SDK](https://apis.io/apis/mercado-pago/sdk-php/) — Official PHP SDK wrapping the Mercado Pago REST APIs. Used by the WooCommerce plugin and most LATAM PHP merchant stacks.
- [Mercado Pago Ruby SDK](https://apis.io/apis/mercado-pago/sdk-ruby/) — Official Ruby SDK wrapping the Mercado Pago REST APIs.
- [Mercado Pago Java SDK](https://apis.io/apis/mercado-pago/sdk-java/) — Official Java SDK wrapping the Mercado Pago REST APIs.
- [Mercado Pago .NET SDK](https://apis.io/apis/mercado-pago/sdk-dotnet/) — Official .NET / C# SDK wrapping the Mercado Pago REST APIs.
- [Mercado Pago Go SDK](https://apis.io/apis/mercado-pago/sdk-go/) — Official Go SDK for the Mercado Pago REST APIs.
- [Mercado Pago iOS SDK](https://apis.io/apis/mercado-pago/sdk-ios/) — Official iOS / Swift mobile SDK providing card tokenisation, hosted payment screens, and Checkout integration for native iOS apps.
- [Mercado Pago Android SDK](https://apis.io/apis/mercado-pago/sdk-android/) — Official Android / Kotlin mobile SDK for tokenisation, payment screens, and Checkout integration in native Android apps.
- [Mercado Pago CLI](https://apis.io/apis/mercado-pago/cli/) — Command-line interface for managing Mercado Pago integrations: trigger test events, inspect webhook deliveries, scaffold sample apps, and run local…
- [Mercado Pago MCP Server](https://apis.io/apis/mercado-pago/mcp/) — Model Context Protocol server exposing Mercado Pago APIs as tools for AI agents and IDE assistants. Enables agent-driven payment, preference, and checkout…
- [Mercado Pago WooCommerce Plugin](https://apis.io/apis/mercado-pago/woocommerce/) — Official WooCommerce gateway plugin enabling Mercado Pago Checkout Pro, Bricks, and Checkout API payment methods in WordPress stores.
- [Mercado Pago n8n Node](https://apis.io/apis/mercado-pago/n8n/) — Official n8n workflow automation node for orchestrating Mercado Pago operations alongside other SaaS apps.
- [Mercado Pago Authentication API](https://apis.io/apis/mercado-pago/mercado-pago-authentication-api/) — OAuth 2.0 authorisation flows
- [Mercado Pago Cards API](https://apis.io/apis/mercado-pago/mercado-pago-cards-api/) — Tokenised customer cards
- [Mercado Pago Chargebacks API](https://apis.io/apis/mercado-pago/mercado-pago-chargebacks-api/) — Read chargebacks and disputes
- [Mercado Pago Claims API](https://apis.io/apis/mercado-pago/mercado-pago-claims-api/) — Buyer claims, mediations, and evidence
- [Mercado Pago Customers API](https://apis.io/apis/mercado-pago/mercado-pago-customers-api/) — Stored customers and addresses
- [Mercado Pago Merchant Orders API](https://apis.io/apis/mercado-pago/mercado-pago-merchant-orders-api/) — Aggregated preference + payments order resource
- [Mercado Pago Orders API](https://apis.io/apis/mercado-pago/mercado-pago-orders-api/) — Unified Orders API (next-generation checkout)
- [Mercado Pago Payment Methods API](https://apis.io/apis/mercado-pago/mercado-pago-payment-methods-api/) — Discover available payment methods
- [Mercado Pago Payments API](https://apis.io/apis/mercado-pago/mercado-pago-payments-api/) — Create, capture, refund, and search payments
- [Mercado Pago Plans API](https://apis.io/apis/mercado-pago/mercado-pago-plans-api/) — Subscription plans
- [Mercado Pago Point API](https://apis.io/apis/mercado-pago/mercado-pago-point-api/) — In-person POS (stores, terminals)
- [Mercado Pago Preferences API](https://apis.io/apis/mercado-pago/mercado-pago-preferences-api/) — Checkout Pro preferences
- [Mercado Pago QR API](https://apis.io/apis/mercado-pago/mercado-pago-qr-api/) — QR-code in-person collection
- [Mercado Pago Refunds API](https://apis.io/apis/mercado-pago/mercado-pago-refunds-api/) — Refund payments
- [Mercado Pago Reports API](https://apis.io/apis/mercado-pago/mercado-pago-reports-api/) — Settlement and release reports
- [Mercado Pago Subscriptions API](https://apis.io/apis/mercado-pago/mercado-pago-subscriptions-api/) — Recurring preapproval subscriptions

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Mercado Pago Webhooks (IPN / Webhooks v2)](https://apis.io/asyncapis/mercado-pago/mercado-pago-asyncapi/)

#### Event channels (5)

Individual events and webhooks the provider emits.

- [/webhooks/mercadopago](https://apis.io/channels/mercado-pago/mercado-pago-webhooks-ipn-webhooks-v2-webhooks-mercadopago/)
- [/webhooks/mercadopago](https://apis.io/channels/mercado-pago/mercado-pago-webhooks-ipn-webhooks-v2-webhooks-mercadopago-2/)
- [/webhooks/mercadopago](https://apis.io/channels/mercado-pago/mercado-pago-webhooks-ipn-webhooks-v2-webhooks-mercadopago-3/)
- [/webhooks/mercadopago](https://apis.io/channels/mercado-pago/mercado-pago-webhooks-ipn-webhooks-v2-webhooks-mercadopago-4/)
- [/webhooks/mercadopago](https://apis.io/channels/mercado-pago/webhooks-mercadopago/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Mercado Pago Agentic Access](https://apis.io/agentic-access/mercado-pago/mercado-pago-agentic-access/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Mercado Pago Payment](https://apis.io/schemas/mercado-pago/mercado-pago-payment/)
- [Mercado Pago Checkout Preference](https://apis.io/schemas/mercado-pago/mercado-pago-preference/)
- [Mercado Pago Refund](https://apis.io/schemas/mercado-pago/mercado-pago-refund/)
- [Mercado Pago Subscription (Preapproval)](https://apis.io/schemas/mercado-pago/mercado-pago-subscription/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Mercado Pago Payment Structure](https://apis.io/json-structure/mercado-pago/mercado-pago-payment-structure/)
- [Mercado Pago Preference Structure](https://apis.io/json-structure/mercado-pago/mercado-pago-preference-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Mercado Pago Context](https://apis.io/jsonld/mercado-pago/mercado-pago-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Mercado Pago Vocabulary](https://apis.io/vocabularies/mercado-pago/mercado-pago-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Mercado Pago Create Payment Example](https://apis.io/examples/mercado-pago/mercado-pago-create-payment-example/)
- [Mercado Pago Create Preference Example](https://apis.io/examples/mercado-pago/mercado-pago-create-preference-example/)
- [Mercado Pago Create Subscription Example](https://apis.io/examples/mercado-pago/mercado-pago-create-subscription-example/)
- [Mercado Pago Refund Payment Example](https://apis.io/examples/mercado-pago/mercado-pago-refund-payment-example/)
- [Mercado Pago Webhook Payment Example](https://apis.io/examples/mercado-pago/mercado-pago-webhook-payment-example/)

#### Collections (17)

Postman and Open Collection request collections.

- [Mercado Pago REST API](https://apis.io/collections/mercado-pago/open-mercado-pago/)
- [Mercado Pago REST Authentication API](https://apis.io/collections/mercado-pago/open-mercado-pago-authentication-api/)
- [Mercado Pago REST Authentication Cards API](https://apis.io/collections/mercado-pago/open-mercado-pago-cards-api/)
- [Mercado Pago REST Authentication Chargebacks API](https://apis.io/collections/mercado-pago/open-mercado-pago-chargebacks-api/)
- [Mercado Pago REST Authentication Claims API](https://apis.io/collections/mercado-pago/open-mercado-pago-claims-api/)
- [Mercado Pago REST Authentication Customers API](https://apis.io/collections/mercado-pago/open-mercado-pago-customers-api/)
- [Mercado Pago REST Authentication Merchant Orders API](https://apis.io/collections/mercado-pago/open-mercado-pago-merchant-orders-api/)
- [Mercado Pago REST Authentication Orders API](https://apis.io/collections/mercado-pago/open-mercado-pago-orders-api/)
- [Mercado Pago REST Authentication Payment Methods API](https://apis.io/collections/mercado-pago/open-mercado-pago-payment-methods-api/)
- [Mercado Pago REST Authentication Payments API](https://apis.io/collections/mercado-pago/open-mercado-pago-payments-api/)
- [Mercado Pago REST Authentication Plans API](https://apis.io/collections/mercado-pago/open-mercado-pago-plans-api/)
- [Mercado Pago REST Authentication Point API](https://apis.io/collections/mercado-pago/open-mercado-pago-point-api/)
- [Mercado Pago REST Authentication Preferences API](https://apis.io/collections/mercado-pago/open-mercado-pago-preferences-api/)
- [Mercado Pago REST Authentication QR API](https://apis.io/collections/mercado-pago/open-mercado-pago-qr-api/)
- [Mercado Pago REST Authentication Refunds API](https://apis.io/collections/mercado-pago/open-mercado-pago-refunds-api/)
- [Mercado Pago REST Authentication Reports API](https://apis.io/collections/mercado-pago/open-mercado-pago-reports-api/)
- [Mercado Pago REST Authentication Subscriptions API](https://apis.io/collections/mercado-pago/open-mercado-pago-subscriptions-api/)

#### Governance rules (4)

Spectral rulesets for the provider's contracts.

- [Mercado Pago — asyncapi rules](https://apis.io/rules/mercado-pago/mercado-pago-asyncapi-spectral-rules/)
- [Mercado Pago — jsonschema rules](https://apis.io/rules/mercado-pago/mercado-pago-jsonschema-spectral-rules/)
- [Mercado Pago — openapi rules](https://apis.io/rules/mercado-pago/mercado-pago-openapi-spectral-rules/)
- [Mercado Pago API Rules](https://apis.io/rules/mercado-pago/mercado-pago-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Mercado Pago Authentication](https://apis.io/security/mercado-pago/mercado-pago-authentication/)
- [Mercado Pago Domain Security](https://apis.io/security/mercado-pago/mercado-pago-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Mercado Pago Scopes](https://apis.io/scopes/mercado-pago/mercado-pago-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Mercado Pago Plans Pricing](https://apis.io/plans/mercado-pago/mercado-pago-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Mercado Pago Rate Limits](https://apis.io/rate-limits/mercado-pago/mercado-pago-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Mercado Pago Finops](https://apis.io/finops/mercado-pago/mercado-pago-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.mercadopago.com/)
- [Documentation](https://www.mercadopago.com.br/developers/en/docs)
- [Getting started](https://www.mercadopago.com.br/developers/en/docs/your-integrations/credentials)
- [API reference](https://www.mercadopago.com.br/developers/en/reference)
- [Blog](https://www.mercadopago.com.ar/developers/en/news)
- [GitHub](https://github.com/mercadopago)

## API Evangelist rating

**Kin Score 41.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 60.7 |
| Contract quality | 58.0 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 54.8 |
| Access clarity | 5.3 |

**Agent readiness 25.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.1** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/mercado-pago/](https://apis.io/providers/mercado-pago/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Mercado Pago: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/mercado-pago/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
