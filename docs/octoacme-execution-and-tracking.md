# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Board ownership and hand-offs:
  - Backlog, Ready: PdM defines scope and PM confirms delivery sequencing.
  - In Progress, In Review: Developers implement and review with UX/UI Designer input when needed.
  - QA: QA/Test Lead validates acceptance criteria, regression risk, and release quality status.
  - Done: PM records completion, and Release Manager tracks readiness for deployment.
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- QA/Test Lead owns test strategy and acceptance validation.
- Developers own unit tests for new logic and integration tests where applicable.
- QA/Test Lead and Developers run end-to-end smoke tests for critical flows before release.
- Security Champion ensures security scanning in CI is active and reviewed.
- UX/UI Designer and QA/Test Lead coordinate manual QA for usability/accessibility acceptance when needed.

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
