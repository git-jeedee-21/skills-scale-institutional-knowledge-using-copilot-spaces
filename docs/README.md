# OctoAcme Project Management Docs

This folder contains OctoAcme's project management guidance for initiating, planning, executing, releasing, and improving work across the organization.

## Project management process overview

OctoAcme uses a simple lifecycle for project delivery: initiation, planning, execution, release, and retrospective. During initiation, teams confirm the business need, measurable outcomes, stakeholders, timeline, risks, and resource needs; if the work is approved, it moves into planning. Planning turns the approved initiative into a prioritized backlog with acceptance criteria, estimates, milestones, and an agreed Definition of Done.

Once work is underway, execution is driven by a visible project board, regular standups, planned syncs, and demos that keep progress, blockers, and dependencies transparent. Roles are kept clear and accountable: Project Managers coordinate delivery and communications, Product Managers define outcomes and priorities, developers implement work, QA validates quality, and stakeholders provide alignment and approvals. Risks are tracked in a risk register, with owners, mitigation plans, and escalation paths defined as needed.

Quality is built into the workflow from the start. Unit testing, integration testing where appropriate, and smoke tests for critical flows help validate the work. CI should run automated tests and linting, and security scans should be included before review. Pull requests should stay small where possible, include issue references and acceptance criteria, and require approval before merging.

When a release is ready, the team verifies acceptance criteria, security checks, deployment readiness, and rollback plans. After release, retrospectives capture what went well, what needs improvement, and the action items required to keep improving the process.

## Documents

- [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Recommended reading order

1. [OctoAcme Project Management Overview](octoacme-project-management-overview.md)
2. [Project Initiation Guide](octoacme-project-initiation.md)
3. [Project Planning](octoacme-project-planning.md)
4. [Execution & Tracking](octoacme-execution-and-tracking.md)
5. [Risk Management & Communication](octoacme-risks-and-communication.md)
6. [Release & Deployment Guide](octoacme-release-and-deployment.md)
7. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
8. [Roles and Personas](octoacme-roles-and-personas.md)

This README acts as the entry point for the OctoAcme process library and should be used as the default starting point for onboarding and day-to-day project guidance.
