# OctoAcme Project Management Docs

## Purpose and Value

This folder is the central reference for how OctoAcme plans, delivers, and improves projects. It provides a consistent framework that new team members can follow from day one, reduces onboarding time, and keeps all stakeholders aligned on process expectations.

## Summary

OctoAcme uses a structured, lifecycle-based approach to project management built around five core phases:

1. **Initiation** — Validate the business need, align stakeholders, define success metrics, and decide whether to move forward. Key deliverables include a Project One-pager, stakeholder list, and initial risk inventory.
2. **Planning** — Translate an approved initiative into a prioritized backlog, release plan, and milestone map. Teams hold a kickoff meeting, estimate scope, define the Definition of Done, and identify dependencies.
3. **Execution** — Deliver working software in small, testable increments. The team follows a daily standup cadence, a structured PR workflow (≤ 400 lines, linked issues, CI checks, and peer review), and continuous quality practices including unit tests, integration tests, end-to-end smoke tests, and security scanning.
4. **Release** — Deploy changes safely using pre-release checklists, staging smoke tests, automated pipelines, and a documented rollback plan. Releases are announced to stakeholders with standardized release notes.
5. **Continuous Improvement** — After each sprint, release, or milestone the team runs a retrospective (what went well, what to improve, action items), tracks improvements in the backlog, and measures the impact of changes.

### Personas and Roles

| Role | Key Responsibilities |
|---|---|
| **Project Manager (PM)** | Maintains project plans and timelines, manages risks and dependencies, facilitates meetings, coordinates cross-team communication, and produces status reports. |
| **Product Manager (PdM)** | Defines problem statements and success metrics, prioritizes the roadmap and backlog, and validates solutions with users and data. |
| **Developers** | Implement features to meet acceptance criteria, write and maintain tests and documentation, participate in design and code reviews, and help identify technical risks. |

### Communication Cadence

- **Daily standups** (15 min) — progress, blockers, and dependencies for the delivery team.
- **Weekly PM ↔ PdM sync** — alignment on roadmap, risks, and upcoming milestones.
- **Weekly delivery sync** — broader team progress review and flagged risks.
- **Monthly stakeholder updates** — written status report or meeting.
- **Ad-hoc escalations** — Team → PM → Product Lead → Sponsor; security incidents follow the security incident runbook.

### Quality Assurance and Risk Management

- Automated unit, integration, and end-to-end smoke tests run in CI on every pull request.
- Security scanning is part of the CI pipeline.
- A **Risk Register** tracks each risk by ID, impact, likelihood, owner, mitigation plan, and status; reviewed and updated at every weekly sync.
- Blocker escalation follows a three-level path: team standup → PM escalation → sponsor-level escalation for business-impacting issues.

---

## Index of Process Documents

| Document | Description |
|---|---|
| [OctoAcme Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, lifecycle summary, and communication cadence. |
| [Project Initiation](octoacme-project-initiation.md) | Steps to validate and authorize new work, align stakeholders, and create a lightweight plan. |
| [Project Planning](octoacme-project-planning.md) | Turning an approved initiative into an actionable backlog, release plan, and milestone map. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day delivery rhythm, PR workflow, quality practices, metrics, and escalation paths. |
| [Risks & Communication](octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates, and escalation paths. |
| [Release & Deployment](octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running the session, tracking action items, and building an improvement culture. |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers. |
