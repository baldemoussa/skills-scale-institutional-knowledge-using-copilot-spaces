# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a lightweight, repeatable project management lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. The approach emphasizes customer value, iterative delivery, clear ownership, and data-informed decisions. Projects begin with a concise one‑pager to validate the problem and success metrics, move into planning to decompose and estimate work, and then execute with a disciplined delivery rhythm, clear acceptance criteria, and quality checks before release.

This README serves as the single entry point to OctoAcme's process documentation. Use it to find the right guidance for your project phase, locate templates and checklists, and understand who owns which artifacts and decisions.

## Table of contents

- Overview
- Key Workflows
- Roles & Personas
- Quality Assurance Practices
- Links to Process Documents
- Communication Cadence & Quick Reference
- Acceptance Criteria for Process Docs
- Getting Started
- How to Contribute

## Key Workflows

- Backlog & planning: Create prioritized backlog items with acceptance criteria, estimates, and owners. Define a Definition of Done (DoD), map release milestones, and capture risks in the Risk Register.
- Execution & PR workflow: Use the project board with columns Backlog → Ready → In Progress → In Review → QA → Done. Favor small PRs that include issue links and acceptance criteria; require CI/linting to pass and at least one approval before merging.
- Releases & deployments: Follow Patch/Minor/Major release types with pre-release checklists, smoke tests, and rollback/incident playbooks to reduce risk.

## Roles & Personas

- Product Manager (PdM): Defines outcomes, success metrics, and prioritizes the backlog.
- Project Manager (PM): Coordinates delivery, schedules, risk management, and stakeholder communications.
- Developers: Implement features, write tests, and participate in design and code reviews.
- QA/Testing: Validate acceptance criteria, run manual and automated tests, and sign off on releases.

Templates and persona definitions are available in the docs to ensure consistent handoffs and predictable delivery.

## Quality Assurance Practices

Unit and integration tests are expected for new logic; end-to-end smoke tests are used for critical flows. CI pipelines run automated tests and security scans; manual QA is used for acceptance when needed. Releases require passing CI, completed release notes, and a documented rollback plan. Security and production-readiness checks should be part of the PR/merge workflow for release branches.

## Links to Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risks & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Communication Cadence & Quick Reference

- Daily: Team standups (15 min)
- Weekly: PM + PdM sync and delivery sync; review risk register
- Monthly: Stakeholder updates

Decision gates:
- Initiation: success metrics clear, stakeholders aligned, resources available
- Planning: backlog estimated, DoD documented, dependencies identified
- Execution: acceptance criteria met, PR reviewed, CI passing, QA approved
- Release: tests passing, security scans clean, rollback plan in place

## Acceptance Criteria for This Process README

- [x] Includes a brief overview of OctoAcme project management processes
- [x] Links to all existing process documents in docs/
- [x] Provides a quick navigation guide and communication cadence
- [ ] Has been reviewed with stakeholders (optional)

## Getting Started

1. New to OctoAcme? Start with the Project Management Overview.
2. Launching a project? Complete the Project One‑pager and follow the Initiation Guide.
3. Ready to deliver? Follow Execution & Tracking and use the project board templates.

## How to Contribute

To propose updates to these process docs, open a new issue using the "Add Content to Project Management Process Docs" template located at .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml. Include a summary, rationale, and suggested content. The project maintainer will review and implement changes via PR.

---

*Last updated: 2026-09-02*

For questions or contributions, open an issue and reference the "Process Docs" template.
