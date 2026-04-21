# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based) (Owner: PM)
- Use a single source of truth (project README or release doc) for status
- PdM owns product outcome updates and prioritization changes.
- Support/Success Engineer owns support-facing updates and escalation context.

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary (Owner: PM)
- Actions being taken (Owner: PM + Release Manager)
- Expected timeline (Owner: PM)
- Customer/support update (Owner: Support/Success Engineer)
- Security impact statement when applicable (Owner: Security Champion)
- Post-incident blameless retrospective scheduled (Owner: PM)

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents: Team-level -> Security Champion -> PM + Release Manager -> Sponsor/Security on-call
