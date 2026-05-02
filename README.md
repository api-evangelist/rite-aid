# Rite Aid

Rite Aid is one of the nation's leading drugstore chains, providing prescription drugs, health and beauty aids, and convenience items. Rite Aid supports vendor integrations through EDI (Electronic Data Interchange) and B2B services, and offers digital health tools including an AI health assistant, pharmacy services, vaccination record management, and preventive health screening programs.

## APIs and Integrations

### Rite Aid EDI Integration
Rite Aid supports Electronic Data Interchange (EDI) for vendor integration using ANSI/ASC X12 standards (versions 4010 and 5010). Integration is managed through the OpenText Trading Grid platform.

**Supported Transaction Sets:**

| Transaction | Name | Description |
|-------------|------|-------------|
| 810 | Invoice | Vendor billing to Rite Aid |
| 820 | Payment Order | Payment remittance |
| 832 | Price/Sales Catalog | Product pricing data |
| 846 | Inventory Inquiry/Advice | Inventory status |
| 850 | Purchase Order | Rite Aid orders to vendors |
| 855 | Purchase Order Acknowledgment | Vendor confirms PO |
| 856 | Advance Ship Notice | Pre-shipment notification |
| 860 | Purchase Order Change | PO modification |
| 865 | Purchase Order Change Ack | Change acknowledgment |
| 997 | Functional Acknowledgment | EDI receipt confirmation |

- **EDI Portal:** https://raportal.riteaid.com/
- **EDI Services:** https://www.riteaidediservices.com/
- **Documentation:** https://www.riteaidediservices.com/transaction-guidelines/edi-standards-versions-transactions/

### Rite Aid Digital Health Services
Rite Aid's digital health platform includes an AI health assistant, pharmacy services with prescription transfer and records management, vaccination record access, and preventive health blood testing programs at 2,000+ locations.

- **Website:** https://riteaid.com/
- **Mobile App:** https://riteaid.com/app

## JSON Schemas

| Schema | Description |
|--------|-------------|
| [rite-aid-edi-transaction-schema.json](json-schema/rite-aid-edi-transaction-schema.json) | ANSI X12 EDI transaction structure |

## JSON Structures

| Structure | Description |
|-----------|-------------|
| [rite-aid-edi-transaction-structure.json](json-structure/rite-aid-edi-transaction-structure.json) | Field documentation for EDI transactions |

## JSON-LD

| Context | Description |
|---------|-------------|
| [rite-aid-context.jsonld](json-ld/rite-aid-context.jsonld) | Linked data context for Rite Aid pharmacy, EDI, and health service entities |

## Vocabulary

- [rite-aid-vocabulary.yml](vocabulary/rite-aid-vocabulary.yml) — Domain vocabulary covering EDI standards, pharmacy operations, and vendor integration

## Links

- **Website:** https://www.rite-aid.com
- **EDI Services:** https://www.riteaidediservices.com/
- **Vendor Portal:** https://raportal.riteaid.com/
- **Mobile App:** https://riteaid.com/app
- **Privacy Policy:** https://www.riteaid.com/privacy-policy
