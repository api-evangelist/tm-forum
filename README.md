# TM Forum (tm-forum)

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

TM Forum is a global industry association that helps communications service providers (CSPs) and technology suppliers to digitally transform and thrive in the digital economy. Through collaboration across 850+ member organizations in 180 countries, TM Forum develops the Open API suite — a portfolio of 88+ standardized REST APIs (Apache 2.0 licensed) covering the full telecommunications business support systems (BSS) and operations support systems (OSS) landscape, including product catalog, ordering, customer management, inventory, billing, network resources, and partner management. The Open APIs implement consistent REST/JSON patterns aligned to the TM Forum Information Framework (SID) and enable interoperability across telecom ecosystems.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tm-forum/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Telco
- Telecommunications
- BSS
- OSS
- Open APIs
- Standards

## Timestamps

- **Created:** 2024-11-27
- **Modified:** 2026-05-19

## APIs

### TMF620 Product Catalog Management

The Product Catalog Management API provides a consistent set of mechanisms to manage product offerings, product specifications, and product catalog entries across telecom BSS systems. Covers catalog creation, product offering management, pricing, and lifecycle management.

- **Human URL:** [https://www.tmforum.org/resources/specification/tmf620-product-catalog-management-api-rest-specification-r17-5-0/](https://www.tmforum.org/resources/specification/tmf620-product-catalog-management-api-rest-specification-r17-5-0/)

#### Tags

- Product Catalog
- BSS

#### Properties

- [Documentation](https://www.tmforum.org/resources/specification/tmf620-product-catalog-management-api-rest-specification-r17-5-0/)
- [OpenAPI](openapi/tm-forum-tmf620-product-catalog-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF621 Trouble Ticket Management

The Trouble Ticket API provides standardized access to telecom trouble ticket management functions including incident creation, tracking, routing, and resolution across network and customer-facing support systems.

- **Human URL:** [https://github.com/tmforum-apis/TMF621_TroubleTicket](https://github.com/tmforum-apis/TMF621_TroubleTicket)

#### Tags

- Trouble Ticket
- OSS
- Incident Management

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF621_TroubleTicket)
- [OpenAPI](openapi/tm-forum-tmf621-trouble-ticket-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF622 Product Order Management

The Product Ordering Management API provides a standardized interface for managing product orders across telecom BSS systems, covering order creation, tracking, amendment, and cancellation for telecommunications products and services.

- **Human URL:** [https://github.com/tmforum-apis/TMF622_ProductOrder](https://github.com/tmforum-apis/TMF622_ProductOrder)

#### Tags

- Product Ordering
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF622_ProductOrder)
- [OpenAPI](openapi/tm-forum-tmf622-product-ordering-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF629 Customer Management

The Customer Management API provides a consistent interface for managing customer accounts, customer hierarchy, and customer engagement across telecom BSS systems, supporting B2C and B2B customer lifecycle operations.

- **Human URL:** [https://github.com/tmforum-apis/TMF629_CustomerManagement](https://github.com/tmforum-apis/TMF629_CustomerManagement)

#### Tags

- Customer Management
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF629_CustomerManagement)
- [OpenAPI](openapi/tm-forum-tmf629-customer-management-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF632 Party Management

The Party Management API provides a standardized way to manage parties (organizations and individuals) across telecom systems, supporting customer, partner, supplier, and employee management in a unified party data model aligned to the TM Forum SID.

- **Human URL:** [https://github.com/tmforum-apis/TMF632_PartyManagement](https://github.com/tmforum-apis/TMF632_PartyManagement)

#### Tags

- Party Management
- BSS
- Master Data

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF632_PartyManagement)
- [OpenAPI](openapi/tm-forum-tmf632-party-management-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF633 Service Catalog Management

The Service Catalog API manages service specifications and service catalog entries, enabling telecom operators to expose and manage network and digital service offerings through standardized catalog APIs.

- **Human URL:** [https://github.com/tmforum-apis/TMF633_ServiceCatalog](https://github.com/tmforum-apis/TMF633_ServiceCatalog)

#### Tags

- Service Catalog
- OSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF633_ServiceCatalog)
- [OpenAPI](openapi/tm-forum-tmf633-service-catalog-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf633-service-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf633-service-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMF634 Resource Catalog Management

The Resource Catalog API manages resource specifications and resource catalog entries, providing a standardized interface for network and IT infrastructure resource discovery, specification, and lifecycle management.

- **Human URL:** [https://github.com/tmforum-apis/TMF634_ResourceCatalog](https://github.com/tmforum-apis/TMF634_ResourceCatalog)

#### Tags

- Resource Catalog
- OSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF634_ResourceCatalog)
- [OpenAPI](openapi/tm-forum-tmf634-resource-catalog-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf634-resource-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf634-resource-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMF637 Product Inventory Management

The Product Inventory API provides standardized access to product instances subscribed by customers, enabling product lifecycle management operations including provisioning, suspension, termination, and status queries.

- **Human URL:** [https://github.com/tmforum-apis/TMF637_ProductInventory](https://github.com/tmforum-apis/TMF637_ProductInventory)

#### Tags

- Product Inventory
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF637_ProductInventory)
- [OpenAPI](openapi/tm-forum-tmf637-product-inventory-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### TMF641 Service Order Management

The Service Ordering API manages service orders for provisioning and activating telecom services, orchestrating the end-to-end service delivery workflow from order intake to service activation.

- **Human URL:** [https://github.com/tmforum-apis/TMF641_ServiceOrder](https://github.com/tmforum-apis/TMF641_ServiceOrder)

#### Tags

- Service Ordering
- OSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF641_ServiceOrder)
- [OpenAPI](openapi/tm-forum-tmf641-service-ordering-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf641-service-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf641-service-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMF648 Quote Management

The Quote Management API handles the lifecycle of commercial quotes for telecommunications products and services, supporting quote creation, pricing, approval workflow, and conversion to orders.

- **Human URL:** [https://github.com/tmforum-apis/TMF648_QuoteManagement](https://github.com/tmforum-apis/TMF648_QuoteManagement)

#### Tags

- Quote Management
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF648_QuoteManagement)
- [OpenAPI](openapi/tm-forum-tmf648-quote-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf648-quote-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf648-quote-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMF651 Agreement Management

The Agreement Management API manages commercial agreements between parties in the telecom ecosystem, supporting SLA contracts, partner agreements, and customer agreements across BSS and partner management systems.

- **Human URL:** [https://github.com/tmforum-apis/TMF651_AgreementManagement](https://github.com/tmforum-apis/TMF651_AgreementManagement)

#### Tags

- Agreement Management
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF651_AgreementManagement)
- [OpenAPI](openapi/tm-forum-tmf651-agreement-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf651-agreement-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf651-agreement-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TMF666 Account Management

The Account Management API provides standardized management of financial and billing accounts, supporting account creation, balance management, credit limit operations, and financial transaction history queries.

- **Human URL:** [https://github.com/tmforum-apis/TMF666_AccountManagement](https://github.com/tmforum-apis/TMF666_AccountManagement)

#### Tags

- Account Management
- Billing
- BSS

#### Properties

- [Documentation](https://github.com/tmforum-apis/TMF666_AccountManagement)
- [OpenAPI](openapi/tm-forum-tmf666-account-management-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tm-forum-tmf666-account-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tm-forum-tmf666-account-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tm-forum)
- [Website](https://www.tmforum.org/)
- [Documentation](https://www.tmforum.org/oda/open-apis/)
- [Portal](https://www.tmforum.org/open-digital-architecture/open-apis)
- [GitHub Organization](https://github.com/tmforum-apis)
- [GitHub Organization](https://github.com/tmforum-oda)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Spectral Rules](rules/tm-forum-spectral-rules.yml)
- [Vocabulary](vocabulary/tm-forum-vocabulary.yaml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
