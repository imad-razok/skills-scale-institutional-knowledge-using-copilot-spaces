# OctoAcme Role Interaction Matrix

## Purpose
Provide a quick reference for which roles collaborate on which activities and what decisions/artifacts they produce together.

---

## Interaction Matrix

| Activity | Product Manager | Project Manager | Developer | QA/Testing Lead | Technical Lead | UX Designer | Scrum Master | Operations/DevOps |
|----------|---|---|---|---|---|---|---|---|
| **Project Initiation** | ✓ (defines outcomes) | ✓ (coordinates) | | | | | | |
| **Project Planning** | ✓ (priorities) | ✓ (schedules) | ✓ (estimates) | ✓ (test planning) | ✓ (architecture) | ✓ (design planning) | ✓ (facilitates) | ✓ (infra planning) |
| **Acceptance Criteria Definition** | ✓ (leads) | | ✓ (input) | ✓ (testability) | | ✓ (usability) | | |
| **Backlog Refinement** | ✓ (prioritizes) | ✓ (tracks) | ✓ (clarifies) | ✓ (quality input) | ✓ (tech feasibility) | ✓ (design feasibility) | ✓ (facilitates) | |
| **Sprint Planning** | ✓ (presents goals) | ✓ (allocates resources) | ✓ (commits) | ✓ (capacity planning) | ✓ (tech guidance) | | ✓ (facilitates) | |
| **Daily Standup** | | | ✓ | ✓ (if relevant) | ✓ (if relevant) | | ✓ (facilitates) | |
| **Code Review** | | | ✓ (primary) | ✓ (quality focus) | ✓ (architecture focus) | | | |
| **Design Review** | ✓ (business alignment) | | ✓ (feasibility) | | ✓ (technical feasibility) | ✓ (leads) | | |
| **Risk Assessment** | ✓ (business risk) | ✓ (project risk) | ✓ (technical risk) | ✓ (quality risk) | ✓ (architecture risk) | ✓ (usability risk) | | ✓ (operational risk) |
| **Deployment Planning** | | ✓ (timeline) | ✓ (readiness) | ✓ (smoke test plan) | ✓ (arch readiness) | | | ✓ (leads) |
| **Release Execution** | ✓ (announcement) | ✓ (coordination) | ✓ (hotfixes if needed) | ✓ (validation) | | | | ✓ (deploys) |
| **Sprint Review/Demo** | ✓ (attends) | ✓ (facilitates) | ✓ (presents) | ✓ (quality notes) | | ✓ (design feedback) | | |
| **Retrospective** | ✓ (attends) | ✓ (facilitates) | ✓ (participates) | ✓ (participates) | ✓ (participates) | ✓ (participates) | ✓ (facilitates) | ✓ (attends) |
| **Incident Response** | ✓ (comms) | ✓ (coordinates) | ✓ (troubleshoots) | ✓ (verifies fix) | ✓ (guides fix) | | | ✓ (executes/monitors) |

---

## Decision Authority by Role

### Product Manager
- **Decides:** What features to build, prioritization, success metrics, go/no-go on roadmap items
- **Consults:** Engineering, UX, stakeholders

### Project Manager
- **Decides:** Timeline, milestones, resource allocation, escalation actions
- **Consults:** Product Manager, Team leads, Stakeholders

### Developer
- **Decides:** Technical implementation details, code style, testing approach
- **Consults:** Technical Lead, QA Lead, Peers

### QA/Testing Lead
- **Decides:** Testing strategy, test coverage requirements, release readiness criteria
- **Consults:** Product Manager, Developers, Technical Lead

### Technical Lead
- **Decides:** Architecture direction, tech stack, design patterns, refactoring priorities
- **Consults:** Product Manager, Developers, Operations/DevOps

### UX Designer
- **Decides:** User experience, accessibility standards, design specifications
- **Consults:** Product Manager, Developers, Users

### Scrum Master
- **Decides:** Ceremony schedules, process improvements, impediment escalation timing
- **Consults:** Product Manager, Project Manager, Team

### Operations/DevOps Engineer
- **Decides:** Infrastructure design, deployment strategy, monitoring and alerting
- **Consults:** Technical Lead, Developers, Security teams

---

## Communication Patterns

### High-Frequency (Daily)
- Developers ↔ Developers (standups, code reviews)
- Scrum Master ↔ All (ceremony facilitation)

### Weekly
- Product Manager ↔ Project Manager ↔ Technical Lead (alignment)
- QA Lead ↔ Developers (quality checks, test planning)
- Operations/DevOps ↔ Technical Lead (infrastructure status)

### Milestone/Sprint-Based
- Product Manager → All (roadmap, priorities)
- Project Manager → Stakeholders (status updates)
- Technical Lead → All (architecture guidance)
- All → Retrospectives (improvements)

### As-Needed
- Any role → Incident response (outages, critical issues)
- Any role → Project Manager (blockers, risks)
