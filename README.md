# Awesome-Manufacturing-Execution-System

## Top Manufacturing Execution System (MES) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Shop-Floor Execution, Production Tracking, Traceability, OEE, Quality, Work-Order Management & Real-Time Manufacturing Visibility*  

**Last updated: September 2026**



This repository tracks notable **SaaS / commercial platforms** and **open-source projects** for **Manufacturing Execution Systems (MES)**. These systems bridge ERP and the shop floor—managing work orders, tracking production in real time, enforcing process steps, capturing genealogy/traceability, monitoring OEE, and supporting quality and compliance.



**Examples** include Tulip, Sepasoft, Siemens Opcenter, GE Digital / Proficy, AVEVA MES, Rockwell FactoryTalk ProductionCentre, Critical Manufacturing, 42Q, Forcam, MPDV HYDRA, DELMIA Apriso, Parsec TrakSYS, Aegis FactoryLogix, and Plex MES (the category leaders).



**Open-source emphasis**: Full-featured enterprise MES platforms remain predominantly commercial. Open-source options have grown for small-to-mid-size manufacturers—led by **OpenMES**, **Carbon** (ERP+MES+QMS), and earlier projects such as **mes4u**. This section lists every significant active project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Tulip](https://tulip.co/)**  

  No-code / low-code frontline operations platform for building shop-floor apps, digital work instructions, production tracking, quality, and traceability without traditional MES complexity.



- **[Siemens Opcenter](https://www.sw.siemens.com/)**  

  Comprehensive manufacturing operations management suite covering execution, quality, scheduling, and integration within the Siemens digital enterprise portfolio.



- **[Rockwell FactoryTalk ProductionCentre / FactoryTalk MES](https://www.rockwellautomation.com/)**  

  MES solutions tightly integrated with Rockwell automation hardware and FactoryTalk ecosystem for discrete and process manufacturing.



- **[AVEVA MES, GE Proficy / Plant Applications, DELMIA Apriso](https://www.aveva.com/)**  

  Established enterprise MES platforms supporting production execution, genealogy, performance management, and industry-specific workflows.



- **[Critical Manufacturing, 42Q, Forcam, MPDV HYDRA, Parsec TrakSYS, Aegis FactoryLogix, Plex](https://www.criticalmanufacturing.com/)**  

  Specialized and cloud-native MES offerings for high-tech, electronics, automotive, and multi-plant discrete manufacturing.



- **[Sepasoft MES (Ignition)](https://inductiveautomation.com/)**  

  MES modules built on the Ignition platform, popular for flexible, SCADA-integrated production tracking and OEE.



- **[Other commercial MES & MOM platforms](https://tulip.co/)**  

  Additional solutions covering paperless manufacturing, real-time visibility, and industry 4.0 execution layers.



## Open-Source GitHub Projects



- **[OpenMES](https://github.com/Mes-Open/OpenMes)**  

  Modern open-source Manufacturing Execution System aimed at small and mid-sized manufacturers. Self-hosted, tablet-ready, with production tracking, work orders, quality, and traceability (AGPL-3.0). Live demos available.



- **[Carbon](https://github.com/crbnos/carbon)**  

  Open-source ERP + MES + QMS platform designed for complex assembly, contract manufacturing, high-volume, and configure-to-order environments. API-first with lot/serial traceability, nested BOMs, and shop-floor execution.



- **[mes4u (Sindoh)](https://github.com/sindohmes/mes4u)**  

  Web-based open-source MES developed from real manufacturing-site experience. Provides core shop-floor functions and master data; built with Spring Boot and Vue.js (LGPL).



- **[Other open MES / shop-floor projects](https://github.com/search?q=MES+OR+%22manufacturing+execution%22+open+source)**  

  Community and experimental systems for production tracking, work-order management, and basic OEE for smaller manufacturing environments.



- **[OEE & production monitoring open tools](https://github.com/search?q=OEE+OR+overall+equipment+effectiveness+open+source)**  

  Libraries and dashboards focused on calculating and visualizing Overall Equipment Effectiveness from machine or manual data.



- **[SCADA / IIoT open stacks used with MES](https://github.com/search?q=Ignition+OR+OpenSCADA+OR+Node-RED+manufacturing)**  

  Open or open-core industrial platforms frequently paired with custom MES logic for data collection and visualization.



- **[Traceability & genealogy helpers](https://github.com/search?q=lot+tracking+OR+serial+genealogy+manufacturing)**  

  Open components for lot/serial tracking that can be integrated into custom execution systems.



- **[Workflow & digital work-instruction tools](https://github.com/search?q=digital+work+instructions+OR+shop+floor+app)**  

  Open or low-code frameworks used to digitize operator procedures and capture production data.



### Additional Strong Open-Source Options



- **OpenMES**: Purpose-built free MES for smaller shops seeking self-hosted production control.

- **Carbon**: Broader open manufacturing suite (ERP+MES+QMS) for more complex discrete operations.

- **mes4u**: Mature core functions derived from industrial use.

- **Composable stacks**: Machine data (OPC-UA/MQTT) + Node-RED or Ignition + custom database + open dashboards for lightweight execution visibility.

- **OEE-focused tools**: Open calculators and Grafana/Influx stacks for performance monitoring without full MES.

- Hybrid approaches: Open MES core + commercial SCADA/PLC integration or cloud analytics.



**Frameworks for building custom systems**:  

**OpenMES** and **Carbon** are the strongest current open-source MES options for small-to-mid-size manufacturers.  

**mes4u** provides another solid foundation based on real factory experience.  

These can deliver work-order tracking, basic traceability, and production visibility without license fees.  

Enterprise MES platforms (Siemens Opcenter, Rockwell, AVEVA, GE, Tulip, Critical Manufacturing, etc.) offer deeper industry templates, validated compliance, multi-plant scalability, tight automation integration, and professional support that large and regulated manufacturers typically require.  

Many smaller manufacturers start with open-source or lightweight platforms; larger organizations usually standardize on commercial MES/MOM suites, sometimes augmenting them with open tools for specific lines or analytics.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- MES systems sit at the core of production control and often support regulated industries (medical devices, automotive, aerospace, food). Incorrect configuration or data gaps can affect product quality, compliance, and safety.

- Open-source MES solutions offer transparency and zero licensing cost but require internal expertise for deployment, validation, integration with PLCs/SCADA/ERP, and ongoing maintenance. Evaluate regulatory needs, validation effort, and total cost of ownership carefully before production use.



---



**Made for manufacturing engineers, operations leaders, digital transformation teams, and shop-floor technologists.**  

Let's expand accessible, open tools for production execution while recognizing the depth, compliance support, and scale that mature commercial MES platforms deliver.
