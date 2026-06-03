# NCR (ncr)

NCR Corporation separated in October 2023 into two independent public companies: NCR Voyix, a global provider of digital commerce solutions for retailers and restaurants, and NCR Atleos, a leader in expanding self-directed banking through ATM networks. NCR Voyix operates the Voyix Commerce Platform, an API-based cloud architecture (the Business Services Platform) that powers unified-commerce POS, ecommerce, and payments for retail and restaurants. Developers access it at developer.ncrvoyix.com using AccessKey (HMAC SHA-512) authentication against api.ncr.com.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/ncr/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Retail, Banking, ATM, Point of Sale, Commerce

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-06-02

## APIs

### NCR Voyix Commerce Platform APIs

REST APIs for the NCR Voyix Commerce Platform (Business Services Platform) covering Catalog (items, item-prices, item-attributes, item-details search), Category and Group management, Selling Service shopping carts, Order creation/lookup/search, Site (location) provisioning and geospatial search, Security (authentication, authorization, passwords, roles), and Provisioning (users and user profiles). Requests are signed with AccessKey (HMAC SHA-512) authentication and scoped with nep-organization and nep-enterprise-unit headers against api.ncr.com (production) / gateway-staging.ncrcloud.com (staging).

**Human URL:** [https://developer.ncrvoyix.com/](https://developer.ncrvoyix.com/)

#### Tags:

 - REST, Commerce, Retail, Restaurant, Catalog, Order, Site, Point of Sale

#### Properties

- [Documentation](https://developer.ncrvoyix.com/)
- [OpenAPI](openapi/ncr-voyix-commerce-platform-openapi.yml)
- [Postman](postman/ncr-bsp-hmac-examples.postman_collection.json)
- [GettingStarted](https://developer.ncrvoyix.com/portals/dev-portal/help-center/topics?topic=All+New+Users+Start+Here)
- [APIExplorer](https://developer.ncrvoyix.com/portals/dev-portal/api-explorer)
- [CodeExamples — Retail Demo App (JavaScript)](https://github.com/NCRVoyix-Corporation/ncr-retail-demo)
- [CodeExamples — Hospitality Sample App (Python)](https://github.com/NCRVoyix-Corporation/sample-app-burgers)
- [CodeExamples — BSP HMAC Authentication Examples](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-catalog.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-category.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-selling.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-order.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-site.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-security.yaml)
- [NaftikoCapability](capabilities/ncr-voyix-commerce-platform-provisioning.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/NCRVoyix-Corporation)
- [LinkedIn](https://www.linkedin.com/company/ncr-corporation)
- [Website](https://www.ncr.com)
- [Website](https://www.ncrvoyix.com/)
- [Website](https://www.ncratleos.com/)
- [DeveloperPortal](https://developer.ncrvoyix.com/)
- [Documentation](https://www.docs.ncr.com/)
- [Authentication — AccessKey (HMAC SHA-512) Authentication](https://github.com/NCRVoyix-Corporation/ncr-bsp-hmac)
- [Rules](rules/ncr-voyix-commerce-platform-spectral-rules.yml)
- [JSONSchema](json-schema/)
- [JSONStructure](json-structure/)
- [JSONLD](json-ld/ncr-voyix-commerce-platform-context.jsonld)
- [Vocabulary](vocabulary/ncr-vocabulary.yml)
- [Plans](plans/ncr-plans-pricing.yml)
- [RateLimits](rate-limits/ncr-rate-limits.yml)
- [FinOps](finops/ncr-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [NCR Voyix Commerce Platform APIs](openapi/ncr-voyix-commerce-platform-openapi.yml) — 43 operations across 7 tags (Catalog, Category, Selling, Order, Site, Security, Provisioning)

### Postman

- [NCR BSP HMAC Examples](postman/ncr-bsp-hmac-examples.postman_collection.json)

### JSON Schema

- 30 schemas in [json-schema/](json-schema/)

### JSON Structure

- 30 structures in [json-structure/](json-structure/)

### JSON-LD

- [NCR Voyix Commerce Platform Context](json-ld/ncr-voyix-commerce-platform-context.jsonld)

### Examples

- 30 example payloads in [examples/](examples/)

## Capabilities

Naftiko capabilities — one self-contained file per Commerce Platform business surface, each exposing a REST adapter and an MCP adapter routed through its own inline consumes block.

| Capability | API | Tools |
|------------|-----|-------|
| [Catalog](capabilities/ncr-voyix-commerce-platform-catalog.yaml) | NCR Voyix Commerce Platform | 11 |
| [Category](capabilities/ncr-voyix-commerce-platform-category.yaml) | NCR Voyix Commerce Platform | 7 |
| [Selling](capabilities/ncr-voyix-commerce-platform-selling.yaml) | NCR Voyix Commerce Platform | 8 |
| [Order](capabilities/ncr-voyix-commerce-platform-order.yaml) | NCR Voyix Commerce Platform | 4 |
| [Site](capabilities/ncr-voyix-commerce-platform-site.yaml) | NCR Voyix Commerce Platform | 6 |
| [Security](capabilities/ncr-voyix-commerce-platform-security.yaml) | NCR Voyix Commerce Platform | 4 |
| [Provisioning](capabilities/ncr-voyix-commerce-platform-provisioning.yaml) | NCR Voyix Commerce Platform | 3 |

## Vocabulary

- [NCR Voyix Vocabulary](vocabulary/ncr-vocabulary.yml) — Unified taxonomy mapping 11 resources, 9 actions, 7 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [NCR Voyix Commerce Platform Spectral Rules](rules/ncr-voyix-commerce-platform-spectral-rules.yml) — 37 rules across 13 categories enforcing NCR Voyix API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
