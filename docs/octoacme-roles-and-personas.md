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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

To reduce ambiguity and improve handoffs on cross-team initiatives, releases, and incidents, add the following personas. For each persona below we provide: Role Summary, Responsibilities, Typical Interactions, and an Example Scenario.

### Technical Program Manager (TPM)
Role Summary
- Coordinates planning and delivery for complex, cross-team initiatives. Focuses on sequencing, dependency management, and milestone tracking.

Responsibilities
- Own cross-team planning, integration points, and milestone tracking.
- Maintain and update the cross-team plan and risk register.
- Drive dependency resolution and coordinate integration testing.

Typical Interactions
- Works with Product Manager (priorities), Project Manager (schedule), Engineering Leads (technical dependencies), and Release Engineer (sequencing).

Example Scenario
- TPM coordinates multi-team rollout; identifies a blocking dependency and schedules a dedicated integration sync to resolve it.

---

### Delivery Lead
Role Summary
- Day-to-day execution owner for a release or program; ensures sprint commitments and backlog readiness.

Responsibilities
- Ensure backlog items meet DoD and acceptance criteria.
- Facilitate daily execution decisions and unblock teams.
- Drive readiness checks prior to release.

Typical Interactions
- Collaborates with PM, Developers, QA, and Release Engineer to keep delivery on track.

Example Scenario
- Delivery Lead works with QA to reprioritize testing for a critical bug found during staging.

---

### Engineering Lead / Tech Lead
Role Summary
- Provides technical direction, architecture decisions, and implementation guidance for the team.

Responsibilities
- Make architecture and design decisions; own technical tradeoffs.
- Lead code reviews and major technical designs.
- Ensure non-functional requirements (security, performance, reliability) are met.

Typical Interactions
- Works with Developers, TPM, PdM, and Security Liaison to validate technical approach.

Example Scenario
- Engineering Lead approves a scoped change to meet a performance SLA while minimizing scope.

---

### UX Researcher / Designer
Role Summary
- Owns user research, design acceptance criteria, and usability validation.

Responsibilities
- Run user research and usability testing.
- Provide designs, interaction specs, and acceptance criteria.
- Validate UX in prototypes and during UAT.

Typical Interactions
- Partners with PdM for requirements and Developers for implementation.

Example Scenario
- UX Researcher conducts quick usability test to validate a redesign before final implementation.

---

### Data Analyst
Role Summary
- Defines measurement plans, instruments metrics, and analyzes impact.

Responsibilities
- Define success metrics and measurement plan for features.
- Implement and validate telemetry; create dashboards and reports.
- Analyze results to inform product decisions.

Typical Interactions
- Works with PdM (success metrics) and Developers/QA (instrumentation).

Example Scenario
- Data Analyst builds a dashboard used in the sprint review to validate feature adoption.

---

### Release Engineer / Platform Engineer
Role Summary
- Maintains CI/CD pipelines and owns automated deployments and rollback mechanisms.

Responsibilities
- Maintain deployment pipelines and automation.
- Run staging and production deployments, own rollback and mitigation steps.
- Support release verification automation and observability.

Typical Interactions
- Works with Delivery Lead, Developers, and On-call/Support during releases and incidents.

Example Scenario
- Release Engineer identifies a failing pipeline step and coordinates a hotfix and rollback plan.

---

### Security Liaison
Role Summary
- Coordinates security reviews and ensures compliance with security requirements.

Responsibilities
- Triage security findings, coordinate remediations, and advise on secure design patterns.
- Ensure necessary reviews and scans are completed before release.

Typical Interactions
- Works with Engineering Leads, PM, and Security on-call.

Example Scenario
- Security Liaison confirms mitigation for a vulnerability before approving production rollout.

---

### Support / On-call Liaison
Role Summary
- Represents operations/support perspective during planning and post-release support.

Responsibilities
- Capture user-reported issues, triage operational impact, and manage handoff for post-release support.
- Provide runbook updates and ensure support readiness.

Typical Interactions
- Works with Developers, Delivery Lead, and Release Engineer during rollouts and incidents.

Example Scenario
- On-call Liaison escalates a customer-impacting bug and coordinates support and engineering response.

---

Placement guidance
- Suggested placement: add an "Additional Personas" section (as above) in docs/octoacme-roles-and-personas.md.
- For each persona, include: Role Summary, Responsibilities, Typical Interactions, and Example Scenario.
