# Rough Execution Plan (2 Developers)

Based on `ESTIMATION.md`, this plan outlines a multi-phase execution strategy tailored for a 2-developer team.

> [!IMPORTANT]
> **Reality Check**: The total estimated development effort is **~65 man-months**. With 2 developers, this represents **~32 months (2.5+ years)** of work, assuming perfect efficiency and no holidays/sickness.
> To deliver value sooner, this plan prioritizes a "Foundation -> Core -> Growth" strategy.

## Strategy
*   **Team**: 2 Full-stack Developers.
*   **Methodology**: Agile/Kanban. Focus on completing one functional module before moving to the next to avoid context switching.
*   **Bottleneck Mitigation**:
    *   **Dev A**: Focuses on Backend, Data Structure, Compliance, and Complex Logic (Royalties, AI).
    *   **Dev B**: Focuses on Frontend, UI/UX, Dashboards, and User-facing features.
    *   **Shared**: Testing, QA, and Deployment.

---

## Phase 1: Foundation, Compliance & Admin (Months 1-4)
**Goal**: Establish a stable, compliant base and tools for internal ops.

*   **Focus**: Security, Legal, DevOps, and Basic User Management.
*   **Key Deliverables**:
    *   [M4] CI/CD pipelines + automated tests (Critical for small team efficiency).
    *   [M1] Full admin panel + user impersonation (Rewrite/Setup).
    *   [1] Bug fixes & UX polish.
    *   [2] Stable SSO + role switching.
    *   [3] Unified dashboard.
    *   [8] GDPR + Japan + Korea personal data compliance.
    *   [M13] App Store / Google Play compliance (Initial setup).

**Resource Allocation**:
*   Dev A: CI/CD, Compliance (GDPR), SSO Backend.
*   Dev B: Admin Panel UI, Unified Dashboard, UX Polish.

---

## Phase 2: Core IP & Creator Economy (Months 5-10)
**Goal**: Enable IP Owners to list IPs and Creators to register/transact.

*   **Focus**: The core B2B / B2C2C loop.
*   **Key Deliverables**:
    *   [9] Full IP registration (Metadata).
    *   [10] Secondary creation guidelines.
    *   [13] Country-specific contract templates.
    *   [14] Electronic signature integration.
    *   [21] Creator portfolio management.
    *   [27] Collaboration proposal inbox/outbox.
    *   [11] Secondary creation approval workflow.
    *   [30] Revenue dashboard (Basic).

**Resource Allocation**:
*   Dev A: Contract Logic, E-signature API, Approval Workflow Backend.
*   Dev B: IP Registration Forms, Portfolio UI, Dashboard Visuals.

---

## Phase 3: Commerce & Payments (Months 11-15)
**Goal**: Turn the platform into a marketplace.

*   **Focus**: Money movement, Shops, and Orders.
*   **Key Deliverables**:
    *   [7] Multi-currency payment & settlement.
    *   [22] Full digital/physical store with inventory.
    *   [37] Store with shopping cart & reviews (Fan side).
    *   [23] Order fulfilment & shipping management.
    *   [31] Tax report generation.
    *   [25] Monthly recurring sponsorship tiers.

**Resource Allocation**:
*   Dev A: Payment Gateway Integration, Tax Logic, Order Backend.
*   Dev B: Storefront UI, Cart Flow, Sponsorship UI.

---

## Phase 4: Wonder Festival Integration (Months 16-20)
**Goal**: Prepare for the physical event (Must align with event schedule).

*   **Focus**: O2O (Online to Offline) features.
*   **Key Deliverables**:
    *   [41] WF booth application system.
    *   [42] WF-specific product registration.
    *   [44] Real-time booth map in EXPO app.
    *   [45] On-site payment & purchase sync.
    *   [46] Automatic WF sales reporting.
    *   [43] WF-specific tabs & labels.

**Resource Allocation**:
*   Dev A: Map Data Sync, Real-time Sales Backend, Booth Logic.
*   Dev B: Map UI, Mobile App Views, Booth Application Forms.

---

## Phase 5: Fan Engagement & Community (Months 21-25)
**Goal**: Drive retention and daily active usage.

*   **Focus**: Social features and Gamification.
*   **Key Deliverables**:
    *   [32] Personalised main feed.
    *   [34] Full community (comments, likes, UGC).
    *   [35] Direct Creator-Fan messaging.
    *   [36] Mana / point loyalty system.
    *   [33] Multi-layer ranking system.
    *   [39] Premium membership perks.

**Resource Allocation**:
*   Dev A: Feed Algorithms, Messaging Socket Server, Points Logic.
*   Dev B: Feed UI, Chat UI, Community Interaction Components.

---

## Phase 6: Advanced Features & AI (Months 26+)
**Goal**: Automation and High-value differentiators.

*   **Focus**: Reducing manual work and "Wow" factors.
*   **Key Deliverables**:
    *   [12] AI-assisted secondary creation auto-review.
    *   [19] AI-powered Creator/Brand matching.
    *   [28] AI-powered IP Owner matching.
    *   [6] Full multi-language real-time auto-translation.
    *   [15] Automated royalty calculation engine (Complex).
    *   [16] Multi-currency royalty settlement.
    *   [48] AR / Pokémon GO-style event mode.
    *   [M2-M12] Remaining Production Readiness (Load testing, Security Audit, etc.).

**Resource Allocation**:
*   Dev A: AI Model Integration, Royalty Engine, AR Backend.
*   Dev B: AI Feedback UI, AR Frontend, Advanced Analytics UI.

---

## Risks & Mitigations (2-Dev Team)
1.  **Bus Factor**: If one dev leaves or gets sick, velocity drops by >50%.
    *   *Mitigation*: Strict code documentation and weekly knowledge transfer sessions.
2.  **Burnout**: The scope is massive.
    *   *Mitigation*: Strictly adhere to "Best Case" scope. Cut features aggressively if deadlines slip.
3.  **Context Switching**: Jumping between Frontend/Backend/DevOps.
    *   *Mitigation*: Dedicate specific days for specific types of work (e.g., "Frontend Fridays").
