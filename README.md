# SAP Ariba (sap-ariba)
SAP Ariba is a cloud-based procurement and supply chain collaboration platform that connects buyers and suppliers. It offers APIs for procurement, sourcing, contract management, supplier management, and spend analysis.

**URL:** [Visit APIs.json URL](https://www.ariba.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - B2B, Contract Management, Procurement, Sourcing, Spend Analysis, Supplier Management, Supply Chain

## Timestamps

- **Created:** 2024
- **Modified:** 2026-04-18

## APIs

### SAP Ariba Procurement API
Enables integration with procurement processes including requisitions, purchase orders, invoices, suppliers, and receipts across the SAP Business Network.

**Human URL:** [https://developer.ariba.com/api/procurement](https://developer.ariba.com/api/procurement)

#### Tags:

 - Invoices, Procurement, Purchase Orders, Requisitions, Suppliers

#### Properties

- [Documentation](https://developer.ariba.com/api/apis/procurement/overview)
- [OpenAPI](openapi/sap-ariba-procurement-api.yml)
- [JSONSchema](json-schema/sap-ariba-purchase-order-schema.json)
- [JSONLD](json-ld/sap-ariba-context.jsonld)
- [Authentication](https://developer.ariba.com/api/authentication)

## Common Properties

- [DeveloperPortal](https://developer.ariba.com)
- [Authentication](https://developer.ariba.com/api/authentication)
- [GettingStarted](https://developer.ariba.com/api/getting-started)
- [StatusPage](https://status.ariba.com)
- [Support](https://help.sap.com/ariba)
- [TermsOfService](https://www.ariba.com/legal/terms-of-use)
- [RateLimits](https://developer.ariba.com/api/rate-limits)
- [SDK](https://developer.ariba.com/tools/sdks)
- [ReleaseNotes](https://developer.ariba.com/api/release-notes)

## Features

| Name | Description |
|------|-------------|
| Procure-to-Pay Automation | End-to-end automation from requisition through purchase order, receipt, and invoice processing. |
| Supplier Network | Access to millions of suppliers on the SAP Business Network for discovery and collaboration. |
| Three-Way Matching | Automated matching of purchase orders, receipts, and invoices for payment approval. |
| Contract Lifecycle Management | Full contract creation, compliance tracking, and renewal workflow management. |
| Spend Analytics | Comprehensive reporting and analytics across procurement, sourcing, and supplier management. |

## Use Cases

| Name | Description |
|------|-------------|
| Strategic Sourcing | Run RFx events, auctions, and supplier evaluations to optimize procurement decisions. |
| Invoice Automation | Automate invoice submission, approval workflows, and payment reconciliation. |
| Supplier Risk Management | Monitor supplier risk exposure and manage risk assessment engagements. |
| Catalog Management | Manage internal and external catalogs for guided buying experiences. |

## Integrations

| Name | Description |
|------|-------------|
| SAP S/4HANA | Native integration with SAP ERP for purchase order, invoice, and master data synchronization. |
| SAP Business Network | Connect buyers and suppliers for electronic document exchange across the network. |
| External ERP Systems | Integration with non-SAP ERP systems through standardized APIs and data replication. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SAP Ariba Procurement API](openapi/sap-ariba-procurement-api.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Procurement API](capabilities/shared/procurement.yaml) -- 19 operations for purchase orders, invoices, suppliers, requisitions, and receipts

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Procure-to-Pay](capabilities/procure-to-pay.yaml) | Procurement | 19 | Procurement Team |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
