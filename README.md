# Qiwi (qiwi)

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

Qiwi provides payment reception, payouts, and banking platform APIs for processing wallet, card, mobile, and SBP transactions across Russia and CIS markets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qiwi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qiwi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Payments
- Wallet
- Payouts
- Fintech
- Banking

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Qiwi Payment Protocol

Protocol for accepting Qiwi payments from wallet, card, and account sources, including payment confirmation, status checks, and reconciliation.

- **Human URL:** [https://developer.qiwi.com/ru/payments/](https://developer.qiwi.com/ru/payments/)

#### Tags

- Payments
- Acceptance

#### Properties

- [Documentation](https://developer.qiwi.com/ru/payments/)
- [OpenAPI](openapi/qiwi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Legal Entity Payouts

API for legal entities to issue payouts to wallets, cards, and bank accounts with batch and individual transfer support.

- **Human URL:** [https://developer.qiwi.com/ru/payout/v2/](https://developer.qiwi.com/ru/payout/v2/)

#### Tags

- Payouts
- B2B

#### Properties

- [Documentation](https://developer.qiwi.com/ru/payout/v2/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Wallet Payouts

API for sending payouts directly to Qiwi wallets.

- **Human URL:** [https://developer.qiwi.com/ru/topup-wallet/](https://developer.qiwi.com/ru/topup-wallet/)

#### Tags

- Payouts
- Wallet

#### Properties

- [Documentation](https://developer.qiwi.com/ru/topup-wallet/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Card Wallet SBP Payouts

API for issuing payouts to bank cards, wallets, and SBP (Faster Payments System) recipients.

- **Human URL:** [https://developer.qiwi.com/ru/topup-card/](https://developer.qiwi.com/ru/topup-card/)

#### Tags

- Payouts
- Cards
- SBP

#### Properties

- [Documentation](https://developer.qiwi.com/ru/topup-card/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Mobile Topups

API for topping up mobile phone balances across telecom operators.

- **Human URL:** [https://developer.qiwi.com/ru/topup-mobile/](https://developer.qiwi.com/ru/topup-mobile/)

#### Tags

- Payouts
- Mobile

#### Properties

- [Documentation](https://developer.qiwi.com/ru/topup-mobile/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Banking Platform

Banking-as-a-Service platform for issuing accounts, cards, and banking operations on top of Qiwi infrastructure.

- **Human URL:** [https://developer.qiwi.com/baas/](https://developer.qiwi.com/baas/)

#### Tags

- Banking
- BaaS

#### Properties

- [Documentation](https://developer.qiwi.com/baas/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Client Identification Service

API for client identification and KYC verification workflows.

- **Human URL:** [https://developer.qiwi.com/ru/identification-service/](https://developer.qiwi.com/ru/identification-service/)

#### Tags

- KYC
- Identification

#### Properties

- [Documentation](https://developer.qiwi.com/ru/identification-service/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Terminal Map

API to retrieve Qiwi terminal locations and their service capabilities.

- **Human URL:** [https://developer.qiwi.com/ru/qiwi-map/](https://developer.qiwi.com/ru/qiwi-map/)

#### Tags

- Terminals
- Locations

#### Properties

- [Documentation](https://developer.qiwi.com/ru/qiwi-map/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi Wallet Personal

Personal Qiwi Wallet API for managing balance, transfers, payments, and transaction history for end users.

- **Human URL:** [https://developer.qiwi.com/ru/qiwi-wallet-personal/](https://developer.qiwi.com/ru/qiwi-wallet-personal/)

#### Tags

- Wallet
- Personal

#### Properties

- [Documentation](https://developer.qiwi.com/ru/qiwi-wallet-personal/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qiwi P2P Payments

Peer-to-peer payment API for accepting payments from individuals via payment forms and invoices.

- **Human URL:** [https://developer.qiwi.com/ru/p2p-payments/](https://developer.qiwi.com/ru/p2p-payments/)

#### Tags

- Payments
- P2P

#### Properties

- [Documentation](https://developer.qiwi.com/ru/p2p-payments/)
- [Postman Collection](collections/qiwi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qiwi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qiwi)
- [Portal](https://developer.qiwi.com)
- [GitHub Organization](https://github.com/QIWI-API)
- [Website](https://qiwi.com)
- [Support](https://qiwi.com/support)
- [Terms of Service](https://qiwi.com/legal)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
