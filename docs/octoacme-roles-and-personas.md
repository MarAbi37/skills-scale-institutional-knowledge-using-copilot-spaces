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

## Release Manager

### Role Summary
Release Managers own release coordination and readiness across teams. The Project Manager remains accountable for the overall project plan; the Release Manager is the primary owner of release execution and launch readiness.

### Responsibilities
- Coordinate release dates, deployment windows, and readiness checks
- Prepare release notes and rollback plans
- Confirm required approvals and launch criteria are complete
- Track release actions through deployment and post-release verification

### Interactions
- Aligns release milestones and stakeholder communication with the Project Manager
- Coordinates with Developers and QA Lead on validation and readiness
- Works with the SRE / On-call Engineer on operational readiness and rollback plans
- Partners with the Communications / Change Management Lead on launch messaging

---

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers coordinate complex initiatives that span multiple teams, with a focus on technical dependencies and program-level execution.

### Responsibilities
- Drive cross-team technical planning and dependency management
- Track milestones, delivery timelines, and program-level risks
- Facilitate decisions and unblock work across participating teams
- Maintain a consolidated view of progress for complex initiatives

### Interactions
- Partners with the Project Manager, who owns the project plan and project-level reporting, to align milestones and dependencies
- Collaborates with Engineering Leads and Developers to resolve technical blockers
- Coordinates with Product Managers to keep technical sequencing aligned with product priorities

---

## Security / Compliance Lead

### Role Summary
Security / Compliance Leads guide security and compliance reviews and ensure required checks and mitigations are addressed before release.

### Responsibilities
- Review designs and delivery plans for security and compliance implications
- Lead threat modeling and track mitigation actions
- Verify required compliance checks and evidence are completed
- Escalate high-risk issues and advise on release risks

### Interactions
- Works with Developers and QA Lead to validate controls and remediation
- Coordinates with the Project Manager on risks, ownership, and schedule impacts
- Partners with Product Managers on scope trade-offs and escalates high-risk items to the Product Lead and security team

---

## UX Researcher / Design Representative

### Role Summary
UX Researchers and Design Representatives ensure that product decisions and implementations reflect user needs and usable, accessible experiences.

### Responsibilities
- Validate user assumptions through research and usability testing
- Provide design input and user-centered acceptance criteria
- Share usability, accessibility, and workflow findings with the team
- Identify experience risks early enough to inform planning

### Interactions
- Works with Product Managers to connect research findings to product priorities
- Collaborates with Developers and QA Lead to clarify and validate user-facing requirements
- Shares findings with the Project Manager when they affect scope, timelines, or delivery risks

---

## Site Reliability / On-call Engineer (SRE)

### Role Summary
SREs and On-call Engineers prepare services for reliable operation and support incident response and recovery.

### Responsibilities
- Define operational readiness needs, monitoring thresholds, and alerts
- Create or review runbooks and recovery procedures
- Assess reliability risks for releases
- Participate in first response and incident follow-up when on call

### Interactions
- Partners with Developers on observability, reliability, and remediation
- Coordinates with the Release Manager on deployment readiness and rollback plans
- Works with the Project Manager and delivery team on incident follow-ups and action tracking

---

## QA Lead

### Role Summary
QA Leads define and coordinate the project test strategy and communicate quality readiness and risks. Developers remain responsible for testing their changes; the QA Lead coordinates overall coverage and release validation.

### Responsibilities
- Define test strategy, coverage expectations, and quality gates
- Coordinate test execution, regression checks, and defect triage
- Validate that acceptance criteria are covered by testing
- Communicate quality risks and readiness for release

### Interactions
- Works with Developers to plan testability, resolve defects, and maintain coverage
- Aligns test plans and acceptance criteria with Product Managers and the Project Manager
- Coordinates release validation and readiness with the Release Manager

---

## Data Analyst

### Role Summary
Data Analysts help teams define, validate, and interpret the measures used to assess product and project outcomes.

### Responsibilities
- Define instrumentation and measurement requirements
- Validate success metrics and data quality
- Analyze post-release performance and adoption
- Present findings that inform product and delivery decisions

### Interactions
- Partners with Product Managers to define outcome measures and interpret results
- Coordinates with Developers on instrumentation and data availability
- Shares analysis with the Project Manager and stakeholders to support status reviews and retrospectives

---

## Communications / Change Management Lead

### Role Summary
Communications / Change Management Leads prepare stakeholders and support teams for changes and coordinate clear, consistent messaging.

### Responsibilities
- Draft stakeholder communications and customer-facing release notes
- Plan communications around rollout timing and audience needs
- Prepare internal change guidance and support materials
- Identify communication and adoption risks

### Interactions
- Aligns messaging and timing with the Release Manager and Project Manager
- Works with Customer Success / Stakeholder Representatives to address audience and support needs
- Coordinates with Product Managers to ensure communications accurately represent product changes

---

## Customer Success / Stakeholder Representative

### Role Summary
Customer Success / Stakeholder Representatives bring customer, support, and business stakeholder perspectives into planning, release readiness, and adoption decisions.

### Responsibilities
- Represent customer and support-team needs and likely impact
- Identify customer readiness, adoption, and support concerns
- Provide feedback on rollout and support readiness
- Relay stakeholder feedback to the delivery team

### Interactions
- Partners with Product Managers on customer impact and prioritization
- Coordinates with the Project Manager on stakeholder alignment and concerns
- Works with the Communications / Change Management Lead on audience-specific messaging and with the Release Manager on support readiness

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When responsibilities overlap, the role identified as the primary owner is accountable for the activity; supporting roles provide coordination, expertise, or validation as described above.
