# TechSaints.dev — Open-Source Tooling

**Catholic technologists, creatives, and builders advancing the Church’s mission through **open, interoperable software**.**

[![License: Apache-2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

---

## 🌟 Vision
The Catholic Church faces fragmentation in technology: siloed data, duplicated parishioner onboarding, and limited integration with modern digital tools. **TechSaints.dev** unites builders worldwide to create tools that embody the Church’s mission while solving real-world pain points.

Our work is open source, community-driven, and aligned with Catholic values of stewardship, collaboration, and service.


## 🔥 Call to Action
> “The mission of the Church is to proclaim His presence and to serve Him.”  

By building interoperable, open tools, we make parish life **welcoming, connected, and future-ready**. 

**Join The Mission and let's build!**



## Catalog Overview

### Categories
1. **Identity & Data Standards** — interoperability, SSO, canonical schemas  
2. **Parish & Faith Community Platforms** — parishioner/parish apps and profiles  
3. **AI & Content Tools** — Catholic-aligned AI (verification, catechesis, summarization)  
4. **Giving & Marketplace Integrations** — donations, vendor tithing, financial plumbing  
5. **Community & Collaboration** — prayer, events, contributor hub

**Legend** — 
- Type: spec, library, service, ext
- Stage: 
   - Incubating ▢  
   - Beta ◧ 
   - Stable ●  
   - **HP**: High-Potential

| Category | Product | Type | Problem Solved | Stage | HP |
|---|---|---|---|:---:|:--:|
| Identity & Data Standards | PIEP (Parishioner & Ecclesial Identity Protocol) | spec + ref services | Lack of data portability; SSO + canonical schemas | ◧ | ✅ |
| Parish & Faith Community | CatholicProfile.com (built on PIEP) | SaaS app + APIs | Single source of truth (members, sacraments, giving) | ▢ |  |
| AI & Content Tools | CatholicCheck | ext + API | “Grammarly for Catholic content” with sources | ▢ | ✅ |
| AI & Content Tools | CateContent | service + CLI | Summarize/auto-create bulletins & catechesis with citations | ▢ |  |
| Giving & Marketplace | TechTithe | microservice | % of subscription/checkout routed to a parish | ▢ | ✅ |
| Community & Collaboration | TechSaints.dev Hub | web portal | Contributor onboarding, docs, partner directory | ◧ |  |
| Community & Collaboration | Prayer Feed | service + widget | Shared prayer intentions with privacy tiers | ▢ |  |
| Community & Collaboration | Event & Resource Listings | service | Central calendar + resources with tags/iCal | ▢ |  |

---

## Getting Started

1. Clone the repo:  
   ```bash
   git clone https://github.com/techsaints/tooling.git
   cd tooling
   ```
2. Review `docs/ROADMAP.md` and `docs/ARCHITECTURE.md`.
3. Pick an issue labeled `good first issue` or `help wanted`.
4. See `CONTRIBUTING.md` for development flow and style.

---

## Governance & Community

- **Steering Committee (Core Team):** sets vision, approves new projects.  
- **Maintainers (per project):** triage, review, release.  
- **Contributors:** anyone filing issues, PRs, or docs.  
- **SIGs/Working Groups:** focused initiatives (PIEP, AI, Giving).  

See `GOVERNANCE.md` for full details.

---

## Security

If you discover a vulnerability, **do not open a public issue**.  
Email: **security@techsaints.dev**. See `SECURITY.md`.

---

Contact: [Rhyan.dev](https://rhyan.dev)

## License

Apache License 2.0 — see `LICENSE`.

---
