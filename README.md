# Booking Holdings (booking-holdings)

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

Booking Holdings is the world's leading provider of online travel and related services, operating a portfolio of brands including Booking.com, Priceline, Agoda, KAYAK, OpenTable, Rentalcars.com, Rocketmiles, FareHarbor, HotelsCombined, Cheapflights, and Momondo. The company connects travelers with accommodations, flights, rental cars, restaurant reservations, and travel experiences worldwide.

**URL:** [https://raw.githubusercontent.com/api-evangelist/booking-holdings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/booking-holdings/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Accommodations, Airlines, Car Rentals, Hospitality, Hotels, Restaurants, Travel

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-06-02

## APIs

### Booking.com Demand API

The Booking.com Demand API enables approved Affiliate Partners to access Booking.com's travel inventory — accommodations, car rentals, and flights. A RESTful, RPC-style API (HTTPS POST, JSON) for searching inventory, retrieving details, checking availability, managing orders, and exchanging partner-guest messages. This is Booking Holdings' primary publicly documented developer API; restaurant inventory (OpenTable) and other brand APIs are partner-gated and not included here.

**Human URL:** [https://developers.booking.com/demand/docs](https://developers.booking.com/demand/docs)

**Base URL:** `https://demandapi.booking.com/3.1`

#### Tags:

 - Accommodations, Car Rentals, Travel, Orders, Affiliate

#### Properties

- [OpenAPI](openapi/booking-com-demand-api.yaml)
- [Documentation](https://developers.booking.com/demand/docs)
- [Authentication](https://developers.booking.com/demand/docs/getting-started)
- [Naftiko Capability — Accommodations](capabilities/demand-api-accommodations.yaml)
- [Naftiko Capability — Cars](capabilities/demand-api-cars.yaml)
- [Naftiko Capability — Orders](capabilities/demand-api-orders.yaml)
- [Naftiko Capability — Messages](capabilities/demand-api-messages.yaml)
- [Naftiko Capability — Conversations](capabilities/demand-api-conversations.yaml)
- [Naftiko Capability — Attachments](capabilities/demand-api-attachments.yaml)
- [Naftiko Capability — Locations](capabilities/demand-api-common-locations.yaml)
- [Naftiko Capability — Payments](capabilities/demand-api-common-payments.yaml)
- [Naftiko Capability — Languages](capabilities/demand-api-common-languages.yaml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/bookingholdings)
- [Website](https://www.bookingholdings.com)
- [About](https://www.bookingholdings.com/about/)
- [InvestorRelations](https://ir.bookingholdings.com)
- [Careers](https://www.bookingholdings.com/careers/)
- [Contact](https://www.bookingholdings.com/contact/)
- [Plans](plans/booking-holdings-plans-pricing.yml)
- [RateLimits](rate-limits/booking-holdings-rate-limits.yml)
- [FinOps](finops/booking-holdings-finops.yml)
- [Rules](rules/booking-com-demand-api-spectral-rules.yml)
- [Vocabulary](vocabulary/booking-holdings-vocabulary.yaml)
- [JSON-LD](json-ld/booking-holdings-demand-api-context.jsonld)
- [GitHub Organization — Booking.com](https://github.com/bookingcom)
- [GitHub Organization — OpenTable](https://github.com/opentable)
- [GitHub Organization — KAYAK](https://github.com/kayak)

## Brand Portfolio

- **[Booking.com](https://www.booking.com)** — World's leading accommodation booking platform (Demand API, Connectivity API, Affiliate Program)
- **[Priceline](https://www.priceline.com)** — Hotels, flights, and car rentals with Express Deals
- **[Agoda](https://www.agoda.com)** — Asia-Pacific focused accommodation platform
- **[KAYAK](https://www.kayak.com)** — Travel search and comparison engine
- **[OpenTable](https://www.opentable.com)** — Restaurant reservations and guest management (partner-gated platform API)
- **[Rentalcars.com](https://www.rentalcars.com)** — Global car rental search
- **[FareHarbor](https://fareharbor.com)** — Tours, activities, and experience booking (partner API)
- **[Momondo](https://www.momondo.com)** — Flight and hotel price comparison
- **[Cheapflights](https://www.cheapflights.com)** — Cheap flight search
- **[Rocketmiles](https://www.rocketmiles.com)** — Hotel bookings earning loyalty miles
- **[HotelsCombined](https://www.hotelscombined.com)** — Hotel price aggregation

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Booking.com Demand API](openapi/booking-com-demand-api.yaml) — 39 operations across 9 resource groups (OpenAPI 3.1)

### JSON Schema

25 schemas extracted from the Demand API in [json-schema/](json-schema/) — accommodations, orders, locations, flights, and reference-data entities.

### JSON Structure

25 [json-structure/](json-structure/) representations converted from the JSON Schemas.

### Examples

25 example payloads in [examples/](examples/), one per JSON Schema.

## Capabilities

Naftiko capabilities, one self-contained file per Demand API business surface (each with REST and MCP exposers).

| Workflow | API | Operations | Persona |
|----------|-----|-----------|---------|
| [Accommodations](capabilities/demand-api-accommodations.yaml) | Demand API | 9 | Affiliate Partner |
| [Cars](capabilities/demand-api-cars.yaml) | Demand API | 6 | Affiliate Partner |
| [Orders](capabilities/demand-api-orders.yaml) | Demand API | 8 | Affiliate Partner |
| [Messages](capabilities/demand-api-messages.yaml) | Demand API | 3 | Affiliate Partner |
| [Conversations](capabilities/demand-api-conversations.yaml) | Demand API | 1 | Affiliate Partner |
| [Attachments](capabilities/demand-api-attachments.yaml) | Demand API | 3 | Affiliate Partner |
| [Locations](capabilities/demand-api-common-locations.yaml) | Demand API | 6 | Affiliate Partner |
| [Payments](capabilities/demand-api-common-payments.yaml) | Demand API | 2 | Affiliate Partner |
| [Languages](capabilities/demand-api-common-languages.yaml) | Demand API | 1 | Affiliate Partner |

## Vocabulary

- [Booking Holdings Vocabulary](vocabulary/booking-holdings-vocabulary.yaml) — Unified taxonomy mapping 9 resources, 30 actions, 9 workflows, and 1 persona across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Booking.com Demand API Spectral Rules](rules/booking-com-demand-api-spectral-rules.yml) — 30 rules across info, paths, operations, parameters, responses, schemas, and security enforcing Booking.com Demand API conventions

## Plans & FinOps

- [Plans / Pricing](plans/booking-holdings-plans-pricing.yml) — Demand API is free to approved affiliates; revenue is an affiliate commission share
- [Rate Limits](rate-limits/booking-holdings-rate-limits.yml) — Per-account RPM limits (sandbox 50 RPM, cars/search 3000 RPM, production partner-specific)
- [FinOps](finops/booking-holdings-finops.yml) — FOCUS-aligned commission-tracking model

## Developer Resources

- Booking.com: [developers.booking.com](https://developers.booking.com/)
- OpenTable: [platform.opentable.com](https://platform.opentable.com/) (partner-gated)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
