# Awesome-Game-User-Acquisition

Markdown
Copy
Copied
## Top Game User Acquisition Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Mobile Measurement Partners (MMPs), Attribution, UA Analytics, Fraud Protection & Campaign Optimization for Games*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Game User Acquisition**. These systems measure installs and in-app events, attribute campaigns across networks, protect against fraud, and help UA teams optimize spend and ROI for mobile games and apps.

**Examples** include AppsFlyer, Adjust, Singular, Branch, Kochava, Tenjin, AppsFlyer ROI360, Remerge, AppSamurai, and Liftoff (the category leaders).

**Open-source emphasis**: Full mobile measurement partners are almost entirely commercial. Practical open options include **OpenAttribution** (open-source MMP aims), privacy-first analytics tools, and self-hosted event tracking stacks. This section lists the strongest available open resources and is realistic about the gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[AppsFlyer](https://www.appsflyer.com/)**  
  Leading mobile measurement partner with extensive ad network integrations, advanced fraud protection, deep linking, and strong adoption among large gaming studios.

- **[Adjust](https://www.adjust.com/)**  
  MMP popular with gaming and European publishers, offering attribution, automation, CTV measurement, and fraud prevention focused on performance marketing.

- **[Singular](https://www.singular.net/)**  
  Marketing analytics and MMP platform known for cost aggregation, unified ROI reporting, and connecting spend data with attribution for UA optimization.

- **[Branch](https://www.branch.io/)**  
  Deep linking and attribution platform strong in web-to-app journeys, deferred deep links, and cross-platform measurement.

- **[Kochava](https://www.kochava.com/)**  
  Mobile attribution and analytics platform with fraud tools, CTV support, and flexible data ownership options used by gaming and hybrid-monetization apps.

- **[Tenjin](https://www.tenjin.io/)**  
  Cost-effective MMP and analytics platform popular with indie and mid-market game developers for attribution and UA reporting.

- **[AppsFlyer ROI360](https://www.appsflyer.com/)**  
  AppsFlyer’s ROI and cost-aggregation capabilities that unify media spend with attributed performance for UA decision-making.

- **[Remerge](https://www.remerge.io/)**  
  Mobile retargeting and re-engagement platform frequently used by games to bring users back and optimize post-install value.

- **[AppSamurai](https://appsamurai.com/)**  
  User acquisition and campaign management platform focused on mobile app and game growth, often used alongside MMPs.

- **[Liftoff](https://liftoff.io/)**  
  Mobile app marketing and programmatic UA platform that helps games acquire and engage users across channels.

## Open-Source GitHub Projects
- **[OpenAttribution](https://github.com/OpenAttribution/open-attribution)**  
  Open-source mobile measurement platform aimed at giving developers ownership of advertising and attribution data—impression/click tracking, event attribution, SDKs, and analytics components.

- **[Aptabase](https://github.com/aptabase/aptabase)**  
  Open-source, privacy-first analytics for mobile, desktop, and web apps—useful for product analytics and basic acquisition funnel visibility without traditional MMP lock-in.

- **[Self-hosted event and analytics stacks (PostHog, Plausible, etc.)](https://github.com/)**  
  Open product analytics platforms that can track installs and key events when full network-level attribution is not required.

- **[Open mobile SDKs for event tracking](https://github.com/)**  
  Community and first-party SDKs for sending install and in-app events to self-hosted backends.

- **[ClickHouse / open OLAP pipelines for attribution](https://github.com/)**  
  Open analytical databases and pipelines used by teams building custom attribution and UA reporting warehouses.

- **[Deep linking open libraries](https://github.com/)**  
  Open tools and patterns for deferred deep links and campaign parameter handling outside commercial deep-link platforms.

- **[Fraud and bot-detection open research tools](https://github.com/)**  
  Academic and community projects exploring install fraud signals (limited production parity with commercial MMP fraud suites).

- **[SKAdNetwork and privacy-preserving measurement open helpers](https://github.com/)**  
  Utilities and documentation projects supporting Apple’s privacy frameworks in custom measurement setups.

- **[UA dashboard open templates](https://github.com/)**  
  Open BI and dashboard templates for visualizing spend, installs, and ROAS from exported MMP or first-party data.

- **[Ad network postback and S2S open connectors](https://github.com/)**  
  Scripts and small services for receiving and normalizing network postbacks in self-hosted environments.

### Additional Strong Open-Source Options
- Evaluating **OpenAttribution** when data ownership and self-hosted MMP-style tracking are primary goals.
- Using **privacy-first open analytics** (Aptabase, PostHog, etc.) for product-side measurement while relying on commercial MMPs for paid UA attribution.
- Building custom attribution warehouses on open OLAP stacks fed by network postbacks and first-party events.
- Accepting that scale, ad network coverage, certified fraud protection, SKAN/ADvanced aggregation, and real-time UA optimization still favor commercial MMPs (AppsFlyer, Adjust, Singular, Kochava, Branch, Tenjin, etc.).
- Focusing open-source efforts on data ownership, privacy, and reducing dependency on third-party data processors.

**Frameworks for building custom systems**: Instrument apps with open or first-party SDKs → send events to a self-hosted backend → store and attribute in ClickHouse or similar → visualize in open BI tools → optionally feed selected events to a commercial MMP for network-level reporting. Suitable for privacy-focused or data-sovereign teams. Most game UA organizations rely on commercial MMPs for multi-network attribution and fraud defense.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- User acquisition and attribution systems process device and campaign data subject to privacy regulations (GDPR, CCPA, platform policies). Open-source or self-built measurement requires careful privacy design and compliance. This list is not legal or advertising advice.

---
**Made for game UA managers, growth teams, and mobile marketers measuring acquisition performance.**
Let's keep attribution transparent, privacy-aware, and as open as practical.
