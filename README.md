# Awesome-Deal-Desk-Automation

## Top Deal Desk Automation Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Quote-to-Cash Automation, CPQ, Deal Collaboration & Subscription Billing*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Deal Desk Automation**. These tools help revenue teams automate quoting, pricing, approvals, document generation, e-signature, and the handoff from deal to billing—reducing manual work and accelerating deal velocity.



**Examples** include DealHub, Ignition, QuoteWerks, Conga, Salesforce Revenue Cloud, Subskribe, Logik.io, Quoter, and Expedite Commerce (the category leaders).



**Open-source emphasis**: Deal Desk Automation is a **commercially dominated category**—DealHub, Conga, and Salesforce Revenue Cloud lead the market. However, the **open-source foundation is mature and composable**. **Odoo** provides a comprehensive open-source ERP with native CPQ, CRM, Sales, and eCommerce modules that can be extended for deal desk workflows . **Kill Bill** is the leading open-source subscription billing and payments platform, powering large SaaS and e-commerce organizations with real-time analytics and no vendor lock-in . **Bagisto B2B Ecommerce** delivers open-source B2B features including Request for Quote (RFQ), quotation handling, and company credit—directly relevant to deal desk automation . **DocuSeal** provides self-hosted document signing and form automation for contracts and agreements . **Lago** offers open-source metering and usage-based billing for complex pricing models .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[DealHub](https://dealhub.io/)**

  Agentic quote-to-revenue platform spanning CPQ, proposals, subscriptions, billing, and deal collaboration. **DealRoom** brings buyers and sellers into one shared space for quoting, contracts, and eSign. Blueshift achieved **500% faster deal approvals** and **80% fewer sales inquiries to operations** after adopting DealHub .



- **[Conga CPQ](https://conga.com/)**

  Enterprise CPQ built for complex quoting, pricing, and subscription lifecycles. Pairs intricate product configuration with **document automation** for clean quote-to-contract handoff. Suited for enterprise teams managing renewals and non-standard terms .



- **[Salesforce Revenue Cloud](https://www.salesforce.com/)**

  CPQ and billing suite for Salesforce-native organizations. Provides guided selling, pricing rules, approval workflows, and revenue recognition integrated with the Salesforce platform.



- **[Ignition](https://ignitionapp.com/)**

  Automates proposals, billing, payment collection, and client workflows. Popular with professional services firms for turning signed proposals into automated billing and revenue workflows .



- **[QuoteWerks](https://www.quotewerks.com/)**

  CPQ and quote management for SMBs. Provides product configuration, pricing, quote generation, and document automation with integrations to CRMs and accounting systems.



- **[Subskribe](https://www.subskribe.com/)**

  Adaptive CPQ and billing platform for SaaS. Handles subscription management, usage-based pricing, and revenue recognition.



- **[Logik.io](https://www.logik.io/)**

  Headless, composable, API-first CPQ and product configuration engine. Powers guided configuration, pricing, and quoting across Salesforce CPQ/Commerce and headless frontends.



- **[Quoter](https://quoter.com/)**

  CPQ and quoting for SMBs and MSPs. Provides quote generation, pricing, and approval workflows with a focus on simplicity.



- **[Expedite Commerce](https://www.expeditecommerce.com/)**

  CPQ and eCommerce platform for B2B manufacturers and distributors. Handles complex product configuration, pricing, and quote-to-order workflows.



## Open-Source GitHub Projects



### ERP & CPQ Foundations



- **[Odoo](https://github.com/odoo/odoo)**

  **The most comprehensive open-source ERP platform and the strongest foundation for deal desk automation.** **Open-source** (Community edition LGPLv3, Enterprise commercial). **Native CPQ capabilities** through modular apps: CRM, Sales, Product Configurator, eCommerce, Inventory, Accounting, and Manufacturing . Aktiv Software built their CPQ solution on Odoo because it provides "a proven, open-source ecosystem that's modular, extensible, and fully customizable" . **Key advantage**: Integrates natively with Accounting, CRM, Inventory, eCommerce, and Manufacturing—enabling true quote-to-cash in a single system . **Free Version** available; **Cloud and On-Premise** deployment .



- **[Kontor](https://github.com/Kontor-ProcessWire/Kontor)**

  **Modular open-source ERP, CRM, and business operations platform for ProcessWire.** **MIT licensed**. **35 components** sharing one audited core and permission-aware admin workspace . **Deal desk relevant modules**: **CRM** (leads, pipelines, stages, deals, Kanban); **Catalog** (products/services, price lists); **Sales** (quotations, orders, status workflows); **Invoices** (quotation-to-order-to-invoice conversion); **Workflow** (state-machine engine with approvals); **Documents** (versioned templates, PDF rendering, immutable issued-document snapshots); **Portal** (customer self-service for quotations, invoices, payments) . **Best for**: Organizations wanting a composable, self-hosted business platform with deal-to-cash workflows.



### B2B Quote & RFQ Platforms



- **[Bagisto B2B Ecommerce](https://github.com/bagisto/b2b-ecommerce)**

  **Open-source B2B eCommerce package extending Bagisto with powerful B2B features.** **MIT licensed** . **Deal desk relevant features**: **Company Registration & Approval**; **Role-Based Permissions**; **Request for Quote (RFQ)** from cart; **Quotation Handling** with end-to-end buyer-seller negotiation and messaging; **Purchase Orders**; **Company Catalogs** with per-company pricing (flat, percentage, quantity-tier); **Company Credit** with audited ledger and Pay By Credit checkout . **Built for**: Wholesalers, manufacturers, distributors needing flexible B2B quote-to-order workflows.



- **[Spree Commerce B2B](https://github.com/spree/spree)**

  **Open-source eCommerce platform with B2B wholesale portal capabilities.** **Spree 5.6** supports **wholesale portals** with spreadsheet-style ordering grids, customer-specific pricing, and pre-orders . **Enterprise Edition B2B module** adds buyer organizations, spending limits, and role-based purchasing . **Open source**, **Docker-image-first deployment** with 40% smaller image and 2-3x faster app creation . **Best for**: B2B commerce portals with quote and order workflows.



- **[Virto Commerce](https://github.com/VirtoCommerce/vc-platform)**

  **Open-source B2B eCommerce platform with native quotes module.** **Quoter** enables business users to execute quote requests online, with internal pricing negotiation (quantity breaks, discounts) and customer acceptance/rejection . **Modular architecture** with catalog, pricing, order, customer, and marketing modules .



### Subscription Billing & Metering



- **[Kill Bill](https://github.com/killbill/killbill)**

  **The leading open-source subscription billing and payments platform for over 10 years.** **Apache 2.0 licensed** . **Out-of-the-box**: subscription management, invoicing, payment processing, real-time analytics, and financial reports. **No vendor lock-in**—you control your business and client data . **Highly modularized**—disable functionality you don't need or replace with existing systems . **On-premises or cloud**, scales with your subscription business . **Best for**: SaaS and e-commerce organizations needing robust subscription billing.



- **[Lago](https://github.com/getlago/lago)**

  **Open-source metering and usage-based billing platform.** **Open-source** (self-hosted) and **Lago Cloud** (SaaS) . **Five-step billing workflow**: Usage Ingestion (event-based, duplicate prevention); Metrics Aggregation (COUNT, COUNT_UNIQUE, LATEST, MAX, SUM, WEIGHTED SUM); Pricing & Packaging (subscription, usage-based, or hybrid); Invoicing (automated generation with fees and taxes); Payments (native integrations or any PSP via invoice payload) . **Best for**: Complex usage-based and hybrid pricing models.



- **[UniBee](https://github.com/UniBee-Billing/unibee)**

  **Open-source universal billing software for SaaS businesses.** **AGPLv3 licensed** . **Features**: Subscription management, invoicing, billable metrics, product/plan management, webhooks, user management, reports, transaction management, discounts, and user portal . **Docker Compose deployment** . **Best for**: SaaS businesses wanting an affordable, self-hosted billing alternative to Recurly, Chargebee, and Paddle .



### Document Automation & eSignature



- **[DocuSeal](https://github.com/docusealco/docuseal)**

  **Open-source document signing and form automation platform.** **AGPL licensed** (with SaaS version available) . **Features**: Visual PDF field editor; 10 field types in free version (checkbox, image, date, multiple choice); **multiple signers with sequential order**; invitations via your own SMTP; signed documents stored on your disk, S3, Google Storage, or Azure; **REST API and webhooks** . **eIDAS-compliant simple electronic signature** (valid for quotes and internal agreements; qualified signature available via partner) . **Docker deployment**: `docker run --name docuseal -p 3000:3000 -v.:/data docuseal/docuseal` . **Best for**: Self-hosted contract and agreement signing.



### Product Configuration Engines



- **[openCPQ](https://github.com/webXcerpt/openCPQ)**

  **Browser-based product configuration framework.** **MIT licensed** . React-based, data-driven product modeling with reusable knowledge and ecosystems. **Use cases**: Complex product configuration, bill of materials, pricing . **Best for**: Building custom product configurators with code.



### Additional Strong Open-Source Options



- **ERP/CPQ Foundations**: **Odoo** (native CPQ, quote-to-cash integration) , **Kontor** (35 components, workflow, portal) .

- **B2B Quote/RFQ**: **Bagisto B2B** (RFQ, quotation negotiation, company credit) , **Spree Commerce B2B** (wholesale portal) , **Virto Commerce** (Quoter module) .

- **Billing**: **Kill Bill** (Apache 2.0, subscription billing) , **Lago** (usage-based metering) , **UniBee** (AGPLv3, SaaS billing) .

- **eSignature**: **DocuSeal** (AGPL, self-hosted) .

- **Configuration**: **openCPQ** (MIT, browser-based configurator) .



**Frameworks for building custom systems**: Combine **Odoo** as the core ERP/CPQ foundation with native CRM, Sales, and Accounting, **Bagisto B2B** or **Spree B2B** for RFQ and quotation negotiation workflows, **Kill Bill** or **Lago** for subscription and usage-based billing, **DocuSeal** for self-hosted eSignature, and **openCPQ** for custom product configuration. Add **PostgreSQL** for persistence and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Deal desk automation platforms handle sensitive pricing, contract, and customer data; ensure proper access controls and compliance with data protection regulations.

- **Open-source reality**: The open-source ecosystem for deal desk automation is **mature at the component level** but **requires assembly** for full quote-to-cash. **Odoo** provides the most comprehensive foundation with native CPQ, CRM, Sales, and Accounting . **Bagisto B2B** delivers production-grade RFQ and quotation workflows . **Kill Bill** and **Lago** handle subscription and usage-based billing at scale . **DocuSeal** provides self-hosted eSignature . However, **commercial platforms** (DealHub, Conga, Salesforce Revenue Cloud) offer **integrated deal collaboration, AI-powered guided selling, and enterprise-grade approval workflows** that open-source alternatives require significant integration to match. The open-source path is **genuinely viable** for organizations with strong engineering capacity seeking full data ownership and zero license fees.



---



**Made for revenue operations teams, sales engineers, finance leaders, and full-stack developers.**

Let's make deal desk automation more open, transparent, and efficient.
