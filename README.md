# Awesome-Customer-Data-Platform-CDP

# Awesome-Customer-Data-Platform-CDP

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Customer Data Unification, Identity Resolution, Audience Segmentation & Data Activation*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Data Platforms (CDP)**. These tools help organizations collect, unify, and activate customer data across channels, creating a single customer view for marketing, analytics, and personalization.

**Examples** include Microsoft Dynamics 365 Customer Insights, Salesforce Data Cloud, Adobe Real-Time CDP, Segment (Twilio), Tealium, mParticle, Treasure Data, Simon Data, BlueConic, and ActionIQ (the category leaders).

**Open-source emphasis**: The open-source CDP ecosystem is **developing but fragmented**. **RudderStack** leads as the most mature warehouse-first CDP with Segment API compatibility . **Apache Unomi** is the only Apache Top-Level Project in this category, serving as the OASIS CDP specification reference implementation . **Tracardi** provides an API-first composable CDP engine , while **Jitsu** offers a lightweight event pipeline under MIT license . However, **no open-source CDP matches the full enterprise capabilities** of Salesforce, Adobe, or Oracle .

Contributions welcome! Open an Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global CDP market was evaluated across **100+ companies** in 2025, with the top 25 recognized as quadrant leaders based on revenue, growth strategies, and technological innovations . **Salesforce, Oracle, and Adobe** lead the market with AI-driven customer insights, real-time data integration, and privacy-first personalization . Latka tracks **107 CDP companies with $10M–$100M revenue**, representing **$3.2B in combined revenue** and **$2.7B in funding** . The sector is **moderately concentrated** at the enterprise tier, with hyperscalers and specialized vendors competing on different strengths.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Salesforce Data Cloud](https://www.salesforce.com/)** | **Top-ranked CDP with Einstein AI.** Unifies customer data from sales, service, and commerce into real-time profiles. Part of Customer 360 ecosystem . | **Enterprise pricing** — quote required. Salesforce CDP typically starts at **~$108,000/year** for mid-size deployments. | **None** — enterprise demo required. | **~$37.9B revenue (FY2025)** |
| **[Adobe Real-Time CDP](https://business.adobe.com/)** | **Top-ranked CDP with privacy-by-design.** Consolidates B2C and B2B data into real-time profiles for personalized experiences across marketing channels . | **Enterprise pricing** — quote required. Adobe Real-Time CDP starts at **~$125,000/year** for enterprise deployments. | **None** — enterprise demo required. | **~$21.5B revenue (FY2025)** |
| **[Oracle Unity CDP](https://www.oracle.com/)** | **Top-ranked CDP with AI-driven analytics.** Captures data from marketing, commerce, and service channels. Strong in data governance and compliance . | **Enterprise pricing** — quote required. Oracle Unity starts at **~$100,000/year** for enterprise deployments. | **None** — enterprise demo required. | **~$53B revenue (Oracle FY2025)** |
| **[Microsoft Dynamics 365 Customer Insights](https://dynamics.microsoft.com/)** | **Microsoft's CDP within Dynamics 365.** Unifies customer data and provides AI-powered insights and personalization. | **$1,500/month** (base) + **$1,000/month** per additional 100,000 unified profiles. | **None** — 30-day trial available via Dynamics 365 trial. | **~$281B revenue (Microsoft FY2025)** |
| **[Segment (Twilio)](https://segment.com/)** | **The CDP category pioneer.** Developer-first event collection and routing with 450+ connectors. Strong schema governance via Protocols. | **Free**: 1,000 monthly tracked users (MTUs); **Team**: $120/month; **Business**: $1,000/month. MTU-based pricing escalates at scale. | **Free tier**: **1,000 MTUs/month**, 2 sources, 2 destinations. | **~$4.9B revenue (Twilio FY2025)** |
| **[Tealium](https://tealium.com/)** | **CDP with deep tag management heritage.** 1,200+ prebuilt integrations, strong in regulated verticals with HIPAA-compliant private cloud. | **Enterprise pricing** — quote required. Entry contracts typically start at **~$60,000/year**. | **None** — enterprise demo required. | **Private (~$100M+ revenue est.)** |
| **[mParticle](https://www.mparticle.com/)** | **Mobile-first CDP known for low TCO.** Strong mobile SDKs and data quality. Acquired by Rokt in January 2025 for $300M . | **Enterprise pricing** — quote required. Entry contracts typically **$50,000–$100,000/year**. | **Free tier**: Available with limited MTUs and features. | **Acquired by Rokt ($300M)** |
| **[Treasure Data](https://www.treasuredata.com/)** | **Hybrid CDP supporting Complete and Composable modes.** Sub-second latency for profile lookups. Named in CDP quadrant leaders . | **Enterprise pricing** — quote required. Gartner reports pricing nearly double the second-highest response. | **None** — enterprise demo required. | **Private (~$230M+ raised)** |
| **[BlueConic](https://www.blueconic.com/)** | **CDP with strong first-party data focus.** Named in CDP quadrant leaders . | **Enterprise pricing** — quote required. Entry contracts typically start at **~$40,000/year**. | **None** — enterprise demo required. | **Private (~$100M+ raised)** |
| **[ActionIQ](https://www.actioniq.com/)** | **Enterprise CDP with warehouse-native architecture.** Acquired by Uniphore in late 2024 . | **Enterprise pricing** — quote required. | **None** — enterprise demo required. | **Acquired by Uniphore** |

## 🔓 Open-Source GitHub Projects

Sorted by star count (descending). Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|---|---|---|
| **[RudderStack](https://github.com/rudderlabs/rudder-server)** — **The most mature open-source CDP.** Warehouse-first Customer Data Pipeline and Segment alternative. Collects and routes clickstream data, builds customer data lake on your warehouse. **ELv2 licensed** (not OSI-approved but source-available). Segment API compatible . | [![Stars](https://img.shields.io/github/stars/rudderlabs/rudder-server?style=social&color=white)](https://github.com/rudderlabs/rudder-server/stargazers) | ~4,500 |
| **[Apache Unomi](https://github.com/apache/unomi)** — **Apache Top-Level Project and OASIS CDP specification reference implementation.** Java-based CDP managing customer, lead, and visitor data with privacy features (GDPR, Do Not Track). Features segmentation, personas, A/B testing. In use at Al-Monitor, Altola, Jahia . | [![Stars](https://img.shields.io/github/stars/apache/unomi?style=social&color=white)](https://github.com/apache/unomi/stargazers) | ~500 |
| **[Jitsu](https://github.com/jitsucom/jitsu)** — **Open-source data collection platform (Segment alternative).** Collects events from websites, apps, and servers, streams to data warehouses. **MIT licensed**, self-host on any cloud provider, no usage limits . | [![Stars](https://img.shields.io/github/stars/jitsucom/jitsu?style=social&color=white)](https://github.com/jitsucom/jitsu/stargazers) | ~4,000 |
| **[LEO CDP](https://github.com/trieu/leo-cdp-framework)** — **Open-source AI-first CDP framework.** Self-hosted, privacy-friendly with ML and big data at core. Features: omnichannel data collection, real-time Customer 360, AI segmentation (RFM, CLV, churn), Agentic AI personalization with LLMs, API-first architecture . | [![Stars](https://img.shields.io/github/stars/trieu/leo-cdp-framework?style=social&color=white)](https://github.com/trieu/leo-cdp-framework/stargazers) | ~200 |
| **[Tracardi](https://github.com/Tracardi/tracardi-api)** — **API-first composable open-source CDP engine.** Build your own CDP with total control. Features: customer data collection, profile unification, real-time personalization, social engagement bridges. **MIT with Common Clause license** . | [![Stars](https://img.shields.io/github/stars/Tracardi/tracardi-api?style=social&color=white)](https://github.com/Tracardi/tracardi-api/stargazers) | ~300 |

**Additional open-source options worth exploring:**

| Repo | Description |
|---|---|
| **[Cairo](https://github.com/outcome-driven-studio/cairo)** — **Segment-compatible self-hosted CDP.** Full pipeline: identity resolution, event transformations, tracking plans, GDPR compliance, event replay. First-class AI agent tracking (LLM generations, tool calls) with MCP server. Node.js + PostgreSQL . |
| **[Odoo CRM](https://github.com/odoo/odoo)** — Open-source ERP with CRM, marketing automation, and customer data management. Multi-channel campaigns, lead scoring, and personalization . |
| **[Pimcore](https://github.com/pimcore/pimcore)** — Open-core data & experience management platform (PIM, MDM, CDP, DAM, DXP/CMS) . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CDP platforms handle sensitive customer data; ensure compliance with GDPR, CCPA, and applicable data protection regulations.
- **Open-source reality**: The open-source CDP ecosystem is **developing but fragmented**. **RudderStack** is the most mature open-source CDP with Segment API compatibility and warehouse-first architecture . **Apache Unomi** is the only Apache Top-Level Project in this category, serving as the OASIS CDP specification reference implementation with proven enterprise deployments . However, **commercial platforms** (Salesforce, Adobe, Oracle) provide **unified AI-powered insights, real-time data integration, and privacy-first personalization at enterprise scale** that open-source alternatives require significant integration and engineering investment to match . The open-source path is **genuinely viable** for organizations with strong data engineering capacity seeking full data sovereignty.
- **License caveat**: **RudderStack uses ELv2** (not OSI-approved) and **Tracardi uses MIT with Common Clause** — evaluate license compatibility before commercial use .

---

**Made for CDP engineers, marketing technologists, data platform teams, and customer experience architects.**
Let's make customer data platforms more open, transparent, and privacy-first.
