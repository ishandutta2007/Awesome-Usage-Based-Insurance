# Awesome-Usage-Based-Insurance

# Top Usage-Based Insurance (UBI) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Mobile & Hardware Telematics, Driver Behavior Scoring, Risk Assessment, Crash Detection, Mileage Tracking & Pay-How-You-Drive Pricing*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Usage-Based Insurance (UBI)**. These systems collect driving data via smartphone sensors or connected hardware, analyze behavior (harsh braking, acceleration, speeding, phone use, mileage), generate risk scores, and enable personalized insurance pricing and safety coaching.

**Examples** include Cambridge Mobile Telematics, Arity, Octo Telematics, Zendrive, DriveQuant, Greater Than, TrueMotion, IMS, Mojio, and Scope Technology (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for telematics data pipelines, driver behavior analysis, smartphone sensor scoring, OBD-II/fleet analytics, and UBI proof-of-concept systems — ideal for insurers, mobility startups, researchers, and developers seeking transparent alternatives or building blocks.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Cambridge Mobile Telematics (CMT)](https://www.cmtelematics.com/)**  
  Leading AI-powered mobile telematics platform providing driving risk assessment, crash detection, driver coaching, and claims support for insurers and mobility providers.

- **[Arity](https://www.arity.com/)**  
  Allstate-backed mobility data and analytics company specializing in driving behavior insights and telematics solutions for insurance and transportation.

- **[Octo Telematics](https://www.octotelematics.com/)**  
  Global insurance telematics provider offering both hardware and smartphone-based solutions for UBI, risk scoring, and claims management.

- **[Zendrive](https://www.zendrive.com/)**  
  Smartphone-based telematics and driver safety platform focused on behavior scoring, distraction detection, and fleet/insurance applications.

- **[DriveQuant](https://www.drivequant.com/)**  
  Mobile telematics SDK and analytics platform that delivers driving scores, trip analysis, and safety insights for insurers and mobility services.

- **[Greater Than](https://www.greaterthan.eu/)**  
  AI-driven driver risk scoring and predictive analytics platform used by insurers for underwriting and portfolio management.

- **[TrueMotion (Cambridge Mobile Telematics)](https://www.cmtelematics.com/)**  
  Mobile sensing and telematics technology (now part of the broader CMT ecosystem) known for accurate smartphone-based driving measurement.

- **[IMS](https://www.ims.tech/)**  
  Insurance telematics and mobility solutions provider offering data collection, analytics, and UBI program support.

- **[Mojio](https://www.mojio.com/)**  
  Connected-car platform providing telematics data, vehicle insights, and insurance-oriented services via OEM and aftermarket integrations.

- **[Scope Technology](https://www.scopetechnology.com/)**  
  Telematics and UBI solution provider focused on data analytics and insurance applications, particularly strong in certain regional markets.

## Open-Source GitHub Projects
- **[Telematics UBI Pipeline (end-to-end POC)](https://github.com/AjaySreekumar47/Sreekumar_Ajay_TelematicsUBI)**  
  Full open-source telematics UBI pipeline covering event ingestion, ETL, feature engineering, claim prediction, driver risk scoring, and a Streamlit dashboard.

- **[Siphyy](https://github.com/surajit003/siphyy)**  
  Open-source agentic framework for fleet telematics analytics, including driver behavior intelligence, anomaly detection, and provider-agnostic canonical schemas.

- **[TeleDrive](https://github.com/sharansergio-creator/TeleDrive)**  
  On-device AI driving behavior analysis using smartphone sensors and TensorFlow Lite — detects harsh events with no cloud dependency.

- **[Fleet Management / Automotive Telematics systems](https://github.com/)**  
  Open-source platforms with OBD-II diagnostics, GPS tracking, driver behavior monitoring, safety scoring, and live dashboards suitable for UBI-style use cases.

- **[DriverMonitor and similar sensor fusion projects](https://github.com/)**  
  Research and prototype systems combining OBD-II, smartphone, and wearable data for real-time driving performance and risk monitoring.

- **[CANcloud & open CAN/OBD telematics tools](https://github.com/)**  
  Open-source tools for managing CAN loggers, visualizing vehicle data, and building custom telematics pipelines.

- **[Open Vehicles (OVMS)](https://www.openvehicles.com/)**  
  Fully open-source vehicle monitoring, diagnostics, and control system with strong telematics and fleet-oriented capabilities.

- **[Zenroad and reference telematics apps](https://github.com/)**  
  Open-source mobile reference applications demonstrating smartphone-based mileage tracking and telematics SDKs.

- **[Vehicle telematics analysis notebooks](https://github.com/)**  
  Projects focused on gear detection, fuel efficiency, sharp-turn detection, and driving pattern analysis from sensor data.

- **[Kafka/OBD-II telematics hubs](https://github.com/)**  
  Event-driven open-source pipelines for ingesting OBD-II and GPS data, computing driving scores, and supporting insurance/fleet analytics.

### Additional Strong Open-Source Options
- Smartphone sensor libraries and activity-recognition frameworks that can feed custom scoring models.
- Open OBD-II readers, CAN decoders, and diagnostic tools.
- Time-series databases + Grafana/Metabase dashboards for trip and score visualization.
- Machine-learning notebooks for risk modeling (frequency/severity prediction) on public or synthetic telematics datasets.
- Privacy-preserving techniques and on-device inference examples for compliant UBI scoring.

**Frameworks for building custom systems**: Collect data via smartphone sensors or OBD-II/open hardware, normalize events into a canonical schema (as in **Siphyy** or custom ETL), engineer features (harsh events, speed profiles, time-of-day, mileage), train or apply open risk models, and surface scores via dashboards or APIs. Use **TeleDrive**-style on-device models for privacy-sensitive deployments. Combine with open mapping and trip segmentation libraries for full trip context.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Usage-based insurance involves highly sensitive personal location and behavior data. Any system must comply with strict privacy, consent, data-protection, and insurance-regulatory requirements in the relevant jurisdictions.
- Open-source components are valuable for research, prototyping, and internal analytics but are not substitutes for certified, actuarially validated commercial UBI platforms used in regulated insurance pricing.
- Always prioritize transparency, user consent, and security when handling telematics data.

---
**Made for insurers, mobility innovators, fleet operators, and developers exploring fairer, data-driven insurance models.**
Let's make usage-based insurance more transparent, privacy-aware, and openly innovable.
