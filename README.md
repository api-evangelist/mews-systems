# Mews (mews-systems)

Mews is a cloud-native hospitality cloud and property management system (PMS) headquartered in Prague, Czech Republic that powers reservations, operations, payments, point of sale, revenue management, and distribution for more than 15,000 hospitality properties globally. The Mews Open API surface is organised into five product APIs — the general-purpose Connector API for partners working with Mews Operations data, the Channel Manager API for two-way distribution with OTAs and channel managers, the Booking Engine API for guest-facing reservation creation, the POS API for point-of-sale integrations, and the Loyalty Partner reverse API for membership systems. Mews also runs a marketplace of more than 1,000 hospitality integrations.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mews-systems/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mews-systems/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Hospitality
- Hotel
- Property Management
- PMS
- Reservations
- Bookings
- Travel
- Payments
- Point of Sale
- Channel Manager
- Booking Engine

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-06-02

## APIs

### Mews Connector API

The Mews Connector API is the general-purpose Open API for Mews Operations. Partners use it to access enterprise configuration, reservations, customers, bills, payments, accounts, rates, products, restrictions, services, resources, and tasks across single properties or whole portfolios. Authentication uses a triple of Client (a free-form name for the calling application), ClientToken (issued by Mews to identify the partner application) and AccessToken (issued by the property to authorise the application against the enterprise). All operations are POST-based, return UTC timestamps, support pagination on multi-property lookups, and emit webhook-style events for near real-time integration. Use cases include kiosks, in-room tech, upsell engines, business intelligence, accounting reconciliation, and custom operational tooling.

