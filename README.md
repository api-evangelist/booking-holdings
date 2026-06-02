# Booking Holdings (booking-holdings)

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
