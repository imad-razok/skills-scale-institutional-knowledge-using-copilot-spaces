# OctoAcme Project Management Docs

This README centralizes OctoAcme project management processes used across initiatives. It provides a comprehensive overview of our structured approach and direct links to detailed process documents stored in the `docs/` folder to make them easier to find, reference, and apply.

## Project Management Overview

OctoAcme follows a structured, lifecycle-based approach that emphasizes customer value, iterative delivery, and clear ownership across five distinct phases:

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and iterate based on outcomes and feedback
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead with defined responsibilities
- **Data-informed decisions**: Define success metrics upfront and measure impact throughout the project lifecycle
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle Phases

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight plan with a Project One-pager
2. **Planning** — Break work into shippable increments with prioritized backlogs, acceptance criteria, and Definition of Done
3. **Execution** — Deliver through disciplined cadence: daily standups, weekly syncs, and regular demos
4. **Release** — Deploy to production with pre-release checks, smoke tests, and post-deployment verification
5. **Closeout & Retrospective** — Capture learnings and convert them into actionable improvements

### Key Workflows & Artifacts

**Communication Cadence:**
- Daily standups (15 min) — focus on progress, blockers, and dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at end of sprint or milestone
- Monthly stakeholder updates

**Core Artifacts:**
- Project One-pager (problem, goal, success metrics, stakeholders, timeline)
- Roadmap and Release Plan
- Prioritized Backlog with acceptance criteria and estimates
- Risk Register and mitigation plans
- Sprint/Iteration plans with Definition of Done
- Release notes and deployment checklists
- Retrospective notes and action items

**Quality Assurance:**
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance
- Small PRs (≤400 lines) with linked issues and clear acceptance criteria

### Roles & Responsibilities

- **Project Manager** — Coordinates delivery, manages schedules, risks, and communications
- **Product Manager** — Defines outcomes, prioritizes backlog, measures success
- **Developers** — Implement features, write tests, collaborate on design and testability
- **QA/Testing** — Validates quality and acceptance criteria
- **Stakeholders** — Provide inputs, approvals, and business context

## Links to Process Documents

### Foundation & Overview
- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme project management approach, roles, and lifecycle

### Lifecycle Phases
- [octoacme-project-initiation.md](./octoacme-project-initiation.md) — Steps to validate work, align stakeholders, and create initial plan
- [octoacme-project-planning.md](./octoacme-project-planning.md) — Turn approved initiative into actionable plan and backlog
- [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) — Day-to-day execution, tracking progress, quality assurance, and blocker escalation
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Standardize releases to production with risk mitigation and rollback procedures
- [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into improvements

### Cross-Cutting Concerns
- [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) — Risk management, risk registers, stakeholder communication, and escalation paths
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Detailed role descriptions and responsibilities for Project Managers, Product Managers, Developers, and QA

## How to Use These Docs

1. **New to OctoAcme?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for context, then dive into [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) to understand your role.

2. **Starting a new project?** Follow the sequence: [Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution](./octoacme-execution-and-tracking.md).

3. **Preparing for release?** Review [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) for checklists and procedures.

4. **Running a retrospective?** Use [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) as your guide.

5. **Managing risks or communicating status?** Consult [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) for templates and escalation guidance.

## Maintaining These Docs

- Keep the `docs/` directory authoritative; update links here when documents are added, renamed, or significantly updated
- Use the [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to request updates
- Treat these docs as living artifacts; gather feedback from the team regularly and incorporate lessons learned

## Questions or Feedback?

For questions, clarifications, or suggested updates to these process documents:
- Open an issue using the [Process Doc Update template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- Contact [@imad-razok](https://github.com/imad-razok)
