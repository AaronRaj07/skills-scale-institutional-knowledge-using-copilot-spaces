# OctoAcme Project Management Docs

## Overview

OctoAcme project management guidance centralizes lightweight, outcome-focused processes to help teams initiate, plan, execute, and iterate on work. Projects start with a one-pager to align stakeholders, move into iterative planning with prioritized backlogs and clear acceptance criteria, and follow a regular cadence of execution, review, and retrospective. Risks and dependencies are tracked in a simple risk register and escalated through defined paths. Continuous improvement is encouraged via action items, retrospectives, and documented process updates.

## Project Management Approach

OctoAcme follows a structured, lifecycle-based approach grounded in five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions.
- **Iterative delivery**: Deliver small, testable increments rather than large, infrequent releases.
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Manager (PdM) with defined responsibilities.
- **Data-informed decisions**: Measure impact and iterate based on evidence and metrics.
- **Psychological safety**: Encourage feedback, learning, and continuous process improvement.

### Project Lifecycle

All OctoAcme projects flow through five phases:

1. **Initiation** — Validate business need, align stakeholders, and create a lightweight one-pager
2. **Planning** — Break work into shippable increments with acceptance criteria and release milestones
3. **Execution** — Build, test, review, and iterate through daily standups and sprint cycles
4. **Release** — Deploy to production with smoke tests, verification, and stakeholder communication
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Execution Rhythm

- **Daily standups** (15 min) — Progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, discuss risks, and flag constraints
- **Sprint planning** — Pull work that meets Definition of Done with clear acceptance criteria
- **Demos and reviews** — Demo completed work at the end of each sprint or milestone
- **Retrospectives** — Capture learnings and improvements after sprints or major milestones

### Quality & Testing

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI pipelines
- Manual QA for feature acceptance when needed

---

## Process Documentation

This folder contains detailed guidance for each phase and aspect of OctoAcme project management:

### Foundation & Strategy

- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts. Start here for a quick orientation.
- **[OctoAcme Roles & Personas](./octoacme-roles-and-personas.md)** — Detailed responsibilities, goals, and communication patterns for each role.

### Project Lifecycle Phases

- **[Project Initiation Guide](./octoacme-project-initiation.md)** — How to validate a new project idea, align stakeholders, and create an initial one-pager. Use this to kick off new initiatives.
- **[Project Planning](./octoacme-project-planning.md)** — How to break work into shippable increments, estimate scope, define acceptance criteria, and identify dependencies.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Day-to-day workflow, project board management, PR practices, testing, and blocker escalation.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardized process for releasing features to production, pre-release requirements, and rollback procedures.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, capture action items, and measure improvement.

### Cross-Cutting Concerns

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, assess, and mitigate risks; maintain a risk register; and communicate status and escalations to stakeholders.

---

## How to Use These Docs

### For New Team Members
1. Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) to understand the big picture.
2. Review [OctoAcme Roles & Personas](./octoacme-roles-and-personas.md) to understand your role and how you interact with others.
3. As you work on a project, refer to the phase-specific docs (Initiation, Planning, Execution, Release, Retrospective).

### For Project Managers
- Use the [Initiation Guide](./octoacme-project-initiation.md) to kick off new projects.
- Refer to [Project Planning](./octoacme-project-planning.md) during planning phases.
- Use [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day coordination.
- Consult [Risk Management & Communication](./octoacme-risks-and-communication.md) to maintain risk registers and stakeholder updates.

### For Product Managers
- Collaborate on [Initiation](./octoacme-project-initiation.md) to define success metrics and stakeholders.
- Use [Project Planning](./octoacme-project-planning.md) to prioritize and scope work.
- Refer to [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality and testing standards.

### For Developers
- Review [Execution & Tracking](./octoacme-execution-and-tracking.md) for PR workflow, testing, and CI requirements.
- Check [Release & Deployment Guide](./octoacme-release-and-deployment.md) before releases.
- Use [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) to provide feedback and improve processes.

---

## Key Artifacts & Templates

Across these docs, you'll find templates and checklists for:

- **Project One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Backlog Item Template** — Title, description, acceptance criteria, priority, estimate, owner
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Definition of Done** — Criteria for marking work complete (tests, review, documentation, etc.)
- **Weekly Status Template** — Progress, next steps, risks, decisions needed
- **Release Notes Template** — Release name, date, summary, notable changes, known issues

---

## Contributing to These Docs

If you'd like to improve, add, or update OctoAcme project management guidance, open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template. This helps us keep our processes clear, aligned, and continuously improving.
