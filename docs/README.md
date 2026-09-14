# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation suite. These process guides help teams execute projects consistently, communicate effectively, and continuously improve.

## Quick Links to Process Docs

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation](octoacme-project-initiation.md)** — Steps to validate, authorize, and kickoff new projects
- **[Project Planning](octoacme-project-planning.md)** — How to break work into shippable increments and build a delivery plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, quality standards, and progress tracking
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — How to identify, monitor, and communicate risks and dependencies
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardized processes for releasing features to production
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to capture learnings and iterate on processes
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Definitions of key project roles and responsibilities

## OctoAcme Project Management Processes: Overview

OctoAcme follows a structured, lifecycle-based approach to project management organized around five key phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The Initiation phase begins with validation of business need through a lightweight Project One-pager that captures the problem statement, objectives, success metrics, stakeholders, and resource requirements. This serves as a decision gate—work only moves forward to planning once success metrics are clear, stakeholders align on priority, and team availability is confirmed. The Planning phase transforms the approved initiative into an actionable backlog by breaking work into shippable increments, estimating scope, defining acceptance criteria, identifying dependencies and risks, and establishing a release timeline. This disciplined approach ensures that delivery teams have clarity on what "done" looks like before work begins.

Execution and delivery are coordinated through a structured team rhythm and clear ownership model. OctoAcme defines four core roles—**Project Manager (PM), Product Manager (PdM), Developers, and QA/Testing**—each with distinct responsibilities. The PM coordinates schedules, risks, and communications; the PdM owns outcomes and backlog prioritization; developers implement features and collaborate on design; and QA validates quality against acceptance criteria. The team operates on a predictable cadence of daily standups, weekly delivery syncs, and regular demos or reviews, using a GitHub Projects board with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines when possible), include issue links and acceptance criteria, and require at least one approval before merging. This combination of clear roles, regular synchronization, and lightweight governance keeps the team aligned and reduces friction.

Quality assurance and risk management are embedded throughout the project lifecycle. OctoAcme requires unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI before any merge or release. A Risk Register captures potential blockers with impact, likelihood, owner, and mitigation plan; risks are reviewed at weekly syncs and escalated through a three-level structure (team triage → PM escalation → sponsor escalation) when needed. Stakeholder communication follows a consistent cadence—weekly status updates, monthly stakeholder reports, and ad-hoc escalations—using standardized templates that surface progress, next steps, risks, and decisions needed. Finally, each project concludes with a retrospective (45–75 minutes) to capture what went well, what could improve, and actionable items with clear owners and due dates, creating a continuous improvement feedback loop.

## Project Lifecycle at a Glance

1. **Initiation** — Validate business need, align stakeholders, define success metrics
2. **Planning** — Break work into shippable increments, identify dependencies and risks
3. **Execution** — Build, test, review, and iterate in short cycles
4. **Release** — Deploy features to production and verify success
5. **Close & Retrospective** — Capture learnings and feed improvements back into processes

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Ship small, testable increments regularly
- **Clear ownership:** Each project has a named PM and Product Lead
- **Data-informed:** Measure impact and adjust based on evidence
- **Psychological safety:** Encourage feedback and continuous learning

## Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

## Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence

- **Weekly sync** between PM + PdM
- **Daily standups** for delivery team (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Reference the appropriate process doc based on your current project phase
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Use issue templates in `.github/ISSUE_TEMPLATE/` to standardize process documentation updates

---

**Last updated:** 2026-09-14

For questions or suggested improvements, see the [Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).
