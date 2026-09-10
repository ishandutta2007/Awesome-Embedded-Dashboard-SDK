# Awesome-Embedded-Dashboard-SDK

# 📊 Top Embedded Dashboard SDK



A curated list of **Embedded Analytics, Embedded BI, Dashboard SDKs, white-label analytics platforms, and open-source alternatives** for integrating interactive dashboards and analytics directly into SaaS applications, portals, enterprise software, and customer-facing products.



Embedded Dashboard SDKs allow developers to bring **charts, dashboards, data exploration, filtering, drill-downs, dashboard builders, analytics APIs, multi-tenancy, row-level security, white-labeling, and analytics experiences** directly into an existing application.



> **Open-source software is the primary focus of this list.** The open-source ecosystem is particularly strong around full BI platforms that can be embedded, including **Apache Superset, Metabase, Lightdash, Grafana, Redash, and related projects**. Some provide dedicated embedding SDKs, while others can be integrated through APIs, web components, iframes, or custom frontend components.



## 📑 Table of Contents



* [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)

* [🌍 Open-Source](#-open-source)

* [🧩 Open-Source Embedded Analytics Building Blocks](#-open-source-embedded-analytics-building-blocks)

* [🏗️ Embedded Analytics Architecture](#️-embedded-analytics-architecture)

* [🔍 Commercial vs Open-Source](#-commercial-vs-open-source)

* [⭐ Recommended Open-Source Options](#-recommended-open-source-options)

* [🤝 How to Contribute](#-how-to-contribute)

* [⚠️ Disclaimer](#️-disclaimer)



---



## ☁️ SaaS/Hosted Platforms



| Platform | Description | Primary Focus | Pricing (Starting Tier) | Free Tier / Trial Limit |
| --- | --- | --- | --- | --- |
| [Luzmo](https://www.luzmo.com/) | Embedded analytics platform providing dashboard embedding, dashboard editing, code-first visualizations, multi-tenant access controls, and analytics components. | Embedded Analytics, SaaS | Starts at $1,995/month (billed annually) platform fee | 10-day free trial with full platform access (no permanent free tier) |
| [Reveal BI](https://www.revealbi.io/) | Embedded analytics platform designed specifically for integrating interactive dashboards and visualizations into applications across web, desktop, and mobile. | Embedded BI, White-Label | Starts at ~$8,995–$9,990/year flat fee per application (unlimited users) | 30-day free trial of SDK & embedded dashboard features (no permanent free tier) |
| [Looker Embedded](https://cloud.google.com/looker) | Google's embedded analytics offering based on Looker, enabling organizations to integrate governed analytics, dashboards, and data exploration into applications. | Enterprise BI, Embedded Analytics | Looker Core Standard starts at ~$35,000–$60,000/year (~$2,900/month) + user licenses (Viewer $30/mo, Standard $60/mo, Developer $125/mo) | No self-service free trial; evaluation instance / Proof of Concept (POC) available via Google Cloud sales |
| [GoodData Embedded](https://www.gooddata.com/) | Analytics platform with developer-focused SDKs and UI components for embedding dashboards, visualizations, and analytics experiences into applications. | Embedded BI, Headless Analytics | Growth tier starts at ~$1,500/month (per-workspace model with unlimited users) | Free forever tier (development & small teams, up to 5 workspaces, REST API) + 30-day full-feature trial |
| [Metabase Embedded](https://www.metabase.com/embedding/) | Embedded analytics capabilities from Metabase supporting dashboards, interactive analytics, filters, and application-integrated experiences. | Embedded BI, Self-Service Analytics | Pro plan with full interactive embedding & SDK starts at $518–$575/month (includes 10 users; +$12/user/month) | 14-day free trial of Pro/Enterprise; self-hosted open-source version is free forever for basic iframe embedding |
| [Apache Superset Embedded](https://superset.apache.org/) | Apache Superset provides an official Embedded SDK for integrating Superset dashboards into host applications using guest-token authentication. | Open-Source Embedded BI | Free & Open Source ($0/month self-hosted under Apache 2.0); Managed cloud via Preset starts at $20/user/month + $500/month for 50 embedded viewer licenses | Self-hosted is free forever with unlimited users; Preset hosted offers 14-day trial and 5-user free tier |
| [Bold BI](https://www.boldbi.com/) | Embedded analytics platform offering JavaScript SDKs, REST APIs, dashboard embedding, white-labeling, multi-tenancy, filtering, events, and dashboard authoring. | Embedded BI, SaaS | Embedded Cloud/Server plans start at ~$495–$795/month (flat platform pricing, no per-user fees) | Free Community License (free forever for teams with <$1M revenue, ≤5 devs, ≤10 employees); 30-day full-feature free trial |
| [Logi Symphony](https://insightsoftware.com/logi/) | Embedded analytics platform for building interactive dashboards, reports, data visualizations, and analytics directly into software applications. | Embedded Analytics | Enterprise contracts start at ~$16,000–$25,000/year (~$1,330/month) | No self-service free trial; guided product demonstration and evaluation Proof of Concept (POC) available upon request |
| [Helical Insight](https://www.helicalinsight.com/) | Open-source-friendly BI and embedded analytics platform supporting dashboards, reporting, self-service analytics, and application embedding. | Embedded BI, Open Source | Enterprise Edition starts at custom annual subscription / ~$1,500/month (per-core or server license) | Community Edition is free forever (complete feature set including AI and embedding, with non-removable watermark); 30-day Enterprise POC trial |
| [DashboardFox](https://www.dashboardfox.com/) | Embedded dashboard and reporting platform focused on integrating analytics into applications and customer portals. | Embedded Dashboards | Cloud Starter at $99/month (up to 5 Monthly Active Users) or Self-Hosted Perpetual license at $4,995 one-time | 7-day free trial (extendable to 14 days upon request, no credit card required) |
| [Sisense](https://www.sisense.com/) | Embedded analytics platform providing APIs, SDKs, dashboards, data models, and white-label analytics for software products. | Embedded Analytics, SaaS | Enterprise embedded contracts typically start at ~$20,000–$40,000/year (~$1,660/month) | Interactive "Test Drive" environment and 7-day to 30-day evaluation trial arranged via sales |
| [Domo Everywhere](https://www.domo.com/platform/embedded-analytics) | Embedded analytics offering for integrating Domo dashboards, data applications, and analytics into external applications. | Embedded BI | Domo credit-based subscription starting at ~$30,000/year (~$2,500/month) for small teams with unlimited users | 30-day free trial (full platform access, unlimited users, sample datasets, no credit card required) |
| [Qlik Embedded Analytics](https://www.qlik.com/us/products/qlik-embedded-analytics) | Developer platform for embedding Qlik analytics, visualizations, and data experiences into applications. | Embedded BI | Qlik Cloud Standard starts at $825/month (25 GB data) / Premium for anonymous embedded access starts at $2,750/month (50 GB data) | 30-day full-featured free trial of Qlik Cloud Analytics (no credit card required) |
| [Power BI Embedded](https://azure.microsoft.com/products/power-bi-embedded) | Microsoft Azure service for embedding Power BI reports and dashboards into applications for customers and users. | Enterprise Embedded BI | Azure A1 SKU capacity starts at $1.008/hour (~$735/month for continuous 24/7 run, pausable when idle) | Azure 30-day free account ($200 in credits) + free development embed tokens (non-production testing only) |
| [Tableau Embedded Analytics](https://www.tableau.com/products/embedded-analytics) | Salesforce Tableau platform for embedding interactive analytics and dashboards into applications and portals. | Enterprise Embedded BI | Embedded deployments start at ~$4,000–$10,000/year (or Creator seat at $75/user/month, Viewer at $35/user/month) | 14-day Tableau Cloud free trial & 30-day Tableau Developer Program sandbox with full API access |
| [ThoughtSpot Embedded](https://www.thoughtspot.com/product/embedded) | Embedded analytics platform focused on search-driven analytics, AI-assisted insights, dashboards, and data exploration inside applications. | AI Analytics, Embedded BI | ThoughtSpot Essentials starts at $1,250/month; Embedded enterprise plans start at custom quotes | Developer Plan is free for 1 year (proof-of-concept for up to 5 users, 25M data rows) + 30-day free trial |
| [Pyramid Analytics](https://www.pyramidanalytics.com/) | Enterprise analytics platform with embedded BI, dashboards, data discovery, visualization, and advanced analytics capabilities. | Enterprise Analytics | Enterprise quote-based deployments start at ~$15,000–$30,000/year | Free Community Edition (limited to 3 users for non-production/POC); 30-day free trial of Enterprise Edition |
| [Yellowfin Embedded](https://www.yellowfinbi.com/) | Embedded BI platform offering dashboards, data storytelling, analytics, and application-integrated business intelligence. | Embedded BI | Starts at $19/user/month (or custom server core/OEM revenue-share starting ~$10,000/year) | 30-day full-feature free trial with direct data connectors + free Proof of Concept (POC) |
| [Phocas Embedded](https://www.phocassoftware.com/) | Embedded analytics platform for integrating dashboards, reporting, and business intelligence into operational applications. | Embedded Analytics | Starts at ~$1,000/month ($12,000/year) platform & user fee + one-time onboarding fee | No self-service free trial; personalized evaluation demo and scoping session via sales |
| [Logi Analytics](https://insightsoftware.com/logi/) | Developer-oriented analytics platform for embedding dashboards, reports, visualizations, and analytics into custom applications. | Developer BI | Enterprise contracts start at ~$16,000/year (under insightsoftware / Logi Symphony family) | No self-service free trial; guided live demo and evaluation POC on request |
| [Explo](https://www.explo.co/) | Embedded analytics platform designed for SaaS products to integrate customer-facing dashboards and reports. | SaaS Embedded Analytics | Growth tier starts at $695/month ($8,350/year billed annually); Pro tier at $1,995/month | 7-day to 14-day free trial upon request (integrated under Omni) |
| [Holistics](https://www.holistics.io/) | BI and embedded analytics platform supporting dashboards, reports, data models, and customer-facing analytics. | Embedded BI | Entry tier starts at $800/month ($9,600/year billed annually); Standard tier at $1,000/month | 14-day free trial (extendable to 21 days upon request, no credit card required, includes Embedded mode) |
| [Embeddable](https://embeddable.com/) | Developer-first embedded analytics platform for building highly customizable customer-facing dashboards and data applications. | Developer-First Embedded BI | Flat monthly subscription starting at ~$1,500–$2,500/month (session-based, unlimited end users) | Guided Proof-of-Concept (POC) with standard 3-month break clause (no self-service trial) |
| [Quill](https://www.quill.co/) | Embedded analytics infrastructure for adding dashboards and data experiences to SaaS products. | SaaS Analytics | Developer analytics infrastructure starting at ~$1,000–$1,500/month | Free sandbox and developer evaluation environment available on request |
| [Preset](https://preset.io/) | Hosted Apache Superset platform providing managed BI and dashboard infrastructure. | Superset Cloud | Preset Professional starts at $20/user/month + $500/month Embedded Dashboard Viewer pack (50 viewers) | Free Starter Plan forever (up to 5 users, 1 workspace, unlimited charts/dashboards) + 14-day Professional trial |
| [Holistics Embedded](https://www.holistics.io/embedded-analytics/) | Embedded analytics capabilities designed for SaaS applications and customer-facing data products. | Embedded Analytics | Embedded plan starts at $800/month ($9,600/year billed annually) | 14-day free trial (extendable to 21 days upon request, no credit card required) |



---



## 🌍 Open-Source



> ⭐ **This is the primary section of this repository.**

>

> There are surprisingly strong open-source options for embedded analytics. Instead of purchasing a proprietary Embedded BI SDK, companies can self-host an open-source BI platform and integrate its dashboards, APIs, SDKs, or frontend components into their own applications.



| Project                                                                  | Description                                                                                                                                                                       | Best Use                    |

| ------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------- |

| [Apache Superset](https://github.com/apache/superset)                    | Apache-licensed modern BI platform with dashboards, SQL exploration, visualization, APIs, and an official `@superset-ui/embedded-sdk` for embedding dashboards into applications. | ⭐ Embedded BI               |

| [Metabase](https://github.com/metabase/metabase)                         | Popular open-source BI platform with dashboards, questions, interactive analytics, APIs, and embedding capabilities.                                                              | ⭐ Embedded Dashboards       |

| [Lightdash](https://github.com/lightdash/lightdash)                      | Open-source BI platform built around dbt and a governed metrics layer, with dashboards, data apps, SDKs, and embedded analytics capabilities.                                     | ⭐ SaaS Embedded Analytics   |

| [Grafana](https://github.com/grafana/grafana)                            | Open-source observability and visualization platform supporting dashboards, panels, data sources, APIs, and application integration.                                              | ⭐ Embedded Dashboards       |

| [Redash](https://github.com/getredash/redash)                            | Open-source data visualization and dashboard platform supporting SQL queries, visualizations, dashboards, and APIs.                                                               | Embedded BI / SQL Analytics |

| [Evidence](https://github.com/evidence-dev/evidence)                     | Open-source code-based BI framework for building data products and analytics applications using SQL and Markdown-like components.                                                 | ⭐ Analytics Apps            |

| [Preset / Apache Superset](https://github.com/apache/superset)           | Superset-based open-source analytics stack suitable for self-hosted dashboards and application embedding.                                                                         | Embedded Superset           |

| [Helical Insight](https://github.com/helicalinsight/helicalinsight)      | Open-source BI platform supporting dashboards, reporting, data visualization, and embedding.                                                                                      | Embedded BI                 |

| [Knowage](https://github.com/KnowageLabs/Knowage-Server)                 | Open-source enterprise analytics and BI platform with dashboards, reporting, data integration, and analytical applications.                                                       | Enterprise BI               |

| [SpagoBI / Knowage](https://github.com/KnowageLabs/Knowage-Server)       | Open-source business-intelligence ecosystem that evolved into Knowage.                                                                                                            | Embedded / Enterprise BI    |

| [BIRT](https://github.com/eclipse-birt/birt)                             | Eclipse open-source reporting system for creating embedded reports and analytics in Java applications.                                                                            | Embedded Reporting          |

| [JasperReports](https://github.com/TIBCOSoftware/jasperreports)          | Open-source Java reporting engine capable of generating reports and integrating reporting functionality into applications.                                                        | Embedded Reporting          |

| [JasperReports Server](https://github.com/TIBCOSoftware/jasperreports)   | Reporting and BI infrastructure built around JasperReports for dashboards, reports, and application integration.                                                                  | Embedded Reporting          |

| [Pentaho Community Edition](https://github.com/pentaho/pentaho-platform) | Open-source-oriented BI platform with reporting, dashboards, data integration, and analytics capabilities.                                                                        | Enterprise BI               |

| [Cube](https://github.com/cube-js/cube)                                  | Open-source semantic layer and analytics API platform for building custom analytics applications and dashboards.                                                                  | ⭐ Headless BI               |

| [Rill Developer](https://github.com/rilldata/rill)                       | Open-source developer-focused BI platform for rapidly building dashboards and analytics on modern data infrastructure.                                                            | Developer BI                |

| [RisingWave](https://github.com/risingwavelabs/risingwave)               | Open-source streaming database that can serve as an analytics backend for real-time embedded dashboards.                                                                          | Real-Time Analytics Backend |

| [Vega](https://github.com/vega/vega)                                     | Open-source visualization grammar for creating interactive visualizations that can be embedded into web applications.                                                             | Visualization SDK           |

| [Vega-Lite](https://github.com/vega/vega-lite)                           | High-level declarative visualization grammar for building interactive charts and embedding them into applications.                                                                | Visualization SDK           |

| [Apache ECharts](https://github.com/apache/echarts)                      | Open-source JavaScript visualization library for highly customizable interactive charts and dashboards.                                                                           | ⭐ Visualization SDK         |

| [Plotly.js](https://github.com/plotly/plotly.js)                         | Open-source JavaScript graphing library for interactive data visualization.                                                                                                       | Visualization SDK           |

| [Chart.js](https://github.com/chartjs/Chart.js)                          | Open-source JavaScript charting library suitable for lightweight embedded dashboards and application analytics.                                                                   | Lightweight Charts          |

| [Highcharts](https://github.com/highcharts/highcharts)                   | JavaScript charting library suitable for embedded data visualization; licensing should be checked for commercial use.                                                             | Charting                    |

| [Apache Druid](https://github.com/apache/druid)                          | Open-source real-time analytics database suitable as a backend for high-performance embedded analytics applications.                                                              | Analytics Backend           |

| [ClickHouse](https://github.com/ClickHouse/ClickHouse)                   | Open-source analytical database designed for high-performance OLAP workloads and real-time analytics applications.                                                                | Analytics Backend           |

| [DuckDB](https://github.com/duckdb/duckdb)                               | In-process analytical database useful for local analytics applications, data apps, and embedded analytics.                                                                        | Embedded Analytics Database |



---



## 🧩 Open-Source Embedded Analytics Building Blocks



A proprietary Embedded BI platform is actually a combination of several layers.



Open-source software provides strong alternatives at almost every layer.



### 📊 Dashboard / BI Platforms



* [Apache Superset](https://github.com/apache/superset)

* [Metabase](https://github.com/metabase/metabase)

* [Lightdash](https://github.com/lightdash/lightdash)

* [Grafana](https://github.com/grafana/grafana)

* [Redash](https://github.com/getredash/redash)

* [Knowage](https://github.com/KnowageLabs/Knowage-Server)

* [Helical Insight](https://github.com/helicalinsight/helicalinsight)

* [Rill](https://github.com/rilldata/rill)

* [Evidence](https://github.com/evidence-dev/evidence)



### 🧠 Headless Analytics / Semantic Layer



* [Cube](https://github.com/cube-js/cube)

* [Lightdash](https://github.com/lightdash/lightdash)

* [Apache Superset](https://github.com/apache/superset)

* [Metabase](https://github.com/metabase/metabase)



These projects are especially interesting when building an **analytics API rather than simply embedding an existing dashboard**.



---



### 📈 Visualization SDKs



* [Apache ECharts](https://github.com/apache/echarts)

* [Vega](https://github.com/vega/vega)

* [Vega-Lite](https://github.com/vega/vega-lite)

* [Plotly.js](https://github.com/plotly/plotly.js)

* [Chart.js](https://github.com/chartjs/Chart.js)

* [D3.js](https://github.com/d3/d3)



These can be used to build a completely custom embedded-dashboard frontend.



---



### 🗄️ Analytics Databases



* [ClickHouse](https://github.com/ClickHouse/ClickHouse)

* [Apache Druid](https://github.com/apache/druid)

* [DuckDB](https://github.com/duckdb/duckdb)

* [PostgreSQL](https://github.com/postgres/postgres)

* [Trino](https://github.com/trinodb/trino)

* [Apache Pinot](https://github.com/apache/pinot)



---



## 🏗️ Embedded Analytics Architecture



A modern embedded analytics product can be structured as:



```text

                         SaaS Application

                                │

                                ▼

                     ┌─────────────────────┐

                     │ Embedded Analytics  │

                     │       Frontend      │

                     └──────────┬──────────┘

                                │

                  ┌─────────────┼─────────────┐

                  │             │             │

                  ▼             ▼             ▼

             Dashboards      Charts       Filters

                  │             │             │

                  └─────────────┼─────────────┘

                                ▼

                     ┌─────────────────────┐

                     │ Analytics API / SDK │

                     └──────────┬──────────┘

                                │

                                ▼

                     ┌─────────────────────┐

                     │ Semantic / Metrics  │

                     │       Layer         │

                     └──────────┬──────────┘

                                │

                                ▼

                     ┌─────────────────────┐

                     │ Analytics Database  │

                     └──────────┬──────────┘

                                │

              ┌─────────────────┼─────────────────┐

              ▼                 ▼                 ▼

         ClickHouse          Druid             DuckDB

```



---



## 🔐 Embedded Security Architecture



Multi-tenant SaaS products generally need to ensure that every customer sees only their own data.



```text

                    SaaS User

                        │

                        ▼

                 Application Auth

                        │

                        ▼

                 Tenant Identification

                        │

                        ▼

                Embed Token / JWT

                        │

                        ▼

              Embedded Analytics SDK

                        │

                        ▼

              Row-Level Security

                        │

                        ▼

                 Customer Dataset

```



Important embedded-analytics security mechanisms include:



* JWT / SSO authentication

* Tenant isolation

* Row-level security

* Attribute-based access control

* Signed embed tokens

* Short-lived tokens

* Server-side authorization

* Dataset-level permissions

* Dashboard-level permissions

* Audit logging



Apache Superset, for example, uses guest tokens for embedded resources and can apply row-level security rules to the embedded user.



---



## 🧱 Example Open-Source Embedded Analytics Stack



One possible fully self-hosted stack is:



```text

Frontend

   │

   ├── React

   ├── Vue

   └── Angular

        │

        ▼

Embedded Analytics

   │

   ├── Apache Superset

   ├── Metabase

   └── Lightdash

        │

        ▼

Semantic Layer

   │

   ├── Cube

   ├── dbt

   └── Lightdash

        │

        ▼

Analytics Database

   │

   ├── ClickHouse

   ├── Apache Druid

   ├── DuckDB

   └── PostgreSQL

        │

        ▼

Data Sources

   │

   ├── PostgreSQL

   ├── MySQL

   ├── Snowflake

   ├── BigQuery

   ├── S3

   └── APIs

```



---



## 🔌 Official Embedded SDK Examples



### Apache Superset



Superset provides an official JavaScript Embedded SDK:



```javascript

import { embedDashboard } from "@superset-ui/embedded-sdk";



embedDashboard({

  id: "dashboard-id",

  supersetDomain: "https://superset.example.com",

  mountPoint: document.getElementById("dashboard"),

  fetchGuestToken: () => fetchTokenFromBackend(),

});

```



The SDK supports application authentication through guest tokens and can be used to embed Superset dashboards inside another application.



### Metabase



Metabase provides embedding through web components and a React-based modular embedding SDK. Its SDK supports static, interactive, and editable dashboards.



```jsx

<InteractiveDashboard dashboardId={1} />

```



The modular SDK can be used with Metabase's self-hosted Open Source Edition for evaluation; some production embedding/SSO capabilities are plan-dependent.



### Lightdash



Lightdash provides an open-source BI platform with embedded analytics, SDKs, data apps, governed metrics, permissions, and row-level security capabilities.



---



## 🔍 Commercial vs Open-Source



| Capability                | Commercial Embedded BI |            Open-Source Stack |

| ------------------------- | ---------------------: | ---------------------------: |

| Dashboard Embedding       |                      ✅ |                            ✅ |

| Interactive Dashboards    |                      ✅ |                            ✅ |

| Charts                    |                      ✅ |                            ✅ |

| Filters                   |                      ✅ |                            ✅ |

| Drill-Down                |                      ✅ |                            ✅ |

| Dashboard Builder         |                      ✅ |                    ⚠️ Varies |

| White Label               |                    ⭐⭐⭐ |                           ⭐⭐ |

| Multi-Tenancy             |                    ⭐⭐⭐ |                            ✅ |

| Row-Level Security        |                      ✅ |                            ✅ |

| JWT / SSO                 |                      ✅ |                            ✅ |

| APIs                      |                      ✅ |                            ✅ |

| SDKs                      |                    ⭐⭐⭐ |                           ⭐⭐ |

| Semantic Layer            |                      ✅ |                            ✅ |

| AI Analytics              |    Increasingly common |                    ⚠️ Varies |

| Self-Hosting              |                 Varies |                          ⭐⭐⭐ |

| Source Code Access        |                      ❌ |                          ⭐⭐⭐ |

| Vendor Lock-in            |                 Higher |                        Lower |

| Customization             |                   High |                          ⭐⭐⭐ |

| Enterprise Support        |                    ⭐⭐⭐ |          Community / Vendors |

| Infrastructure Management |                    Low |                       Higher |

| Cost at Scale             |           Subscription | Infrastructure + Engineering |



---



## ⭐ Recommended Open-Source Options



If the goal is specifically to build an **open-source alternative to Luzmo, Reveal, Looker Embedded, GoodData, or Bold BI**, these are the strongest projects to investigate first:



1. **[Apache Superset](https://github.com/apache/superset)** — ⭐ strongest overall open-source embedded-dashboard platform.

2. **[Metabase](https://github.com/metabase/metabase)** — ⭐ excellent balance of usability, dashboards, APIs, and embedding.

3. **[Lightdash](https://github.com/lightdash/lightdash)** — ⭐ particularly attractive for modern SaaS products using dbt and a metrics layer.

4. **[Cube](https://github.com/cube-js/cube)** — ⭐ strong choice when you want a headless analytics API/semantic layer rather than a monolithic BI application.

5. **[Grafana](https://github.com/grafana/grafana)** — excellent for operational, monitoring, and real-time dashboards.

6. **[Evidence](https://github.com/evidence-dev/evidence)** — strong developer-first option for analytics applications.

7. **[Redash](https://github.com/getredash/redash)** — lightweight SQL-driven dashboards and visualization.

8. **[Helical Insight](https://github.com/helicalinsight/helicalinsight)** — open-source BI and embedded analytics option.

9. **[Knowage](https://github.com/KnowageLabs/Knowage-Server)** — enterprise-oriented open-source BI platform.

10. **[Rill](https://github.com/rilldata/rill)** — developer-centric BI for fast analytics applications.

11. **[Apache ECharts](https://github.com/apache/echarts)** — excellent foundation if you want to build your own dashboard UI.

12. **[Vega](https://github.com/vega/vega)** — powerful declarative visualization framework.

13. **[Plotly.js](https://github.com/plotly/plotly.js)** — flexible interactive visualization library.

14. **[Chart.js](https://github.com/chartjs/Chart.js)** — lightweight option for custom embedded dashboards.



---



## 💡 Two Different Open-Source Strategies



There are essentially **two ways to compete with commercial Embedded Dashboard SDKs**.



### Strategy 1 — Embed an Open-Source BI Platform



```text

Your SaaS

   │

   └── Embedded Apache Superset

          │

          ├── Dashboards

          ├── Filters

          ├── Charts

          ├── SQL

          └── RLS

```



Best projects:



* Apache Superset

* Metabase

* Lightdash

* Grafana

* Knowage

* Redash



### Strategy 2 — Build Your Own Analytics Product



```text

Your SaaS

   │

   ├── React / Vue

   │

   ├── Apache ECharts / Vega

   │

   ├── Cube

   │

   ├── dbt

   │

   └── ClickHouse

```



This approach gives substantially more control over:



* UX

* Branding

* Multi-tenancy

* Pricing

* Product workflows

* Permissions

* Dashboard configuration

* Data modeling

* AI features



It is also much closer to the architecture of a **developer-first Embedded Analytics company**.



---



## 🚧 Where Open Source Still Has Gaps



Commercial embedded analytics vendors can still have significant advantages in:



* Turnkey multi-tenancy

* White-labeling

* Customer-facing dashboard builders

* Embedded authorization

* Enterprise SSO

* Row-level security management

* Analytics-specific SDKs

* Product analytics UX

* Tenant provisioning

* Usage metering

* Customer analytics administration

* Embedded AI

* Support and SLAs

* Managed infrastructure

* Enterprise compliance



This creates a particularly interesting opportunity for open-source projects that combine:



```text

Open-Source BI

      +

Headless Semantic Layer

      +

Embedded SDK

      +

Multi-Tenancy

      +

Row-Level Security

      +

White Label

      +

AI Analytics

      =

Open-Source Embedded Analytics Platform

```



---



## 🤝 How to Contribute



Contributions are welcome! Please help expand this list with:



* Open-source embedded analytics platforms

* Open-source dashboard SDKs

* Open-source BI platforms with embedding

* Headless BI platforms

* Semantic layers

* Visualization SDKs

* Dashboard builders

* White-label analytics projects

* Multi-tenant analytics systems

* Row-level security implementations

* Embedded analytics APIs

* React/Vue/Angular analytics components

* Open-source analytics databases

* Developer-first BI projects



### Contribution Guidelines



1. Fork this repository.

2. Add the project to the appropriate section.

3. Prefer projects with an active repository and a clearly stated license.

4. Clearly distinguish **fully open-source**, **open-core**, **commercial**, and **hosted-only** products.

5. Do not classify a proprietary hosted service as open-source simply because it has an API or free tier.

6. Submit a pull request.



---



## ⚠️ Disclaimer



This repository is a **curated software directory**, not a product endorsement.



Licensing varies substantially between projects. Some projects listed here may use **open-source licenses, source-available licenses, or open-core models**, while certain enterprise/embedding capabilities may be commercially licensed.



Always verify the current license and embedding terms before incorporating a project into a commercial SaaS product.



**Last updated: August 2026**
