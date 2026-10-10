# Awesome-Revenue-Lifecycle-Management-Rlm

## Top Revenue Lifecycle Management (RLM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Quote-to-Cash, Subscription Billing & Self-Hosted Revenue Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial Revenue Lifecycle Management (RLM) platforms** and **open-source projects** that orchestrate the entire revenue journey — from product catalog and quoting through contract management, billing, and revenue recognition.



**Examples** include Salesforce Revenue Lifecycle Management, Model N, Conga Revenue Lifecycle, Zuora, DealHub, Subskribe, Monetize360, Icertis, BillingPlatform, and Maxio (the category leaders).



**Open-source emphasis**: Revenue Lifecycle Management is an emerging open-source domain. **Kill Bill** leads as the most mature open-source subscription billing platform with 15+ years of production use and a plugin architecture for tax, payment, and ERP integrations . **Lago** delivers open-source metering and usage-based billing with 10,000+ GitHub stars . **OpenMeter** brings real-time metering with first-class LLM token cost tracking for AI monetization . **Recurso** provides a Go-based billing engine with a built-in double-entry financial ledger and ASC 606 revenue recognition . **Hyperswitch** orchestrates payments across 120+ processors . **UniBee** and **FlexPrice** round out the ecosystem with universal billing and pricing infrastructure . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesforce Revenue Lifecycle Management](https://www.salesforce.com/)**  

  **Salesforce's native RLM** — product catalog, quoting, contract management, billing, and revenue recognition integrated with Salesforce. **Best for Salesforce customers**.



- **[Zuora](https://www.zuora.com/)**  

  **The enterprise subscription economy standard** — billing, revenue recognition, and subscription management for recurring revenue businesses. **Best for large enterprises**.



- **[Model N](https://www.modeln.com/)**  

  **Revenue management for life sciences and high-tech** — pricing, contracting, and compliance. **Best for complex B2B revenue models**.



- **[Conga Revenue Lifecycle](https://conga.com/)**  

  **Revenue lifecycle management** — CPQ, contract management, and billing on Salesforce. **Best for Salesforce-centric revenue operations**.



- **[DealHub](https://dealhub.io/)**  

  **CPQ and quote-to-revenue platform** — configure, price, quote, and contract with subscription billing. **Best for B2B sales teams**.



- **[Subskribe](https://www.subskribe.com/)**  

  **Unified CPQ and subscription billing** — quote-to-cash for modern SaaS. **Best for subscription businesses**.



- **[Monetize360](https://www.monetize360.com/)**  

  **Revenue lifecycle management** — CPQ, billing, and revenue recognition.



- **[Icertis](https://www.icertis.com/)**  

  **Contract lifecycle management** — AI-powered contract intelligence and obligation management. **Best for enterprise contract management**.



- **[BillingPlatform](https://billingplatform.com/)**  

  **Enterprise billing and revenue management** — complex billing models and revenue recognition. **Best for complex enterprise billing**.



- **[Maxio](https://www.maxio.com/)**  

  **Billing and financial operations** — subscription management with revenue analytics. **Best for SaaS companies**.



## Open-Source GitHub Projects



### Full Subscription Billing Platforms



- **[Kill Bill](https://github.com/killbill/killbill)**  

  **The leading open-source subscription billing and payments platform**, Apache-2.0 licensed with **5,600+ GitHub stars** . **15+ years of production use** with highly modular architecture — disable functionality you don't need or replace components with existing systems . **Plan/trial/add-on management via versioned XML catalog** . **Multi-phase subscription engine with automatic proration** . **Usage-based metering** and **plugin framework** for custom tax, fraud, and ERP integrations . **Kaui admin dashboard** provides MRR tracking, billing timeline visualization, and full audit history . **Best for enterprise-grade subscription billing** .



- **[Lago](https://github.com/getlago/lago)**  

  **Open-source metering and usage-based billing API**, AGPL-3.0 licensed with **10,000+ GitHub stars** . **Built in Go for high-volume event ingestion** . **Designed for AI, cloud, and API companies** needing flexible monetization with consumption tracking, subscription management, and revenue analytics . **Best for usage-based billing at scale** .



- **[Recurso](https://github.com/recurso-dev/recurso)**  

  **Open-source billing engine for SaaS**, MIT licensed, built in Go with PostgreSQL . **Built-in double-entry financial ledger** with ASC 606 revenue recognition (optional TigerBeetle mirror for throughput) . **8 aggregations and 7 charge models with exact rational math** . **Bandit-retry dunning engine** . **India GST depth** (Place of Supply, HSN, TDS, e-invoicing via GSP) . **Self-serve importers from Stripe + Chargebee** . **Best for teams needing built-in financial ledger and revenue recognition** .



- **[UniBee](https://github.com/UniBee-Billing/unibee)**  

  **Open-source universal billing software for SaaS businesses**, AGPLv3 licensed . **Community and enterprise versions** with subscription management, invoicing, billable metrics, product/plan management, webhooks, and transaction management . **Docker Compose deployment** . **Best for self-hosted billing with managed option** .



### Metering & Usage-Based Billing



- **[OpenMeter](https://github.com/openmeterio/openmeter)**  

  **Real-time metering and billing engine for AI, agentic, and DevTool monetization**, Apache-2.0 licensed with **1,170+ GitHub stars** . **Usage metering via CloudEvents** . **Tiered/graduated/flat-fee pricing** . **Entitlements and prepaid credits** . **First-class LLM token cost tracking** . **Built in Go with Kafka, ClickHouse, and PostgreSQL** . **Self-hosted via Docker Compose or Kubernetes Helm chart** . **Best for AI monetization with token tracking** .



- **[FlexPrice](https://github.com/flexprice/flexprice)**  

  **Open-source pricing and billing infrastructure** supporting any pricing model from usage-based to subscription . **No-code UI** for pricing configuration . **Real-time usage metering, credits and top-ups, and feature access control** . **Cloud or self-hosted** . **Best for flexible pricing models** .



- **[Meteroid](https://github.com/meteroid-oss/meteroid)**  

  **Rust-based open-source billing platform**, AGPL-3.0 licensed with **1,089+ GitHub stars** . **Modern architecture for product-led growth companies** . **Best for Rust-native billing infrastructure** .



### Payment & Revenue Operations



- **[Hyperswitch](https://github.com/juspay/hyperswitch)**  

  **Open-source payment orchestration platform from Juspay**, Apache-2.0 licensed with **43,000+ GitHub stars** . **Connects to 120+ payment processors through a single API** . **Intelligent routing, revenue recovery via retries, PCI-compliant card vault, and automated reconciliation** . **Modular architecture** allows deploying individual components . **Best for payment orchestration across processors** .



- **[Autumn](https://github.com/useautumn/autumn)**  

  **Simple Stripe integration layer for AI startups**, Apache-2.0 licensed with **2,644+ GitHub stars** . **Three functions, zero webhooks** — build pricing plans in 30 minutes with usage tracking, credits, and feature controls . **Best for rapid Stripe-based billing** .



- **[Lotus](https://github.com/uselotus/lotus)**  

  **Open-source pricing and packaging infrastructure**, Python-based with **1,730+ GitHub stars** . **Designed for teams wanting to launch, test, and scale complex billing models** with metering, invoicing, and real-time data . **Best for pricing experimentation** .



### Additional Strong Open-Source Options



- **Stripe Billing** — Commercial with open-source client libraries. Usage-based billing, invoicing, and revenue recovery .

- **Chargebee** — Commercial with free tier. Subscription management and recurring billing .

- **Laravel Cashier** — Official Laravel subscription billing integration for Stripe and Paddle, MIT licensed .

- **Paymenter** — Open-source billing and client management for hosting businesses, MIT licensed .

- **SolidInvoice** — Open-source invoicing platform for freelancers and small businesses, MIT licensed .

- **Crater** — AI-driven invoicing workflows and working capital tools .

- **Venn** — Modern self-hosted billing platform written in Clojure .



**Frameworks for building custom RLM solutions**: Combine **Kill Bill** for enterprise-grade subscription billing with plugin extensibility . Use **Lago** or **OpenMeter** for usage-based metering at scale . Deploy **Recurso** for teams needing a built-in financial ledger with ASC 606 revenue recognition . Integrate **Hyperswitch** for payment orchestration across multiple processors . Use **OpenMeter** for AI/DevTool monetization with first-class LLM token cost tracking . Choose **Autumn** for rapid Stripe-based billing in AI startups . Note that true enterprise RLM with full quote-to-cash orchestration, contract lifecycle management, and vendor-supported SLAs (Salesforce RLM, Zuora, Model N) remains primarily commercial territory; open-source stacks provide strong subscription billing, metering, and payment orchestration foundations that require integration for complete revenue lifecycle management.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Revenue Lifecycle Management platforms handle sensitive financial data and must comply with financial regulations, tax laws (VAT, GST, sales tax), and revenue recognition standards (ASC 606, IFRS 15). Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Revenue recognition is complex** — ASC 606 and IFRS 15 require careful implementation. Recurso provides built-in ASC 606 support , but most open-source billing platforms require custom implementation or integration with accounting systems .

- **Tax compliance varies by jurisdiction** — India GST, EU VAT, US sales tax, and other regimes have different requirements. Verify compliance before deployment .

- **License considerations**: Kill Bill uses Apache-2.0 , Lago uses AGPL-3.0 , OpenMeter uses Apache-2.0 , Recurso uses MIT , and Hyperswitch uses Apache-2.0 . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong subscription billing, metering, and payment orchestration foundations, but **full quote-to-cash orchestration, contract lifecycle management, and vendor-supported SLAs** remain primarily commercial offerings.
