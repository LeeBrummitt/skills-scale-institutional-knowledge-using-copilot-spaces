# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This folder contains the canonical guidance for how our organization runs projects, from initiation through retrospectives and continuous improvement.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management grounded in five core principles: **customer-first delivery, iterative development, clear ownership, data-informed decisions, and psychological safety**. Each project is led by a Project Manager (PM) who coordinates delivery and schedules, and a Product Manager (PdM) who defines outcomes and prioritizes the backlog.

### Key Workflows & Phases

**Initiation:** Every project begins with validation and authorization. We create a lightweight Project One-pager that captures the business need, success metrics, stakeholders, and initial timeline. This phase answers the fundamental question: "Do we have clear agreement on what we're building and why?" Only projects that pass stakeholder alignment and have defined success metrics move to planning.

**Planning:** Once approved, the team collaborates to break work into shippable increments. We create a prioritized backlog with acceptance criteria, estimate scope using T-shirt sizing or story points, define our Definition of Done, identify dependencies, and map out release milestones. This phase transforms the high-level vision into an actionable plan.

**Execution & Tracking:** Day-to-day delivery follows a sprint-based rhythm with daily standups (15 min), weekly delivery syncs, and regular demos. We use GitHub Projects boards with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain small pull requests (≤400 lines) with clear acceptance criteria. Quality is enforced through mandatory CI checks, peer code review, and automated testing.

**Release & Deployment:** Before releasing to production, we verify all acceptance criteria are met, run passing CI and security scans, prepare rollback plans, and conduct smoke tests. Releases follow standardized types (Patch, Minor, Major) with documented release notes and post-deployment verification steps.

**Risk Management & Communication:** Throughout execution, we maintain a Risk Register that tracks potential issues by impact, likelihood, and mitigation plan. We communicate transparently through weekly status updates, tiered escalation paths, and incident communication templates. All projects maintain a single source of truth for status.

**Retrospectives & Continuous Improvement:** At the end of each sprint, release, or milestone, the team conducts a retrospective to capture learnings, celebrate wins, and identify 2–3 prioritized action items. These actions feed back into the project backlog, creating a continuous feedback loop that drives improvement.

### Core Roles

- **Project Manager (PM):** Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs, approvals, and strategic direction

## Documentation Index

### Process Guides

- **[Project Management Overview](octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, key roles, artifacts, and lifecycle. Start here if you're new to the organization.

- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate a new project idea, create a one-pager, align stakeholders, and make a go/no-go decision.

- **[Project Planning](octoacme-project-planning.md)** — Breaking approved work into shippable increments, creating a prioritized backlog, defining milestones, and identifying dependencies.

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Managing day-to-day delivery with standups, project boards, PR conventions, quality gates, and regular demos.

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized process for releasing features to production, including pre-release checks, deployment checklists, rollback procedures, and release notes.

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identifying and tracking risks, maintaining a risk register, escalation paths, and communication templates for stakeholders and incidents.

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running effective retrospectives, capturing learnings, and converting action items into backlog improvements.

- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of typical roles (Developers, Product Managers, Project Managers) and their responsibilities within OctoAcme.

## Quick Reference: Process Checklists

### Project Initiation
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Stakeholder alignment confirmed
- [ ] Success metrics are clear
- [ ] Go/no-go decision made
- [ ] Repo or project board skeleton created

### Planning
- [ ] Kickoff meeting held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Risk register initialized

### Execution
- [ ] Branching and PR conventions documented
- [ ] CI configured for tests and lint
- [ ] Daily standups scheduled
- [ ] Project board active and up-to-date
- [ ] Risk register reviewed weekly

### Release
- [ ] All acceptance criteria met
- [ ] Passing CI and security scans
- [ ] Release notes drafted
- [ ] Rollback plan documented
- [ ] Post-deploy verification completed

### Retrospective
- [ ] Retrospective meeting scheduled (45–75 min)
- [ ] What went well, what could improve identified
- [ ] Top 2–3 action items prioritized with owners
- [ ] Action items added to project backlog

## How to Use These Docs

1. **For onboarding:** Start with [Project Management Overview](octoacme-project-management-overview.md) and [Roles & Personas](octoacme-roles-and-personas.md) to understand our approach and where you fit.

2. **Starting a new project:** Follow the sequence: [Initiation Guide](octoacme-project-initiation.md) → [Project Planning](octoacme-project-planning.md) → [Execution & Tracking](octoacme-execution-and-tracking.md) → [Release & Deployment](octoacme-release-and-deployment.md) → [Retrospectives](octoacme-retrospective-and-continuous-improvement.md).

3. **Managing risks and updates:** Reference [Risk Management & Communication](octoacme-risks-and-communication.md) throughout execution.

4. **Adding or updating docs:** Use the [Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose improvements.

## Continuous Improvement

These docs are living artifacts. If you encounter gaps, outdated guidance, or opportunities to improve clarity, please open an issue using the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** template. Your feedback helps us keep these processes current and effective.

---

*Last updated: June 2026 | Maintained by: OctoAcme Project Management*
