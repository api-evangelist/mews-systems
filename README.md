# Mews (mews-systems)
Mews is a cloud-native hospitality cloud and property management system (PMS) headquartered in Prague, Czech Republic that powers reservations, operations, payments, point of sale, revenue management, and distribution for more than 15,000 hospitality properties globally. The Mews Open API surface is organised into five product APIs — the general-purpose Connector API for partners working with Mews Operations data, the Channel Manager API for two-way distribution with OTAs and channel managers, the Booking Engine API for guest-facing reservation creation, the POS API for point-of-sale integrations, and the Loyalty Partner reverse API for membership systems. Mews also runs a marketplace of more than 1,000 hospitality integrations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mews-systems/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Hospitality, Hotel, Property Management, PMS, Reservations, Bookings, Travel, Payments, Point of Sale, Channel Manager, Booking Engine

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Mews Connector API
The Mews Connector API is the general-purpose Open API for Mews Operations. Partners use it to access enterprise configuration, reservations, customers, bills, payments, accounts, rates, products, restrictions, services, resources, and tasks across single properties or whole portfolios. Authentication uses a triple of Client (a free-form name for the calling application), ClientToken (issued by Mews to identify the partner application) and AccessToken (issued by the property to authorise the application against the enterprise). All operations are POST-based, return UTC timestamps, support pagination on multi-property lookups, and emit webhook-style events for near real-time integration. Use cases include kiosks, in-room tech, upsell engines, business intelligence, accounting reconciliation, and custom operational tooling.

