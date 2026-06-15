# NCR (ncr)

NCR Corporation separated in October 2023 into two independent public companies: NCR Voyix, a global provider of digital commerce solutions for retailers and restaurants, and NCR Atleos, a leader in expanding self-directed banking through ATM networks. NCR Voyix operates the Voyix Commerce Platform, an API-based cloud architecture (the Business Services Platform) that powers unified-commerce POS, ecommerce, and payments for retail and restaurants. Developers access it at developer.ncrvoyix.com using AccessKey (HMAC SHA-512) authentication against api.ncr.com.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ncr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ncr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Restaurant
- Retail
- Banking
- ATM
- Point of Sale
- Commerce

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-06-02

## APIs

### NCR Voyix Commerce Platform APIs

REST APIs for the NCR Voyix Commerce Platform (Business Services Platform) covering Catalog (items, item-prices, item-attributes, item-details search), Category and Group management, Selling Service shopping carts, Order creation/lookup/search, Site (location) provisioning and geospatial search, Security (authentication, authorization, passwords, roles), and Provisioning (users and user profiles). Requests are signed with AccessKey (HMAC SHA-512) authentication and scoped with nep-organization and nep-enterprise-unit headers against api.ncr.com (production) / gateway-staging.ncrcloud.com (staging).

- **Human URL:** [https://developer.ncrvoyix.com/](https://developer.ncrvoyix.com/)
- **Base URL:** `https://api.ncr.com`

#### Tags

- REST
- Commerce
- Retail
- Restaurant
- Catalog
- Order
- Site
- Point of Sale

#### Properties

- [Documentation](https://developer.ncrvoyix.com/)
- [OpenAPI](openapi/ncr-voyix-commerce-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ncr-voyix-commerce-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ncr-voyix-commerce-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman](postman/ncr-bsp-hmac-examples.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Getting Started](https://developer.ncrvoyix.com/portals/dev-portal/help-center/topics?topic=All+New+Users+Start+Here)
- [A P I Explorer](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer)
- [Code Examples](https://github.com/NCRVoyix-Corporation/ncr-retail-demo)
- [Code Examples](https://github.com/NCRVoyix-Corporation/sample-app-burgers)
- [Code Examples](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)

## Common Properties

- [GitHub Organization](https://github.com/NCRVoyix-Corporation)
- [LinkedIn](https://www.linkedin.com/company/ncr-corporation)
- [Website](https://www.ncr.com)
- [Website](https://www.ncrvoyix.com/)
- [Website](https://www.ncratleos.com/)
- [Developer Portal](https://developer.ncrvoyix.com/)
- [Documentation](https://www.docs.ncr.com/)
- [Authentication](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [Rules](rules/ncr-voyix-commerce-platform-spectral-rules.yml)
- [JSON Schema](json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/)
- [JSON-LD](json-ld/ncr-voyix-commerce-platform-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/ncr-vocabulary.yml)
- [Plans](plans/ncr-plans-pricing.yml)
- [Rate Limits](rate-limits/ncr-rate-limits.yml)
- [Fin Ops](finops/ncr-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
