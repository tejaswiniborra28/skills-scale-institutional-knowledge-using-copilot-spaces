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

## Additional Personas (Proposed additions)

These personas are commonly involved in cross-functional projects. Each persona below includes a short responsibilities blurb and primary interactions with the existing roles.

### Delivery Lead / Program Manager
- Responsibilities: Coordinate cross-team delivery, manage timelines and milestones, own the consolidated project plan, monitor KPIs for delivery, and consolidate status reporting.
- Interacts with: PM (Project Manager), PdM (Product Manager), Developers, QA, Release Engineer.
- Why it matters: Reduces ambiguity for cross-team dependencies and centralizes delivery tracking across multiple squads.

### Technical Architect
- Responsibilities: Define architecture decisions, system boundaries, non-functional requirements (scalability, security), and review major technical designs; produce architecture decision records (ADRs).
- Interacts with: Developers, Project Manager, Product Manager, Release Engineer.
- Why it matters: Ensures technical consistency, reduces redundant rework, and surfaces technical trade-offs early.

### UX Researcher / Designer
- Responsibilities: Run user research, define UX requirements, produce designs and prototypes, ensure accessibility and usability, and validate designs through testing.
- Interacts with: Product Manager, Developers, QA, Stakeholder Representatives.
- Why it matters: Validates product direction with real users and reduces rework from usability issues.

### Release Engineer / CI-CD Owner
- Responsibilities: Manage deployment pipelines and automation, maintain release playbooks and rollback procedures, ensure observability of deployments, and own release runbooks.
- Interacts with: Developers, QA, Delivery Lead, Support/Operations Liaison.
- Why it matters: Improves deployment reliability and reduces friction during releases and rollbacks.

### Data Analyst / Measurement Lead
- Responsibilities: Define success metrics and instrumentation plans, implement or advise on telemetry, analyze outcomes, and produce post-release insights.
- Interacts with: Product Manager, Developers, Project Manager.
- Why it matters: Ensures features tie to measurable outcomes and supports data-informed prioritization.

### Support / Operations Liaison
- Responsibilities: Represent support and operations concerns (on-call, runbooks), prepare customer-facing support materials, and coordinate post-release monitoring.
- Interacts with: Release Engineer, Project Manager, Developers, SRE.
- Why it matters: Ensures operational readiness and smoother incident response.

### Security Liaison
- Responsibilities: Advise on security requirements, review major changes for security implications, ensure compliance requirements are addressed.
- Interacts with: Technical Architect, Developers, Project Manager.
- Why it matters: Reduces security risk and ensures compliance work is planned, not reactive.

### Accessibility Advocate
- Responsibilities: Define accessibility acceptance criteria, review designs and implementations for accessibility, coordinate audits.
- Interacts with: UX Designer, Developers, QA.
- Why it matters: Ensures legal and usability requirements are considered early in design/dev.

### Service Reliability Engineer (SRE)
- Responsibilities: Define service-level objectives (SLOs), monitor production health, operationalize observability and incident playbooks.
- Interacts with: Release Engineer, Developers, Support/Operations Liaison.
- Why it matters: Improves long-term reliability and reduces time-to-resolution for incidents.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- When applicable, add the specific persona as an owner on backlog items or action items.
- Each persona description should include a short "Interacts with" list so it's clear who the primary touchpoints are.
- For real projects, annotate who is acting in each role (name and contact) so that handoffs are unambiguous.

---

## Using this document in practice
- Add a one-line owner to each persona to show who currently covers the role on this project (if any).
- When creating or updating process docs, reference this personas file to resolve ownership questions.
- Use the checklist in docs/personas-addition-checklist.md to add new personas, get stakeholder review, and finalize additions.
