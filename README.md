
SMG IP Hub Estimation

# Overview

These estimations cover the requested changes for IPGO and OPE platforms.
Before reading please note that the IPGO and OPE current system was never designed to handle this level of complex integration between IPGO-OPE nor the many sensitive new features. It is highly likely a fully custom backend needs to be re-written. Directus might suffice but development speed might be slower over time and less flexibility intermf of admin UI. Include a buffer of 1-1.5months for a potential backend rewrite.

# Key Assumptions Behind These Numbers

- Team: 2 internal developers + occasional light outsourcing
- All features are treated as small, isolated additions on top of a stable existing codebase
- No technical debt (we expect some in OPE Springboot)
- No real security audit, penetration testing, or load testing
- Legal review is treated as a quick rubber-stamp (in reality, features like contracts, royalties, and disputes need months of lawyer time)
- No proper UX/UI design phase — everything uses existing components
- Multi-language, multi-currency, payment gateways, e-signature APIs, etc. “just work” with minimal effort
- Wonder Festival / EXPO app (Spring Boot + React Native) integration goes well.
- Client gives instant feedback and never changes requirements
- Zero holidays, zero scope creep, zero bugs that take days to debug

#### These are best-case, minimum-possible numbers you can show the client so they can pick features.

# Features work estimations

| # | Foundational & Common Feature | Dev Effort | PM / Sync | Testing | Legal Review |
|---|-------------------------------|------------|-----------|---------|--------------|
| 1 | Bug fixes & UX polish (all Appendix 1) | 0.25 mo | 0.25 mo | 0.25 mo | 0 mo |
| 2 | Stable SSO + role switching without logout bugs | 0.25 mo | 0.25 mo | 0.25 mo | 0.25 mo |
| 3 | Unified dashboard with role-based UI auto-change | 0.25 mo | 0.25 mo | 0.25 mo | 0 mo |
| 4 | Real-time data sync across all three sites + cross-promotion | 1.25 mo | 0.3 mo | 0.4 mo | 0.1 mo |
| 5 | Integrated notification system | 0.75 mo | 0.2 mo | 0.25 mo | 0 mo |
| 6 | Full multi-language real-time auto-translation | 1.5 mo | 0.4 mo | 0.5 mo | 0.25 mo |
| 7 | Multi-currency payment & settlement everywhere | 1.5 mo | 0.4 mo | 0.5 mo | 0.4 mo |
| 8 | GDPR + Japan + Korea personal data compliance | 1 mo | 0.4 mo | 0.4 mo | 0.6 mo |

| # | IP Owner Site Feature | Dev Effort | PM / Sync | Testing | Legal Review |
|---|-----------------------|------------|-----------|---------|--------------|
| 9 | Full IP registration with 100+ metadata fields | 1 mo | 0.25 mo | 0.25 mo | 0.2 mo |
| 10 | Secondary creation guidelines public posting + official badge | 0.5 mo | 0.15 mo | 0.15 mo | 0.15 mo |
| 11 | Secondary creation approval workflow (Approve/Reject/Hold + feedback) | 1 mo | 0.25 mo | 0.3 mo | 0.2 mo |
| 12 | AI-assisted secondary creation auto-review | 1.5 mo | 0.4 mo | 0.4 mo | 0.25 mo |
| 13 | Country-specific contract templates | 1 mo | 0.3 mo | 0.25 mo | 0.6 mo |
| 14 | Electronic signature integration (DocuSign / ModuSign) | 1 mo | 0.25 mo | 0.25 mo | 0.5 mo |
| 15 | Automated royalty calculation & splitting engine | 1.5 mo | 0.4 mo | 0.5 mo | 0.5 mo |
| 16 | Multi-currency royalty settlement + escrow + MG offset | 1.5 mo | 0.4 mo | 0.4 mo | 0.4 mo |
| 17 | Japan dual-permission certificate system | 0.75 mo | 0.2 mo | 0.2 mo | 0.3 mo |
| 18 | Dispute filing & arbitration committee module | 1 mo | 0.3 mo | 0.3 mo | 0.75 mo |
| 19 | AI-powered Creator/Brand matching & recommendations | 1.5 mo | 0.4 mo | 0.4 mo | 0.1 mo |
| 20 | Advanced IP analytics dashboard + competitor comparison | 1.5 mo | 0.4 mo | 0.4 mo | 0.15 mo |

