# Rite Aid

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
