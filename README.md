# OctoAcme Project Management Docs

This repository contains the core project management guidance used by OctoAcme. The documents are designed to help teams initiate, plan, execute, release, and improve work in a consistent and repeatable way.

## Overview

OctoAcme uses a clear lifecycle for project work: initiation, planning, execution, release, and close/retrospective. During initiation, teams confirm the business need, stakeholders, success criteria, timeline, and go/no-go decision. Once the initiative is approved, the planning phase converts it into a prioritized backlog, estimates, milestones, and a Definition of Done. Throughout execution, the team tracks work, manages risks, communicates progress, and escalates blockers when needed.

The project approach emphasizes customer value, iterative delivery, shared ownership, and measurable outcomes. Delivery teams use a project board to make status visible and a regular cadence of standups, planning sessions, reviews, and stakeholder updates to stay aligned. Quality is treated as a first-class concern through automated checks, testing, and manual validation when needed.

## Roles and responsibilities

The process docs define several key roles:

- Project Manager (PM): coordinates schedules, risks, communications, and project health
- Product Manager / Product Lead: defines the problem, priorities, success metrics, and trade-offs
- Developers: implement features, maintain code quality, and contribute to tests and design reviews
- QA / Testing: validate quality and acceptance criteria
- Stakeholders: provide input, alignment, and approvals

These roles work together across the lifecycle to ensure clarity, accountability, and delivery continuity.

## Key workflows

OctoAcme's workflow begins with a lightweight project charter or one-pager that captures the problem, goal, success metrics, stakeholders, timeline, and risks. The team then creates a backlog with acceptance criteria, estimates, owners, and dependencies, and agrees on a release plan and milestones.

During execution, daily standups focus on progress, blockers, and cross-team dependencies; weekly delivery syncs surface status and risks; demos and sprint reviews provide visibility into outcomes; and escalation paths move from the team to the PM, then to the Product Lead and sponsor as needed. The risk register is updated continuously so teams can monitor likelihood, impact, ownership, and mitigation.

## Quality and release practices

Quality is integrated throughout the process. New logic should be supported by unit tests, integration tests where applicable, and smoke tests for critical user flows. CI is expected to run tests and linting, and security scans should be part of the validation path. Before merging, pull requests should normally include the issue link and acceptance criteria, stay small where possible, and require an approval per team policy.

Before release, teams confirm all acceptance criteria are met, run CI and security checks, prepare release notes, and verify rollback readiness. Deployments should include staging validation and post-deploy verification, followed by stakeholder and support communication. After each sprint, milestone, or significant incident, the team closes the loop with a retrospective and tracks improvement actions with owners and due dates.

## Documents in this repo

- [OctoAcme Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

## Recommended starting points

If you are new to the project, start with:

1. [OctoAcme Project Management Overview](docs/octoacme-project-management-overview.md)
2. [Project Initiation Guide](docs/octoacme-project-initiation.md)
3. [Project Planning](docs/octoacme-project-planning.md)
4. [Execution & Tracking](docs/octoacme-execution-and-tracking.md)

These documents provide the core working model for how OctoAcme aligns teams, tracks progress, and delivers value.