- **Human URL:** [https://docs.mews.com/connector-api](https://docs.mews.com/connector-api)
- **Base URL:** `https://api.mews.com/api/connector/v1`

#### Tags

- Reservations
- Customers
- Bills
- Payments
- Rates
- Accounts
- Operations
- Hospitality

#### Properties

- [Documentation](https://docs.mews.com/connector-api)
- [Getting Started](https://docs.mews.com/connector-api/getting-started)
- [API Reference](https://docs.mews.com/connector-api/operations)
- [OpenAPI](https://api.mews.com/Swagger/connector/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/mews-connector-api-reservations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-reservations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-reservations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-customers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-customers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-customers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-billing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-resources-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-resources.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-resources.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-pos-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-pos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-pos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-operations-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-operations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-operations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/mews-connector-api-configuration-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-connector-api-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.mews.com/connector-api/guidelines)
- [Webhooks](https://docs.mews.com/connector-api/events)
- [Changelog](https://docs.mews.com/connector-api/changelog)
- [Documentation](https://docs.mews.com/connector-api/deprecations)
- [Support](https://docs.mews.com/connector-api/contact-support)

### Mews Channel Manager API

The Mews Channel Manager API is the two-way distribution surface between Mews and channel managers, online travel agents (OTAs), and other bulk sales channels. Mews pushes availability, rates, and inventory updates outbound to the channel manager, while the channel manager pushes new and modified reservations back into Mews. The API defines both Mews-side endpoints (consumed by the channel manager) and Channel Manager-side endpoints (consumed by Mews) so that pricing, restrictions, stop-sells, and reservation lifecycle stay in sync across all connected demand channels.

- **Human URL:** [https://docs.mews.com/channel-manager-api](https://docs.mews.com/channel-manager-api)
- **Base URL:** `https://api.mews.com/api/channelManager/v1`

#### Tags

- Channel Manager
- Distribution
- OTA
- Availability
- Rates
- Inventory
- Reservations

#### Properties

- [Documentation](https://docs.mews.com/channel-manager-api)
- [Documentation](https://docs.mews.com/channel-manager-api/guidelines)
- [API Reference](https://docs.mews.com/channel-manager-api/operations)
- [Changelog](https://docs.mews.com/channel-manager-api/changelog)
- [Documentation](https://docs.mews.com/channel-manager-api/deprecations)
- [Postman Collection](collections/mews-booking-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-booking-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-customers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-customers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-operations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-operations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-pos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-pos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-reservations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-reservations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-resources.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-resources.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mews Booking Engine API

The Mews Booking Engine API (historically published as the Distributor API and still served from the /api/distributor/v1 path) lets developers build custom guest-facing booking engines that create reservations directly in Mews. It is designed for front-end client consumption rather than server-to-server use, exposes enterprise configuration, availability, rate plans, products, vouchers and reservation creation, and is the foundation behind Mews-built and partner-built booking flows including widgets, kiosks, and direct-booking websites.

- **Human URL:** [https://docs.mews.com/booking-engine-guide](https://docs.mews.com/booking-engine-guide)
- **Base URL:** `https://api.mews.com/api/distributor/v1`

#### Tags

- Booking Engine
- Reservations
- Distribution
- Direct Booking
- Guest

#### Properties

- [Documentation](https://docs.mews.com/booking-engine-guide)
- [Documentation](https://docs.mews.com/booking-engine-guide/guidelines)
- [API Reference](https://docs.mews.com/booking-engine-guide/operations)
- [OpenAPI](https://api.mews.com/Swagger/distributor/swagger.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/mews-booking-engine-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mews-booking-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-booking-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Changelog](https://docs.mews.com/booking-engine-guide/changelog)

### Mews POS API

The Mews POS API gives partner point-of-sale systems real-time access to Mews POS data and services so that food and beverage, retail, and ancillary outlets can post charges to guest folios, share menus and product catalogues, manage table state, and reconcile orders with the property management system. Typical integrators include restaurant POS vendors, table-booking apps, inventory and stock-management systems, and F&B business-intelligence tools.

- **Human URL:** [https://docs.mews.com/pos-api](https://docs.mews.com/pos-api)
- **Base URL:** `https://api.mews.com/api/pos/v1`

#### Tags

- POS
- Point of Sale
- Orders
- Restaurant
- Bills
- Hospitality

#### Properties

- [Documentation](https://docs.mews.com/pos-api)
- [Documentation](https://docs.mews.com/pos-api/guidelines)
- [API Reference](https://docs.mews.com/pos-api/operations)
- [Changelog](https://docs.mews.com/pos-api/changelog)
- [Postman Collection](collections/mews-booking-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-booking-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-customers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-customers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-operations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-operations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-pos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-pos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-reservations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-reservations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-resources.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-resources.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mews Loyalty Partner API

The Mews Loyalty Partner API is a reverse API — Mews calls endpoints that the loyalty provider hosts — used to integrate third-party loyalty and membership programs with Mews Operations. Loyalty partners implement the contract so that member lookup, enrollment, point accrual, and point redemption can happen automatically in the Mews reservation, check-in, and billing flow.

- **Human URL:** [https://docs.mews.com/loyalty-partner-api](https://docs.mews.com/loyalty-partner-api)
- **Base URL:** `https://partner.example.com`

#### Tags

- Loyalty
- Membership
- Reverse API
- Hospitality

#### Properties

- [Documentation](https://docs.mews.com/loyalty-partner-api)
- [Postman Collection](collections/mews-booking-engine-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-booking-engine-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-configuration.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-configuration.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-customers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-customers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-operations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-operations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-pos.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-pos.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-reservations.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-reservations.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-resources.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-resources.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mews-connector-api-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mews-connector-api-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.mews.com/)
- [Portal](https://developers.mews.com/)
- [Documentation](https://docs.mews.com/)
- [Getting Started](https://docs.mews.com/getting-started/the-mews-apis)
- [API Reference](https://docs.mews.com/connector-api/operations)
- [Authentication](https://docs.mews.com/connector-api/guidelines)
- [GitHub Organization](https://github.com/MewsSystems)
- [GitHub Repository](https://github.com/MewsSystems/open-api-docs)
- [GitHub Repository](https://github.com/MewsSystems/fiscalizations)
- [GitHub Repository](https://github.com/MewsSystems/mews-flutter)
- [GitHub Repository](https://github.com/MewsSystems/developers)
- [Blog](https://developers.mews.com/)
- [Blog](https://www.mews.com/en/blog)
- [Status Page](https://status.mews.com/)
- [Sign Up](https://www.mews.com/en/partners/new-partnerships)
- [Pricing](https://www.mews.com/en/pricing)
- [Terms of Service](https://www.mews.com/en/legal)
- [Privacy Policy](https://www.mews.com/en/legal/privacy-policy)
- [Support](https://help.mews.com/)
- [Support](mailto:partnersuccess@mews.com)
- [About](https://www.mews.com/en/about-us)
- [Careers](https://www.mews.com/en/careers)
- [Marketplace](https://www.mews.com/en/marketplace)
- [LinkedIn](https://www.linkedin.com/company/mews-systems)
- [SDK](https://github.com/MewsSystems/mews-flutter)
- [SDK](https://github.com/MewsSystems/fiscalizations)
- [SDK](https://github.com/MewsSystems/FuncSharp)
- [Tools](https://github.com/MewsSystems/awesome-mews)
- [Code Examples](https://github.com/MewsSystems/open-api-docs)
- [Rules](rules/mews-systems-spectral-rules.yml)
- [Vocabulary](vocabulary/mews-systems-vocabulary.yml)
- [Plans](plans/mews-systems-plans-pricing.yml)
- [Rate Limits](rate-limits/mews-systems-rate-limits.yml)
- [Fin Ops](finops/mews-systems-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
