# Hi, I'm Pedro Jose

**Field CTO Telecom EMEA @ Snowflake**

I build end-to-end data platforms and AI-powered solutions for telecom operators across EMEA and LATAM, leveraging Snowflake's ecosystem -- Cortex AI, Streamlit, Snowpark, MCP, A2A, and Data Sharing.

---

## Flagship Demo

| | |
|---|---|
| **Repo** | [SnowTelco -- Snowflake Intelligence for Telecom](https://github.com/pmjose/Snowflake_AI_Demo_Generic_Telco_streamlit) |
| **Operator** | SnowTelco Group PLC (fictional UK telco) |
| **Coverage** | UK -- 30K+ subscribers, 475 sites, 1,720 cells |
| **Scale** | 38 semantic views, 16M+ records, 66 policy documents, 100+ tables, ~1.5 GB |
| **Business Use Cases** | Executive natural-language Q&A across all business domains (CEO, CFO, CMO, CTO, COO + 17 VP personas), revenue & ARPU analysis, churn prediction, network performance monitoring, SLA tracking, marketing ROI, partner/wholesale management, ESG reporting, HR analytics, legal/compliance, fraud detection |
| **Key Features** | 28 demo scripts, 182 test questions, 40+ persona Streamlit dashboard, SnowCRM React app with A2A chat, MCP Server + A2A protocol, TM Forum ODA alignment, one-click SQL installation, multi-year data (2024-2026) |
| **Stack** | `Cortex Agent` `Cortex Analyst` `Cortex Search` `Semantic Views` `MCP` `A2A` `Streamlit` `React` `TypeScript` |

---

## Customer-Specific Data Platforms

| Repo | Operator | Region | Business Use Cases | Coverage & Scale | Stack |
|------|----------|--------|-------------------|-----------------|-------|
| [**BICS Monetization**](https://github.com/pmjose/BICS_monetization) | BICS (Proximus Belgium) | Belgium | Roaming mobility analytics (visitor flows, dwell time, origin/destination), IoT intelligence across 5 verticals (Agriculture, Healthcare, Manufacturing, Transport, OEM), H3 geospatial heatmaps, Cortex Analyst natural-language queries | 4.2M+ roaming records, 3 Belgian regions (Brussels, Wallonia, Flanders), multi-page Streamlit app | `Streamlit` `Cortex Analyst` `H3` `Semantic Models` |
| [**Transatel**](https://github.com/pmjose/Transatel) | Transatel (NTT) | France / Global | MVNO network intelligence, ML anomaly detection (Isolation Forest), IoT analytics across 5 verticals (Automotive, Aviation, Manufacturing, Logistics, Energy), data product marketplace via Snowflake Data Sharing | 30 MNO partners, 7-page Streamlit dashboard, CARTO geospatial maps | `Snowpark ML` `Isolation Forest` `Streamlit` `CARTO` `Data Sharing` |
| [**PremiumFiber**](https://github.com/pmjose/PremiumFiber) | PremiumFiber (Spain) | Spain | Snowflake Intelligence for FTTH provider -- executive Q&A (CEO/CFO/COO/CMO personas), subscriber growth, network coverage, competitive analysis, XGS-PON fiber operations | 12M+ homes passed, Cortex Agent with structured + unstructured data grounding | `Cortex Agent` `Cortex Search` `Snowflake Intelligence` |
| [**TDF**](https://github.com/pmjose/TDF) | TDF (France) | France | Towerco data platform -- executive dashboards, ESG/CSRD reporting, digital twin with 3D tower visualization, CAPEX lifecycle management, site inventory & maintenance | 8,785 sites, 7,877 towers, 10 schemas, PyDeck maps, Plotly 3D scatter, Graphviz dependency graphs | `Streamlit` `PyDeck` `Plotly 3D` `Graphviz` `ESG/CSRD` |
| [**WOM**](https://github.com/pmjose/WOM) | WOM Chile | Chile | Snowflake Intelligence for mobile + fiber telecom -- subscriber metrics, revenue & ARPU, 5G rollout status, churn analysis, marketing ROI, competitive positioning (vs Claro, Entel). Personas: CEO, CFO, COO/CTO, CMO | Chile's 2nd-largest mobile operator, 5G network, 7,000+ km fiber, currency CLP | `Cortex Agent` `Cortex Search` `Snowflake Intelligence` |
| [**MiFibra**](https://github.com/pmjose/MiFibra) | MiFibra Peru | Peru | Snowflake Intelligence for fiber ISP -- subscriber metrics, ARPU, plan adoption (500Mbps-5000Mbps), churn by plan/region, marketing campaigns, competitive analysis (vs Claro, Movistar). Personas: CEO, CFO, COO/CTO, CMO | Peru's fastest ISP (Ookla certified), 100% XGS-PON fiber, residential + business segments, currency PEN (Soles) | `Cortex Agent` `Cortex Search` `Snowflake Intelligence` |
| [**Marlink**](https://github.com/pmjose/Marlink) | Marlink | Global / Maritime | Maritime connectivity analytics for satellite/hybrid network fleet | Streamlit app with Cortex plans | `Streamlit` `Cortex` |
| [**Telit Supply Chain**](https://github.com/pmjose/Telit-Supply-Chain) | Telit Cinterion | Global / IoT | IoT/cellular module supply chain intelligence -- executive KPIs, sales & demand forecasting, inventory optimization, factory OEE, logistics & carrier performance, supplier scorecards, quality & certifications, product lifecycle (NPI to EOL), returns/RMA, finance, ESG/carbon tracking | 15+ dashboard pages, 3D product visualization of 6 module types (FN990A 5G, ME310G1 Cat-M1, etc.), discovery call demo | `Streamlit` `Plotly` `3D Visualization` |

---

## Operator-Branded Snowflake Intelligence Demos

Each demo includes a Cortex Agent with 12 tools (4 Cortex Analyst semantic views + 6 Cortex Search services + web scraper + email), 20+ tables, 60+ documents, 25 audio files, and Streamlit apps.

| Repo | Operator | Region | Type | Business Use Cases | Key Data |
|------|----------|--------|------|-------------------|----------|
| [**VMO2**](https://github.com/pmjose/Snowflake_AI_Demo_VMO2) | Virgin Media O2 | UK | Converged (Mobile + Cable) | Converged subscriber analytics (Volt bundles), 5G coverage, fixed vs mobile network performance, ARPU by service type, churn, competitive analysis (vs BT, Sky) | 5.69M fixed broadband, 34.7M mobile, 2.84M Volt customers, GBP |
| [**CityFibre v2**](https://github.com/pmjose/Snowflake_AI_Demo_CityFibre_v2) | CityFibre | UK | Full-Fibre Infrastructure (Wholesale) | FTTP subscriber & take-up by region, B2B/B2G revenue, XGS-PON utilization, wholesale partner performance, WiFi assurance, 5G backhaul, Project Gigabit | UK city-level subs, B2C bundles, B2B CRM, infrastructure POPs, GBP |
| [**Eutelsat v2**](https://github.com/pmjose/Snowflake_AI_Demo_Eutelsat_v2) | Eutelsat Group | Global (HQ Paris) | Satellite (GEO + LEO) | Multi-orbit fleet management (35 GEO + 600+ OneWeb LEO), broadcast reach (~7,000 TV channels, 274M homes), vertical analysis (Broadcast, Aviation, Maritime, Government, Enterprise/Backhaul), investor updates, ESG/responsible space | Revenue by segment, capacity utilization, SLA adherence, EUR |
| [**Gamma**](https://github.com/pmjose/Snowflake_AI_Demo_Gamma) | Gamma Communications | UK | UCaaS / Business Comms | Revenue mix analysis, subscriber growth, network coverage, competitive positioning, B2B pipeline, marketing campaigns | Finance, sales, marketing, strategy docs, GBP |
| [**Cubic**](https://github.com/pmjose/Snowflake_AI_Demo_Cubic) | Cubic Telecom (Cubic³) | Global (190+ countries) | Connected Vehicles / SDV | Global connectivity KPIs (latency, throughput, attach success, roaming) by OEM/country/vehicle program, driver support sentiment, OTA rollout quality, Explore³ insights, StreamLocal³ adoption, eSIM activation | 17M+ vehicles, OEM programs, MNO partnerships, EUR |
| [**PXC**](https://github.com/pmjose/Snowflake_AI_Demo_PXC) | PlatformX Communications | UK | Wholesale Telecom Platform | Ethernet/optical backhaul circuit performance, partner revenue (reseller, carrier, SI, alt-net), product mix (Connectivity, Voice & Collaboration, Cloud & Security), managed security attach rates, 1Portal order automation, NPS | UK nationwide, 99.995% SLA, partner ecosystem, GBP |
| [**Virgin Media Ireland**](https://github.com/pmjose/Snowflake_AI_Demo_VMIE) | Virgin Media Ireland | Ireland | Cable / Broadband / MVNO | Broadband/TV/voice/mobile (MVNO) subscriber totals, 5G penetration, B2C bundle analysis (WiFi Guarantee, TV 360), B2B revenue, marketing ROI, MVNO host interconnect utilization | Dublin, Cork, Limerick, Galway city-level data, EUR |
| [**Generic Telco v1**](https://github.com/pmjose/Snowflake_AI_Demo_Generic_Telco) | Generic | -- | Template | Original generic telco AI demo template (predecessor to SnowTelco) | 1 fork |
| [**Mobile + Fiber Intelligence**](https://github.com/pmjose/Snowflake_Intelligence_AI_mobile_fiber) | Generic | -- | Mobile + Fiber | Generic Snowflake Intelligence demo for mobile/fiber operators | -- |

---

## Agentic AI & Integrations

| Repo | Description | Business Use Cases | Coverage & Scale | Stack |
|------|------------|-------------------|-----------------|-------|
| [**MWC Prodapt 2026 v2**](https://github.com/pmjose/MWC_Prodapt-2026-v2) | Agentic Assurance demo for MWC Barcelona 2026 with Prodapt | Network assurance -- ServiceNow Assurance Agent orchestrates live event detection, root cause analysis, and remediation via Snowflake MCP. A2A Protocol exposes Cortex Agent for multi-agent interoperability | 2M+ KPI records, 13 tables, 15 views (Radio/Core/Transport KPI, incidents, anomaly scores). PAT, JWT Key-Pair, OAuth auth | `MCP Server` `A2A` `Cortex Agent` `ServiceNow` |
| [**MWC Prodapt 2026 v1**](https://github.com/pmjose/MWC_Prodapt-2026) | First version of MWC Prodapt agentic assurance demo | Network assurance via MCP + Cortex Agent | Predecessor to v2 | `MCP` `Cortex Agent` |
| [**Cortex Agent A2A**](https://github.com/pmjose/cortex_agent_a2a) | Google Agent-to-Agent (A2A) protocol wrapper for Snowflake Cortex Agents. *Forked from sfc-gh-tjia* | Expose any Cortex Agent as an A2A-compatible endpoint for multi-agent interoperability. Agent discovery + message passing | Python server, REST endpoints | `A2A Protocol` `Cortex Agent` `Python` |
| [**Customer Digital Twin**](https://github.com/pmjose/Customer-Digital-Twin) | AI-powered customer persona simulation for "Snowmobile Wireless" (fictional US carrier) | Marketing simulation -- 8 AI personas (Value Seekers, Data Streamers, Family Connectors, Steady Loyalists, Premium Techies, Rural Reliables, Young Digitals, At-Risk Defectors) simulate reactions to pricing changes, product launches, campaigns. K-Means clustering, Cortex LLM (llama3.1-70b) | 28M subscribers, 17.8M records, ~3.4 GB, 3-hour lab workshop, Streamlit UI | `Cortex LLM` `Snowpark ML` `K-Means` `Streamlit` `Jupyter` |

---

## Telco Use Case Library

| Repo | Use Case | Business Use Cases | Stack |
|------|----------|-------------------|-------|
| [**UC1 - Network Operations**](https://github.com/pmjose/UC1-Network-Operations) | Real-time network monitoring | 4 Streamlit dashboards (Engineering, Operations Manager, Executive, Snowflake Intelligence), 450 sites, ~600K performance records, ML anomaly detection, capacity forecasting, MTTD/MTTR tracking, SLA monitoring, CAPEX/OPEX analysis. Portuguese 4G/5G network data. Cortex Agent for natural language queries | `Streamlit` `Cortex Agent` `Cortex Analyst` `Semantic Views` `Plotly` `Graphviz` |
| [**UC2 - Predictive Maintenance**](https://github.com/pmjose/UC2-Predictive-and-Preventive-Maintenance) | Predictive & preventive maintenance | ML-driven maintenance scheduling, equipment failure prediction, work order optimization | `Snowpark ML` `Streamlit` |
| [**UC3 - Sentiment Analysis**](https://github.com/pmjose/UC3-Customer-Complaints-Sentiment-Analysis) | Customer complaints NLP | Sentiment scoring pipeline, complaint categorization, trend analysis, customer satisfaction tracking | `Cortex LLM` `Streamlit` |
| [**UC4 - Customer Journey C360**](https://github.com/pmjose/UC4-Customer-Journey-C360) | Customer 360 & journey mapping | Cross-touchpoint journey mapping, churn risk scoring, segmentation, lifetime value analysis | `Streamlit` `Snowpark` |

<details>
<summary>Earlier versions of use cases</summary>

| Repo | Notes |
|------|-------|
| [UC1 - Network Operations (v1)](https://github.com/pmjose/UC1---Network-Operations) | Earlier version |
| [UC2 - Predictive Maintenance (v1)](https://github.com/pmjose/UC2---Predictive-and-Preventive-Maintenance) | Earlier version |
| [UC4 - Customer Journey C360 (v1)](https://github.com/pmjose/UC4---Customer-Journey---C360) | Earlier version |

</details>

---

## Tools & Utilities

| Repo | Description | Use Case |
|------|------------|----------|
| [**Lucid Architecture**](https://github.com/pmjose/lucid-architecture) | Cortex Code plugin for Snowflake-branded draw.io architecture diagrams. *Forked from lbandini* | Auto-generate architecture diagrams from Snowflake deployments |
| [**Fusion Dataset**](https://github.com/pmjose/Fusion_dataset) | Fusion dataset | Data asset |
| [**Snowflake AI Demo (original)**](https://github.com/pmjose/Snowflake_AI_DEMO) | Original Snowflake AI demo. *Forked from NickAkincilar* | Reference implementation |
| [**SnowPro Core Study Notes**](https://github.com/pmjose/snowflake-snowpro-core-study-notes) | SnowPro Core Certification study notes. *Forked from Infostrux-Solutions* | Certification prep |
| [**snowflake**](https://github.com/pmjose/snowflake) | Base Snowflake repo | Misc |

---

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| **Data Platform** | Snowflake, Snowpark Python, Dynamic Tables, Streams & Tasks |
| **AI & ML** | Cortex AI (Analyst, Search, Agents), Snowflake Intelligence, Snowpark ML, Cortex LLM Functions |
| **Protocols** | Model Context Protocol (MCP), Agent-to-Agent (A2A), TM Forum ODA |
| **Visualization** | Streamlit in Snowflake, Plotly, PyDeck, CARTO, Graphviz |
| **Data Sharing** | Secure Views, Semantic Views, Data Products, Marketplace Listings |
| **Languages** | Python, SQL, TypeScript |

---

## Operator Coverage

| Segment | Operators |
|---------|----------|
| **Towercos & Infrastructure** | TDF (France), CityFibre (UK), PremiumFiber (Spain) |
| **Mobile & Fixed** | VMO2 (UK), Gamma (UK), Virgin Media Ireland, WOM (Chile), MiFibra (Peru) |
| **Wholesale & IoT** | BICS (Belgium), Transatel/NTT (France), PXC (UK), Telit Cinterion (Global) |
| **Connected Vehicles** | Cubic Telecom / Cubic³ (Global -- 190+ countries, 17M+ vehicles) |
| **Satellite & Maritime** | Eutelsat (Global -- GEO + LEO), Marlink (Global) |
| **Systems Integrators** | Prodapt (MWC Barcelona 2026) |

---

*35 repositories and counting*
