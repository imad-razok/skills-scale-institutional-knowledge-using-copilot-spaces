# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure product quality through comprehensive testing strategies, acceptance validation, and quality metrics. They collaborate with product and engineering teams to define and execute test plans that reduce risk and ensure features meet acceptance criteria.

### Responsibilities
- Define testing strategy and test plans aligned with acceptance criteria
- Own quality metrics and reporting
- Lead manual QA, identify and triage defects
- Collaborate on automated testing approach and coverage targets
- Validate releases and production deployments
- Facilitate quality discussions in planning and retrospectives

### Goals
- Deliver high-quality features with minimal post-release issues
- Reduce cycle time through effective test automation and strategy
- Enable customer confidence through transparent quality reporting

### Typical Communication
- Sprint planning and backlog refinement
- Quality metrics and defect reports
- Test case documentation and release sign-off

---

## Technical Lead / Software Architect

### Role Summary
Technical Leads guide technical direction, design, and quality. They work with Product Managers and engineers to balance customer needs with technical sustainability and scalability.

### Responsibilities
- Provide technical guidance on design decisions and architecture
- Review designs for scalability, security, and maintainability
- Mentor developers and lead code review efforts
- Identify and mitigate technical risks and debt
- Advocate for technical quality and refactoring investments
- Partner with operations and security teams on non-functional requirements

### Goals
- Enable sustainable, scalable technical solutions
- Build team capability and technical depth
- Reduce technical risk and long-term maintenance burden

### Typical Communication
- Technical design reviews and architecture discussions
- Code review and mentoring
- Risk identification and mitigation planning

---

## UX Designer

### Role Summary
UX Designers advocate for users and usability. They conduct research, create designs, and validate solutions to ensure product features are intuitive, accessible, and meet user needs.

### Responsibilities
- Conduct user research and define user personas
- Create wireframes, prototypes, and design specifications
- Validate designs through user testing and feedback
- Define accessibility and usability standards
- Participate in acceptance criteria definition
- Provide design reviews and feedback on implementation

### Goals
- Deliver intuitive, accessible, and user-centric solutions
- Validate product direction through user insights
- Minimize rework through design-led collaboration

### Typical Communication
- Roadmap and backlog prioritization input
- Design specifications and usability validation
- Sprint planning and design review discussions

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters / Agile Coaches facilitate team processes, remove blockers, and drive continuous improvement. They enable the team to self-organize and operate efficiently.

### Responsibilities
- Facilitate daily standups, planning, reviews, and retrospectives
- Help the team identify and resolve impediments
- Maintain sprint board and backlog health
- Coach team on Agile practices and continuous improvement
- Identify process bottlenecks and recommend solutions
- Escalate blockers to appropriate leaders

### Goals
- Enable high-performing, self-organizing teams
- Reduce process friction and delivery cycle time
- Build team ownership and continuous improvement culture

### Typical Communication
- Ceremony facilitation and logistics
- Process improvement discussions
- Blocker and impediment escalation

---

## Operations / DevOps Engineer

### Role Summary
Operations and DevOps Engineers ensure reliable, secure, and efficient infrastructure and deployments. They enable safe, repeatable releases and maintain system health.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage infrastructure, monitoring, and observability
- Ensure security compliance and hardening
- Lead deployment planning and execution
- Triage and resolve production incidents
- Document runbooks and operational procedures
- Partner with developers on deployment-readiness and scale testing

### Goals
- Enable safe, reliable, and rapid deployments
- Maintain high availability and system performance
- Reduce operational toil through automation

### Typical Communication
- Deployment planning and release coordination
- Incident response and post-mortems
- Infrastructure and security reviews

---

## Cross-Functional Collaboration Model

These personas work together in the following ways:

### Key Interactions

**Product Definition & Delivery:**
- **Product Manager** defines what to build; **Developers**, **Technical Lead**, and **UX Designer** determine how; **QA Lead** validates quality
- **UX Designer** provides design specifications; **Developers** implement; **QA Lead** validates against acceptance criteria

**Execution & Process:**
- **Project Manager** coordinates the workflow; **Scrum Master** facilitates the team; **Technical Lead** removes technical blocks
- **Scrum Master** identifies impediments; **Project Manager** escalates and resolves cross-team dependencies

**Technical Implementation:**
- **Developers** implement features; **Technical Lead** ensures architecture and code quality; **QA Lead** validates acceptance criteria
- **Technical Lead** works with **Operations/DevOps** on deployment-readiness, infrastructure requirements, and scalability

**Release & Operations:**
- **Operations/DevOps** partners with **Technical Lead** and **Developers** to ensure deployment-ready features
- **QA Lead** validates release readiness; **Operations/DevOps** executes deployment; **Project Manager** communicates to stakeholders

**Continuous Improvement:**
- All roles participate in **Retrospectives** to drive improvement across product, process, and technical quality
- **Scrum Master** facilitates; **Project Manager** tracks action items; **Technical Lead** addresses technical improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Cross-Functional Collaboration Model to understand how roles interact and support each other.