| # | Creator Site Feature | Dev Effort | PM / Sync | Testing | Legal Review |
|---|----------------------|------------|-----------|---------|--------------|
| 21 | Creator portfolio management | 0.75 mo | 0.2 mo | 0.2 mo | 0.1 mo |
| 22 | Full digital/physical store with inventory | 1.25 mo | 0.3 mo | 0.35 mo | 0.2 mo |
| 23 | Order fulfilment & shipping management system | 1.25 mo | 0.3 mo | 0.35 mo | 0.2 mo |
| 24 | Automatic SNS cross-posting promotion | 0.5 mo | 0.15 mo | 0.15 mo | 0 mo |
| 25 | Monthly recurring sponsorship tiers | 1 mo | 0.25 mo | 0.3 mo | 0.2 mo |
| 26 | Project-based crowdfunding (All-or-Nothing + Keep-It-All) | 1 mo | 0.25 mo | 0.3 mo | 0.25 mo |
| 27 | Collaboration proposal inbox/outbox | 0.75 mo | 0.2 mo | 0.2 mo | 0.1 mo |
| 28 | AI-powered IP Owner matching | 1.25 mo | 0.3 mo | 0.3 mo | 0.1 mo |
| 29 | Making-log / progress sharing with fans | 0.75 mo | 0.2 mo | 0.2 mo | 0.1 mo |
| 30 | Revenue dashboard (sales + sponsorship + funding) | 1 mo | 0.25 mo | 0.25 mo | 0.1 mo |
| 31 | Tax report generation | 0.75 mo | 0.2 mo | 0.25 mo | 0.3 mo |

| # | Fan Site Feature | Dev Effort | PM / Sync | Testing | Legal Review |
|---|------------------|------------|-----------|---------|--------------|
| 32 | Personalised main feed & discovery | 1 mo | 0.25 mo | 0.3 mo | 0.1 mo |
| 33 | Multi-layer ranking system (daily/weekly/genre/newcomer) | 0.75 mo | 0.2 mo | 0.25 mo | 0 mo |
| 34 | Full community (comments, likes, follows, fan-art UGC) | 1.25 mo | 0.3 mo | 0.35 mo | 0.2 mo |
| 35 | Direct Creator-Fan messaging | 0.75 mo | 0.2 mo | 0.25 mo | 0.15 mo |
| 36 | Mana / point loyalty system | 0.75 mo | 0.2 mo | 0.25 mo | 0.1 mo |
| 37 | Store with shopping cart & reviews | 1 mo | 0.25 mo | 0.3 mo | 0.15 mo |
| 38 | Ticketing & reservation system | 0.75 mo | 0.2 mo | 0.25 mo | 0.15 mo |
| 39 | Premium membership (Pro/Enterprise) perks | 0.5 mo | 0.15 mo | 0.2 mo | 0.15 mo |
| 40 | Early access & limited-edition pre-orders | 0.5 mo | 0.15 mo | 0.2 mo | 0.1 mo |

| # | Wonder Festival × EXPO × IPGO Integration Feature | Dev Effort | PM / Sync | Testing | Legal Review |
|---|---------------------------------------------------|------------|-----------|---------|--------------|
| 41 | Wonder Festival booth application system (individual & corporate) | 1 mo | 0.25 mo | 0.3 mo | 0.2 mo |
| 42 | WF-specific product registration & purchase limits | 0.5 mo | 0.15 mo | 0.2 mo | 0.1 mo |
| 43 | WF-specific tabs & labels everywhere | 0.25 mo | 0.1 mo | 0.1 mo | 0 mo |
| 44 | Real-time booth map in EXPO app synced with IPGO | 1.5 mo | 0.4 mo | 0.5 mo | 0.1 mo |
| 45 | On-site payment & purchase sync | 1.25 mo | 0.3 mo | 0.4 mo | 0.25 mo |
| 46 | Automatic WF sales reporting visible to IP Owners in real-time | 1.25 mo | 0.3 mo | 0.35 mo | 0.2 mo |
| 47 | Mana rewards for on-site activities (booth visits, votes, etc.) | 0.75 mo | 0.2 mo | 0.25 mo | 0.1 mo |
| 48 | AR / Pokémon GO-style event mode + mini-games at Wonder Festival | 2 mo | 0.5 mo | 0.6 mo | 0.15 mo |

### Limitations and Potential Issues

While the IPGO platform estimations provide an optimistic roadmap, several limitations and risks could impact delivery, scalability, and success. These are based on the document's ambitious scope, current tech stack (Directus/Nuxt/Spring Boot/React Native), and small team constraints.

