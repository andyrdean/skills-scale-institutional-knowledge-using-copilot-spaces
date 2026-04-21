# OctoAcme Project Management Docs

This folder is the source of truth for OctoAcme project management processes, roles, workflows, and delivery standards.

OctoAcme runs delivery through a lightweight lifecycle: initiation, planning, execution, release, and close/retrospective. Work starts with a project one-pager that defines the problem, goals, success metrics, stakeholders, and early risks, followed by a clear decision gate to confirm priority, alignment, and team capacity before deeper planning begins. Planning then turns approved initiatives into a prioritized backlog with acceptance criteria, sizing, milestones, dependencies, and a documented Definition of Done.

Execution is managed through repeatable workflows that keep progress visible and quality high. Teams use a project board flow of Backlog -> Ready -> In Progress -> In Review -> QA -> Done, and a pull request workflow that favors small PRs linked to issues and acceptance criteria, requires CI linting/testing, and includes approval before merge based on team policy. Risks and dependencies are tracked in a risk register (impact, likelihood, owner, mitigation, status) and reviewed during weekly syncs so issues can be escalated early.

Roles and communication are explicit across the lifecycle. Project Managers coordinate delivery plans, timelines, risks, and stakeholder reporting; Product Managers/Product Leads own outcomes, prioritization, and success measurement; Developers and QA/Testing drive implementation quality and acceptance; and Stakeholders provide inputs and decisions. Cadence includes standups, weekly delivery syncs, demos/reviews at sprint or milestone boundaries, and regular stakeholder updates using shared templates, with escalation paths from team triage to PM/Product Lead to sponsor-level support (plus a dedicated security-incident path).

Quality assurance is embedded from planning through release. Teams align on Definition of Done, implement unit/integration tests and end-to-end smoke coverage for critical flows, and rely on CI linting/testing and security scans before release. Manual QA is used where needed for feature acceptance, while release checklists, post-deploy verification, and rollback plans reduce risk in production; retrospectives then convert learnings into owned, time-bound improvements.

## Index

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- [OctoAcme — Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme — Project Planning](./octoacme-project-planning.md)
- [OctoAcme — Execution & Tracking](./octoacme-execution-and-tracking.md)
- [OctoAcme — Risk Management & Communication](./octoacme-risks-and-communication.md)
- [OctoAcme — Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme — Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [OctoAcme Personas](./octoacme-roles-and-personas.md)
- [OctoAcme — Definition of Done & Role Handoffs](./octoacme-definition-of-done-and-role-handoffs.md)
