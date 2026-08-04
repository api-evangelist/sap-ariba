# SAP Ariba (sap-ariba)

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

SAP Ariba is a cloud-based procurement and supply chain collaboration platform that connects buyers and suppliers. It offers APIs for procurement, sourcing, contract management, supplier management, and spend analysis.

**APIs.json:** [https://www.ariba.com](https://www.ariba.com)

## Tags

- B2B
- Contract Management
- Procurement
- Sourcing
- Spend Analysis
- Supplier Management
- Supply Chain

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### SAP Ariba Procurement API

Enables integration with procurement processes including requisitions, purchase orders, invoices, suppliers, and receipts across the SAP Business Network.

- **Human URL:** [https://developer.ariba.com/api/procurement](https://developer.ariba.com/api/procurement)
- **Base URL:** `https://openapi.ariba.com/api/procurement`

#### Tags

- Invoices
- Procurement
- Purchase Orders
- Requisitions
- Suppliers

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/procurement/overview)
- [OpenAPI](openapi/sap-ariba-procurement-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/sap-ariba-purchase-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/sap-ariba-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://developer.ariba.com/api/authentication)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Documentation](https://help.sap.com/docs/ariba-apis)

### SAP Ariba Sourcing API

Provides access to sourcing events, RFx processes, auctions, and bid management.

- **Human URL:** [https://developer.ariba.com/api/sourcing](https://developer.ariba.com/api/sourcing)
- **Base URL:** `https://openapi.ariba.com/api/sourcing`

#### Tags

- Auctions
- Bidding
- RFx
- Sourcing

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/sourcing/overview)
- [OpenAPI](https://developer.ariba.com/api/sourcing/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Sandbox](https://sandbox.ariba.com/api/sourcing)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Management API

Manages supplier lifecycle including onboarding, qualification, performance, and risk assessment.

- **Human URL:** [https://developer.ariba.com/api/supplier](https://developer.ariba.com/api/supplier)
- **Base URL:** `https://openapi.ariba.com/api/supplier`

#### Tags

- Onboarding
- Performance
- Risk Management
- Suppliers

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/supplier/overview)
- [OpenAPI](https://developer.ariba.com/api/supplier/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](https://developer.ariba.com/api/supplier/postman) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Hub](https://api.sap.com/api/supplier_management/overview)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Contract Management API

Enables contract creation, management, compliance tracking, and renewal workflows.

- **Human URL:** [https://developer.ariba.com/api/contracts](https://developer.ariba.com/api/contracts)
- **Base URL:** `https://openapi.ariba.com/api/contracts`

#### Tags

- CLM
- Compliance
- Contracts

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/contracts/overview)
- [OpenAPI](https://developer.ariba.com/api/contracts/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Analytical Reporting API

Provides access to spend analytics, reporting data, and business intelligence metrics.

- **Human URL:** [https://developer.ariba.com/api/analytics](https://developer.ariba.com/api/analytics)
- **Base URL:** `https://openapi.ariba.com/api/analytics`

#### Tags

- Analytics
- Business Intelligence
- Reporting
- Spend Analysis

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/analytics/overview)
- [OpenAPI](https://developer.ariba.com/api/analytics/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://developer.ariba.com/api/analytics/query-guide)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Invoice Management API

Manages invoice processing, approval workflows, and payment status tracking.

- **Human URL:** [https://developer.ariba.com/api/invoices](https://developer.ariba.com/api/invoices)
- **Base URL:** `https://openapi.ariba.com/api/invoices`

#### Tags

- AP Automation
- Invoices
- Payments

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/invoices/overview)
- [OpenAPI](https://developer.ariba.com/api/invoices/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ariba Network Purchase Orders Buyer API

Allows buyers to create, manage, and track purchase orders across the SAP Ariba Network.

- **Human URL:** [https://api.sap.com/api/purchase_orders/overview](https://api.sap.com/api/purchase_orders/overview)
- **Base URL:** `https://openapi.ariba.com/api/purchase-orders-buyer`

#### Tags

- Ariba Network
- Buyers
- Purchase Orders

#### Properties

- [Documentation](https://api.sap.com/api/purchase_orders/overview)
- [Hub](https://api.sap.com/api/purchase_orders/overview)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ariba Network Purchase Orders Supplier API

Enables suppliers to retrieve purchase order and line item information from buyers on the SAP Business Network.

- **Human URL:** [https://api.sap.com/api/purchase_orders_supplier/overview](https://api.sap.com/api/purchase_orders_supplier/overview)
- **Base URL:** `https://openapi.ariba.com/api/purchase-orders-supplier`

#### Tags

- Ariba Network
- Purchase Orders
- Suppliers

#### Properties

- [Documentation](https://api.sap.com/api/purchase_orders_supplier/overview)
- [Documentation](https://help.sap.com/doc/3b0b2f4faaa242dda9004b9f337592bf/cloud/en-US/purchase_order_supplier_api.pdf)
- [Hub](https://api.sap.com/api/purchase_orders_supplier/overview)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ariba Network Supplier Profile API

Provides access to supplier profile details on the SAP Ariba Network.

- **Human URL:** [https://api.sap.com/api/supplier_management/overview](https://api.sap.com/api/supplier_management/overview)
- **Base URL:** `https://openapi.ariba.com/api/supplier-profile`

#### Tags

- Ariba Network
- Profiles
- Suppliers

#### Properties

- [Documentation](https://api.sap.com/api/supplier_management/overview)
- [Hub](https://api.sap.com/api/supplier_management/overview)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ariba Network Invoice Header Data Extraction API

Extracts invoice header information from the SAP Ariba Network for data analysis and integration.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/invoice-extraction`

#### Tags

- Ariba Network
- Data Extraction
- Invoices

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Contract Compliance API

Ensures contract compliance by validating procurement activities against contract terms and conditions.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/contract-compliance`

#### Tags

- Compliance
- Contracts
- Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Data API

Provides access to general supplier data including company information and classification details.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-data`

#### Tags

- Data
- Master Data
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Data API with Pagination

Retrieves supplier data with pagination support for handling large datasets.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-data-paginated`

#### Tags

- Data
- Pagination
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Data Extraction API

Extracts detailed supplier information for integration with external systems and analytics.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-data-extraction`

#### Tags

- Data Extraction
- Integration
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Information API

Provides supplier profile and related detail information for supplier lifecycle management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-information`

#### Tags

- Lifecycle
- Profiles
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Invite API

Invites suppliers to participate in procurement transactions and network activities.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-invite`

#### Tags

- Invitations
- Onboarding
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Risk Exposure API

Analyzes and reports on supplier risk exposure across the supply chain.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/risk-exposure`

#### Tags

- Risk Management
- Suppliers
- Supply Chain

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Supplier Risk Engagements API

Manages supplier risk engagement activities and assessment workflows.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/supplier-risk-engagements`

#### Tags

- Assessments
- Risk Management
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Risk Category Information API

Provides risk classification and category details for supplier risk exposure analysis.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/risk-category`

#### Tags

- Categories
- Classification
- Risk Management

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Document Approval API

Handles approval workflows for procurement documents including requisitions and purchase orders.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/document-approval`

#### Tags

- Approvals
- Documents
- Workflows

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba External Approval API for Sourcing and Supplier Management

Enables external approval routing for sourcing events and supplier management processes.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/external-approval`

#### Tags

- Approvals
- Sourcing
- Supplier Management

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Catalog Content API

Enables applications to manage catalog content and get faceted catalog data based on specific attributes.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/catalog-content`

#### Tags

- Catalogs
- Content Management
- Products

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Network Catalog Management API

Controls catalog operations across the SAP Ariba Network including subscriptions and publishing.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/network-catalog`

#### Tags

- Catalogs
- Network
- Publishing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Internal Catalogs Shop API

Manages internal catalog shopping experiences for procurement users.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/internal-catalogs`

#### Tags

- Catalogs
- Internal
- Shopping

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Public Catalogs Shop API

Manages public marketplace catalog experiences for procurement users.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/public-catalogs`

#### Tags

- Catalogs
- Marketplace
- Shopping

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Contract Workspace Retrieval API

Retrieves contract workspace information for contract lifecycle management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/contract-workspace-retrieval`

#### Tags

- CLM
- Contracts
- Workspaces

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Contract Workspace Management API

Administers contract collaboration spaces including creation, updates, and lifecycle management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/contract-workspace-management`

#### Tags

- Contracts
- Management
- Workspaces

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Contract Terms Management API

Administers contract term definitions and clause libraries.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/contract-terms`

#### Tags

- Clauses
- Contracts
- Terms

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Operational Reporting API for Procurement

Delivers operational metrics and reporting data for procurement activities.

- **Human URL:** [https://help.sap.com/docs/ariba-apis/operational-reporting-api-for-procurement/operational-reporting-api-for-procurement](https://help.sap.com/docs/ariba-apis/operational-reporting-api-for-procurement/operational-reporting-api-for-procurement)
- **Base URL:** `https://openapi.ariba.com/api/operational-reporting-procurement`

#### Tags

- Operations
- Procurement
- Reporting

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis/operational-reporting-api-for-procurement/operational-reporting-api-for-procurement)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Operational Reporting API for Strategic Sourcing

Delivers operational metrics and reporting data for strategic sourcing activities.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/operational-reporting-sourcing`

#### Tags

- Operations
- Reporting
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Analytical Reporting API for Strategic and Operational Procurement

Delivers analytics across strategic and operational procurement domains including contracts, sourcing, spend analysis, and buying.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/analytical-reporting`

#### Tags

- Analytics
- Operational Procurement
- Reporting
- Strategic Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Master Data Retrieval API for Sourcing

Obtains master data for sourcing operations including commodity codes and regions.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/master-data-sourcing`

#### Tags

- Master Data
- Reference Data
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Master Data Retrieval API for Procurement

Retrieves procurement master data including cost centers, accounts, and units of measure.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/master-data-procurement`

#### Tags

- Master Data
- Procurement
- Reference Data

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Sourcing Project Management API

Oversees sourcing project workflows including event creation and management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/sourcing-project`

#### Tags

- Events
- Projects
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Event Management API

Manages sourcing events and their lifecycle including RFx and auction events.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/event-management`

#### Tags

- Auctions
- Events
- RFx
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Surrogate Bid API

Enables proxy bidding mechanisms for sourcing events on behalf of suppliers.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/surrogate-bid`

#### Tags

- Bidding
- Proxy
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Order Change Requests API for Buyers

Manages order modification requests from the buyer perspective.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/order-change-buyer`

#### Tags

- Buyers
- Change Requests
- Purchase Orders

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Order Change Requests API for Suppliers

Handles order change request processing from the supplier perspective.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/order-change-supplier`

#### Tags

- Change Requests
- Purchase Orders
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Ship Notice API for Buyers

Receives and processes shipment notifications for buyers on the Ariba Network.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/ship-notice-buyer`

#### Tags

- Buyers
- Notifications
- Shipping

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Ship Notice API for Suppliers

Sends shipment notifications from suppliers to buyers on the Ariba Network.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/ship-notice-supplier`

#### Tags

- Notifications
- Shipping
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Proof of Service API for Buyers

Validates service fulfillment and delivery for buyers in service procurement.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/proof-of-service-buyer`

#### Tags

- Buyers
- Proof of Service

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Proof of Service API for Suppliers

Validates service fulfillment and delivery for suppliers in service procurement.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/proof-of-service-supplier`

#### Tags

- Proof of Service
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Planning Collaboration Buyer API

Enables buyer-side planning and forecast collaboration with suppliers.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/planning-collaboration-buyer`

#### Tags

- Buyers
- Collaboration
- Forecasting
- Planning

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Planning Collaboration Supplier API

Enables supplier-side planning and forecast collaboration with buyers.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/planning-collaboration-supplier`

#### Tags

- Collaboration
- Forecasting
- Planning
- Suppliers

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Item Volume Import API

Imports item volume data for procurement planning and sourcing optimization.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/item-volume-import`

#### Tags

- Import
- Planning
- Volume

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Bill of Materials Import API

Imports bill of materials structures for sourcing and procurement processes.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/bom-import`

#### Tags

- BOM
- Import
- Materials

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Product Hierarchy Management API

Organizes product classification and category hierarchy structures.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/product-hierarchy`

#### Tags

- Classification
- Hierarchy
- Products

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Pricing API for Product Sourcing

Extracts and manages pricing data for product sourcing price information.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/pricing`

#### Tags

- Pricing
- Products
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Cost Breakdown Data Extraction API

Extracts cost component and cost breakdown information for analysis.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/cost-breakdown`

#### Tags

- Cost Analysis
- Data Extraction
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Content Lookup API

Searches and retrieves content across the SAP Ariba platform.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/content-lookup`

#### Tags

- Content
- Lookup
- Search

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Audit Search API

Provides audit trail search capabilities across procurement and sourcing activities.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/audit-search`

#### Tags

- Audit
- Compliance
- Search

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Create Procurement Workspace API

Initiates and creates procurement workspace environments for project collaboration.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/procurement-workspace`

#### Tags

- Collaboration
- Procurement
- Workspaces

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Flow Extension API

Extends workflow processing capabilities for custom procurement and sourcing processes.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/flow-extension`

#### Tags

- Customization
- Extensions
- Workflows

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Asynchronous Requests Management API

Manages long-running asynchronous operations and their status tracking.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/async-requests`

#### Tags

- Async
- Management
- Operations

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Integration Event Monitoring Query API for Procurement

Monitors and queries integration events for procurement process tracking.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/integration-event-monitoring`

#### Tags

- Events
- Integration
- Monitoring
- Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Integration Monitoring API for Procurement

Tracks integration health and performance for procurement system integrations.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/integration-monitoring-procurement`

#### Tags

- Integration
- Monitoring
- Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Integration Monitoring API for Strategic Sourcing

Tracks integration health and performance for strategic sourcing system integrations.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/integration-monitoring-sourcing`

#### Tags

- Integration
- Monitoring
- Sourcing

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Transaction Monitoring API

Observes and reports on transaction activities and processing status.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/transaction-monitoring`

#### Tags

- Monitoring
- Operations
- Transactions

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba NDA Data Export API

Exports non-disclosure agreement data for compliance and record keeping.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/nda-export`

#### Tags

- Compliance
- Export
- NDA

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Catalog Connectivity Service API

Connects to external catalog systems for punchout and roundtrip catalog integration.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/catalog-connectivity`

#### Tags

- Catalogs
- Integration
- Punchout

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Trading Partner Profile Certification API

Manages trading partner certifications and compliance documentation.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/trading-partner-certification`

#### Tags

- Certification
- Compliance
- Trading Partners

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba User Qualification API

Validates user eligibility and qualifications for procurement processes.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/user-qualification`

#### Tags

- Access
- Qualifications
- Users

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba SCIM API

Implements System for Cross-domain Identity Management for user provisioning and management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/scim`

#### Tags

- Identity
- Provisioning
- SCIM
- User Management

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Custom Forms API

Creates and manages custom form definitions for procurement and sourcing workflows.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/custom-forms`

#### Tags

- Customization
- Forms
- Workflows

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Dynamic Lookup Table API

Manages dynamic reference and lookup tables for configurable procurement data.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/dynamic-lookup-table`

#### Tags

- Configuration
- Lookup Tables
- Reference Data

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Guided Buying Functional Documents API

Manages guided buying documentation and functional purchase request workflows.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/guided-buying`

#### Tags

- Documents
- Guided Buying
- Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Asset Management API

Manages asset lifecycle and inventory tracking for procurement-related assets.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/asset-management`

#### Tags

- Assets
- Inventory
- Lifecycle

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Configuration Parameter Review API

Reviews and manages system configuration parameters for Ariba solutions.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/configuration-review`

#### Tags

- Administration
- Configuration
- Parameters

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Project Document Management API

Organizes and manages project-related documents within sourcing and procurement projects.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/project-documents`

#### Tags

- Documents
- Management
- Projects

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Public Procurement Notices Export API

Exports public procurement announcements and tender notices.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/public-procurement-notices`

#### Tags

- Notices
- Public Procurement
- Tenders

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba ETendering Notice Management API

Manages electronic tendering announcements and notice lifecycle.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/etendering`

#### Tags

- eTendering
- Notices
- Public Procurement

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Discovery RFx Publication TO External Marketplace API

Publishes RFx opportunities to external marketplaces for broader supplier discovery.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/discovery-rfx-to-external`

#### Tags

- Discovery
- Marketplace
- RFx

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Discovery RFx Publication FROM External Marketplace API

Imports RFx opportunities from external marketplaces into SAP Ariba.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/discovery-rfx-from-external`

#### Tags

- Discovery
- Marketplace
- RFx

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Materials and BOM Tag Management API

Manages tagging and classification for materials and bill of materials entries.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/materials-bom-tags`

#### Tags

- BOM
- Classification
- Materials

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Data Replication Status API

Monitors data replication status across multi-ERP configurations.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/data-replication-status`

#### Tags

- Integration
- Multi-ERP
- Replication

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Master Data Integration Job Status API

Tracks master data synchronization job status for operational procurement.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/master-data-job-status`

#### Tags

- Integration
- Jobs
- Master Data

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Engagement Risk Assessment External Response Import API

Imports external risk assessment responses for supplier engagement risk evaluation.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/risk-assessment-import`

#### Tags

- Assessments
- Import
- Risk Management

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Ariba Finding and Event Collaboration Integration API for Supplier Risk

Integrates risk findings and event collaboration for supplier risk management.

- **Human URL:** [https://help.sap.com/docs/ariba-apis](https://help.sap.com/docs/ariba-apis)
- **Base URL:** `https://openapi.ariba.com/api/risk-collaboration`

#### Tags

- Collaboration
- Findings
- Risk Management

#### Properties

- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Postman Collection](collections/sap-ariba-procurement-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-ariba-procurement-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/ariba)
- [Developer Portal](https://developer.ariba.com)
- [Authentication](https://developer.ariba.com/api/authentication)
- [Getting Started](https://developer.ariba.com/api/getting-started)
- [Status Page](https://status.ariba.com)
- [Support](https://help.sap.com/ariba)
- [Terms of Service](https://www.ariba.com/legal/terms-of-use)
- [Rate Limits](https://developer.ariba.com/api/rate-limits)
- [SDK](https://developer.ariba.com/tools/sdks)
- [Community](https://community.ariba.com)
- [Release Notes](https://developer.ariba.com/api/release-notes)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/overview)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/rest)
- [Hub](https://api.sap.com/package/SAPAribaOpenAPIs/documents)
- [Portal](https://api.sap.com/products/SAPAriba/apis/packages)
- [Documentation](https://help.sap.com/docs/ariba-apis)
- [Quickstart](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers)
- [Getting Started](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/steps-to-start-using-sap-ariba-apis)
- [Authentication](https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-authentication)
- [Resources](https://community.sap.com)
- [Marketplace](https://www.sap.com/products/spend-management/ariba-network.html)
- [Code Examples](https://github.com/SAP-samples/ariba-extensibility-samples)
- [Blog](https://community.sap.com/t5/spend-management-blog-posts-by-sap/sap-ariba-api-faq-and-best-practice-on-developer-portal-and-gateway/ba-p/13512565)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