**Human URL:** [https://docs.mews.com/connector-api](https://docs.mews.com/connector-api)

**Base URL:** `https://api.mews.com/api/connector/v1`

#### Tags:

 - Reservations, Customers, Bills, Payments, Rates, Accounts, Operations, Hospitality

#### Properties

- [Documentation](https://docs.mews.com/connector-api)
- [GettingStarted](https://docs.mews.com/connector-api/getting-started)
- [APIReference](https://docs.mews.com/connector-api/operations)
- [OpenAPI](https://api.mews.com/Swagger/connector/swagger.yaml)
- [Documentation](https://docs.mews.com/connector-api/guidelines)
- [Webhooks](https://docs.mews.com/connector-api/events)
- [ChangeLog](https://docs.mews.com/connector-api/changelog)
- [Documentation](https://docs.mews.com/connector-api/deprecations)
- [Support](https://docs.mews.com/connector-api/contact-support)

### Mews Channel Manager API
The Mews Channel Manager API is the two-way distribution surface between Mews and channel managers, online travel agents (OTAs), and other bulk sales channels. Mews pushes availability, rates, and inventory updates outbound to the channel manager, while the channel manager pushes new and modified reservations back into Mews. The API defines both Mews-side endpoints (consumed by the channel manager) and Channel Manager-side endpoints (consumed by Mews) so that pricing, restrictions, stop-sells, and reservation lifecycle stay in sync across all connected demand channels.

**Human URL:** [https://docs.mews.com/channel-manager-api](https://docs.mews.com/channel-manager-api)

**Base URL:** `https://api.mews.com/api/channelManager/v1`

#### Tags:

 - Channel Manager, Distribution, OTA, Availability, Rates, Inventory, Reservations

#### Properties

- [Documentation](https://docs.mews.com/channel-manager-api)
- [Documentation](https://docs.mews.com/channel-manager-api/guidelines)
- [APIReference](https://docs.mews.com/channel-manager-api/operations)
- [ChangeLog](https://docs.mews.com/channel-manager-api/changelog)
- [Documentation](https://docs.mews.com/channel-manager-api/deprecations)

### Mews Booking Engine API
The Mews Booking Engine API (historically published as the Distributor API and still served from the /api/distributor/v1 path) lets developers build custom guest-facing booking engines that create reservations directly in Mews. It is designed for front-end client consumption rather than server-to-server use, exposes enterprise configuration, availability, rate plans, products, vouchers and reservation creation, and is the foundation behind Mews-built and partner-built booking flows including widgets, kiosks, and direct-booking websites.

**Human URL:** [https://docs.mews.com/booking-engine-guide](https://docs.mews.com/booking-engine-guide)

**Base URL:** `https://api.mews.com/api/distributor/v1`

#### Tags:

 - Booking Engine, Reservations, Distribution, Direct Booking, Guest

#### Properties

- [Documentation](https://docs.mews.com/booking-engine-guide)
- [Documentation](https://docs.mews.com/booking-engine-guide/guidelines)
- [APIReference](https://docs.mews.com/booking-engine-guide/operations)
- [ChangeLog](https://docs.mews.com/booking-engine-guide/changelog)

### Mews POS API
The Mews POS API gives partner point-of-sale systems real-time access to Mews POS data and services so that food and beverage, retail, and ancillary outlets can post charges to guest folios, share menus and product catalogues, manage table state, and reconcile orders with the property management system. Typical integrators include restaurant POS vendors, table-booking apps, inventory and stock-management systems, and F&B business-intelligence tools.

**Human URL:** [https://docs.mews.com/pos-api](https://docs.mews.com/pos-api)

**Base URL:** `https://api.mews.com/api/pos/v1`

#### Tags:

 - POS, Point of Sale, Orders, Restaurant, Bills, Hospitality

#### Properties

- [Documentation](https://docs.mews.com/pos-api)
- [Documentation](https://docs.mews.com/pos-api/guidelines)
- [APIReference](https://docs.mews.com/pos-api/operations)
- [ChangeLog](https://docs.mews.com/pos-api/changelog)

### Mews Loyalty Partner API
The Mews Loyalty Partner API is a reverse API — Mews calls endpoints that the loyalty provider hosts — used to integrate third-party loyalty and membership programs with Mews Operations. Loyalty partners implement the contract so that member lookup, enrollment, point accrual, and point redemption can happen automatically in the Mews reservation, check-in, and billing flow.

**Human URL:** [https://docs.mews.com/loyalty-partner-api](https://docs.mews.com/loyalty-partner-api)

#### Tags:

 - Loyalty, Membership, Reverse API, Hospitality

#### Properties

- [Documentation](https://docs.mews.com/loyalty-partner-api)

## Common Properties

- [Website](https://www.mews.com/)
- [Portal](https://developers.mews.com/)
- [Documentation](https://docs.mews.com/)
- [GettingStarted](https://docs.mews.com/getting-started/the-mews-apis)
- [APIReference](https://docs.mews.com/connector-api/operations)
- [Authentication](https://docs.mews.com/connector-api/guidelines)
- [GitHubOrganization](https://github.com/MewsSystems)
- [GitHubRepository](https://github.com/MewsSystems/open-api-docs) — Mews Open API documentation source
- [GitHubRepository](https://github.com/MewsSystems/fiscalizations) — .NET fiscalization library for government e-invoice reporting
- [GitHubRepository](https://github.com/MewsSystems/mews-flutter) — Flutter and Dart open-source packages maintained by Mews
- [GitHubRepository](https://github.com/MewsSystems/developers) — Mews engineering blog and developer microsite source
- [Blog](https://developers.mews.com/) — Mews Engineering and R&D Blog
- [Blog](https://www.mews.com/en/blog) — Mews Hospitality Blog
- [StatusPage](https://status.mews.com/)
- [SignUp](https://www.mews.com/en/partners/new-partnerships) — Become a Mews Partner
- [Pricing](https://www.mews.com/en/pricing)
- [TermsOfService](https://www.mews.com/en/legal)
- [PrivacyPolicy](https://www.mews.com/en/legal/privacy-policy)
- [Support](https://help.mews.com/)
- [Support](mailto:partnersuccess@mews.com) — Partner Success email
- [About](https://www.mews.com/en/about-us)
- [Careers](https://www.mews.com/en/careers)
- [Marketplace](https://www.mews.com/en/marketplace) — Mews Marketplace - 1,000+ hospitality integrations
- [LinkedIn](https://www.linkedin.com/company/mews-systems)

## Features

| Name | Description |
|------|-------------|
| Cloud-Native Property Management System | Reservation management, group bookings, guest check-in/out, housekeeping, billing, and accounting in a single hosted PMS |
| Point of Sale (POS) | Embedded POS for hotel restaurants, bars, and ancillary outlets with charge posting to guest folios |
| Revenue Management System (RMS) | Dynamic pricing, demand forecasting, and portfolio/group pricing with AI assistance |
| Integrated Payments | Tokenization, multicurrency, automated reconciliation, and certified payment terminals |
| Open API Surface | Five product APIs — Connector, Channel Manager, Booking Engine, POS, and Loyalty Partner — for partners and custom integrations |
| Webhook Events | Connector API events feed for near real-time integration with reservation, customer, and billing state changes |
| Portfolio Access Tokens | Single-token access across multiple properties for chain and enterprise integrations |
| Mews Marketplace | 1,000+ certified hospitality integrations spanning channel managers, OTAs, POS, payments, guest experience, BI, and operations |
| Booking Engine | Direct-booking widgets and websites powered by the Booking Engine API |
| Business Intelligence and Analytics | Reporting, KPI dashboards, and data exports for revenue, operations, and guest data |
| Security and Compliance | SOC 2, ISO, and PCI DSS certified hosting and processing |
| Multi-Property and Multi-Brand Support | Single Mews account spans many properties, brands, and legal entities under chain or enterprise structures |

## Use Cases

| Name | Description |
|------|-------------|
| Kiosk and Self Check-In | Build self-service kiosks and mobile check-in flows on top of the Connector API |
| Custom Booking Engine | Power direct-booking widgets and white-label websites with the Booking Engine API |
| OTA and Channel Manager Distribution | Two-way sync of availability, rates, inventory, and reservations between Mews and OTAs via the Channel Manager API |
| Point of Sale Integration | Post charges from restaurant, retail, spa, and activity POS to guest folios via the POS API |
| Loyalty Program Integration | Plug a loyalty or membership program into the Mews reservation and folio lifecycle via the Loyalty Partner API |
| Business Intelligence and Reporting | Pull reservation, revenue, and operations data into BI tools and data warehouses |
| Accounting and Finance Automation | Reconcile bills, payments, and accounting categories with general-ledger and ERP systems |
| Guest Experience and Upsell | Deliver pre-arrival upsell, in-stay messaging, and guest-app experiences using Connector API data and events |
| Operations and Housekeeping | Drive housekeeping, maintenance, and task workflows with real-time room and reservation state |
| Fiscalization and Tax Reporting | Report e-invoices to government tax authorities using the open-source Mews Fiscalizations .NET library |

## Integrations

| Name | Description |
|------|-------------|
| Online Travel Agents | Booking.com, Expedia, Airbnb, and other OTAs via certified channel managers using the Channel Manager API |
| Channel Managers | SiteMinder, Cloudbeds, RateGain, D-EDGE and other channel managers via the Channel Manager API |
| Payment Processors | Mews Payments plus integrations with Adyen, Stripe, and regional acquirers |
| Point of Sale Systems | Mews POS plus third-party POS vendors integrated via the POS API |
| Business Intelligence | Connector API feeds into Power BI, Tableau, Looker, and hospitality BI tools like HotelIQ and Demand Calendar |
| Guest Experience Apps | Mobile check-in, messaging, upsell, and concierge apps built on the Connector API |
| Revenue Management | Mews RMS plus third-party RMS vendors like Duetto, IDeaS, and Atomize integrated via the Connector API |
| Accounting and ERP | General-ledger and ERP integrations including Xero, QuickBooks, NetSuite, and SAP via the Connector API |
| Door Locks and IoT | Smart-lock and in-room device vendors integrated through the Connector API |
| Fiscalization Authorities | Government e-invoice and fiscal reporting via the open-source Mews Fiscalizations .NET library |

## Solutions

| Name | Description |
|------|-------------|
| Independent Hotels | PMS, POS, payments, and booking engine for single-property independent hotels |
| Hotel Chains and Enterprise | Multi-property, multi-brand operations with portfolio access tokens and central reporting |
| Hostels | Bed-level inventory, group bookings, and self-service flows for hostels |
| Serviced Apartments and Extended Stay | Long-stay billing, recurring charges, and apartment-style inventory |
| Motels and Limited Service | Streamlined operations and self-service check-in for limited-service properties |

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