| Issue Category | Description | Potential Impact | Mitigation Suggestion |
|----------------|-------------|------------------|-----------------------|
| **Underestimated Effort** | Estimations are optimistic, assuming no tech debt or changes; real-world bugs, integrations, or scope creep will extend timelines 2-3x. | Delayed launches (e.g., WF 2026 readiness slips); budget overruns. | Phase deliveries strictly. Smaller deliverables |
| **Directus Limitations** | Directus handles data/auth well but requires heavy extensions for complex flows (royalties, AI matching, real-time WF sync); at scale, it may bottleneck on DB performance or custom logic. | Maintenance debt; perf issues during high-traffic events like WF (50k+ users). | Monitor extension complexity; migrate to custom backend if >50% code is custom (1-2mo effort). |
| **Team & Resource Constraints** | Only 2 devs (1 junior); no dedicated QA, designer, or lawyer; outsourcing risks quality/miscommunication. | Burnout, slow progress; incomplete testing leads to production bugs. | Hire/outsource QA early |
| **Legal & Compliance Risks** | Features like contracts, royalties, disputes, and Japan-specific certificates need thorough review; omissions could violate IP laws (e.g., JASRAC in Japan). | Lawsuits, platform shutdown; delays from audits. | Engage external lawyers per feature (add 1-3 mo each); prioritize JP/KR compliance. |
| **Scaling & Performance** | Real-time features (sync, notifications, AR at WF) untested at scale; missing production elements (load testing, backups) could fail under load. | Downtime during events; data loss. | Conduct pilots at small WF-like events; add monitoring tools early. |
| **Integration Dependencies** | Reliance on external APIs (DocuSign, payments, AI services) introduces downtime risks; WF/EXPO app sync could break with updates. | Feature failures; increased support needs. | Use fallback mechanisms; version APIs strictly. |


# Production Ready-ness

While the application is feature rich, it is missing what is expected from global-tier b2c2c platform.

| # | Missing Production Component | Dev Effort | PM / Sync | Testing |
|---|------------------------------|------------|-----------|---------|
| M1 | Full admin panel + user impersonation (not possible on directus) | 2 mo (rewrite) | 0.5 mo | 0.8 mo |
| M2 | Rate limiting, brute-force protection, 2FA | 0.5 mo | 0.3 mo | 0.6 mo |
| M3 | Proper monitoring + logging (Sentry/Datadog) | 1.5 mo | 0.4 mo | 0.4 mo |
| M4 | CI/CD pipelines + automated tests | 2 mo | 0.5 mo | 1 mo |
| M5 | Full security audit & pentest | 0.5 mo setup | 0.5 mo | 2 mo external |
| M6 | Performance & load testing (10k+ users) | 0.5 mo | 0.4 mo | 1.5 mo |
| M7 | Backup, disaster recovery & rollback | 0.5 mo | 0.5 mo | 0.8 mo |
| M8 | Transactional email deliverability system | 1 mo | 0.3 mo | 0.4 mo |
| M9 | KYC / age verification (JP requirements) | 1.5 mo | 0.4 mo | 0.5 mo |
| M10 | Customer support tools integration | 1.5 mo | 0.5 mo | 0.5 mo |
| M11 | Onboarding flows & in-app tutorials | 2 mo | 0.6 mo | 0.6 mo |
| M12 | Full mobile-responsive + PWA fixes | 2 mo | 0.5 mo | 0.8 mo |
| M13 | App Store / Google Play compliance | 1 mo | 0.5 mo | 0.5 mo |
| M14 | Accessibility WCAG 2.1 AA | 2 mo | 0.5 mo | 1 mo |


# Concluson

The IPGO platform, as outlined, is an ambitious integrated system for IP management, creator support, fan engagement, and Wonder Festival integration. However, feasibility is low for a full build with a 2-developer team due to the scope's complexity, requiring extensive Directus extensions for workflows like royalties and AI matching, which could evolve into a de facto custom backend as data manipulation scales.

Risks include burnout, delayed deliveries, and maintenance issues from tech debt or untested integrations. It's unrealistic to deliver the entire 48-feature vision without significant outsourcing or hiring, as the small team lacks capacity for parallel work, legal reviews, and production essentials like security audits.

It becomes feasible if goals are kept small, focusing on modular, shippable features with constant releases (e.g., start with WF approvals and basics) rather than big chunks. System fundamentals may need to change mid-project, such as migrating to a custom backend if Directus hits limits on real-time or AI ops, to ensure long-term scalability. Prioritize iterative feedback from Kaiyodo to align with practical constraints and achieve sustainable progress.