# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process guide. This directory centralizes the workflows, roles, artifacts, and practices used to plan, deliver, release, and improve cross-functional projects.

## Quick Overview

OctoAcme follows a structured, iterative project lifecycle:

1. **Initiation** — Validate the business need, define measurable outcomes, identify stakeholders, and secure approval to proceed.
2. **Planning** — Turn the approved initiative into a prioritized backlog, define acceptance criteria and the Definition of Done, estimate work, and map dependencies and milestones.
3. **Execution and tracking** — Deliver small increments through the project board, monitor progress and risks, and resolve blockers through regular team and stakeholder communication.
4. **Release and deployment** — Verify quality, complete release preparation, deploy safely, perform post-deployment checks, and communicate the outcome.
5. **Retrospective and improvement** — Capture lessons after sprints, releases, milestones, or incidents and convert them into owned, time-bound improvement actions.

## Core Principles

- **Customer-first:** Prioritize customer value, usability, and measurable outcomes.
- **Iterative delivery:** Deliver small, testable increments so the team can learn and adjust.
- **Clear ownership:** Give each project a named Project Manager and Product Lead, with responsibilities understood across the team.
- **Data-informed decisions:** Use success metrics, delivery metrics, dashboards, and feedback to guide priorities and improvements.
- **Psychological safety:** Encourage candid feedback, blameless learning, and continuous improvement.

## Documentation Map

### Getting Started

- [**Project Management Overview**](./octoacme-project-management-overview.md) — Introduction to OctoAcme's scope, principles, roles, key artifacts, lifecycle, and communication cadence.
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Responsibilities, goals, and typical communication patterns for Developers, Product Managers, and Project Managers.

### Project Lifecycle

- [**Project Initiation**](./octoacme-project-initiation.md) — Validate a project idea, create the Project One-pager, align stakeholders, identify initial risks and resources, and make the go/no-go decision for planning.
- [**Project Planning**](./octoacme-project-planning.md) — Create the backlog, define acceptance criteria and the Definition of Done, estimate scope, identify dependencies, and establish the release and milestone plan.
- [**Execution and Tracking**](./octoacme-execution-and-tracking.md) — Manage daily delivery using the project board, standups, delivery syncs, demos, quality checks, metrics, and blocker escalation.
- [**Release and Deployment**](./octoacme-release-and-deployment.md) — Prepare releases, complete deployment checks, run smoke tests and post-deployment verification, communicate releases, and respond to deployment issues.
- [**Retrospective and Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives, follow up on action items, measure their impact, and make incremental improvements.

### Cross-cutting Concerns

- [**Risk Management and Communication**](./octoacme-risks-and-communication.md) — Maintain the risk register, manage dependencies, communicate status and incidents, and follow escalation paths.

## Key Workflows and Quality Practices

Work is managed on a project board with stages such as **Backlog**, **Ready**, **In Progress**, **In Review**, **QA**, and **Done**. Pull requests should be small where possible, link to the relevant issue, and include acceptance criteria. Automated tests, linting, and security scans run in CI before review, with at least one approval required according to team policy. Teams use unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, and manual QA when feature acceptance requires it.

Before a release, acceptance criteria must be complete, CI and security checks must pass, release notes must be drafted, a rollback or mitigation plan must be documented, and staging smoke tests must be prepared. Risks are recorded with an owner, impact, likelihood, mitigation, and status, then reviewed during weekly syncs. Blockers escalate from team-level triage to the Project Manager, Product Lead, and sponsor when they have wider business impact.

## Using This Documentation

- **New team members:** Start with [Project Management Overview](./octoacme-project-management-overview.md), then review [Roles and Personas](./octoacme-roles-and-personas.md).
- **Starting a project:** Follow [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) before beginning delivery.
- **Running delivery:** Use [Execution and Tracking](./octoacme-execution-and-tracking.md) alongside [Risk Management and Communication](./octoacme-risks-and-communication.md).
- **Preparing a release:** Follow [Release and Deployment](./octoacme-release-and-deployment.md) and confirm the pre-release and deployment checklists are complete.
- **After a milestone or incident:** Use [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to capture learning and track follow-up actions.
- **Using Copilot Spaces:** Add the relevant process documents to `.copilot/` when you want Copilot to use them as project-management context.

Keep project-specific plans, decisions, risks, and status updates in the project repository so the documentation remains a shared, current source of truth.
