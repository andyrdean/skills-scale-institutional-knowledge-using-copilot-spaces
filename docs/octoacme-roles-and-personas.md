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

## QA/Test Lead

### Role Summary
QA/Test Leads own the test strategy and quality gates across the delivery lifecycle. They ensure acceptance criteria are validated before work is moved to done or included in a release.

### Responsibilities
- Define and maintain the project test strategy (unit, integration, and end-to-end coverage)
- Validate acceptance criteria and regression risk before sign-off
- Coordinate manual QA where automation is not sufficient
- Track defects, triage quality risks, and partner with Developers on remediation

### Goals
- Prevent escaped defects in critical user flows
- Keep quality signals visible and actionable for the team
- Improve release confidence through repeatable quality gates

### Typical Communication
- Test plan and coverage updates during planning and sprint reviews
- Defect triage notes in project boards/issues
- Release go/no-go quality status with PM, PdM, and Release Manager

### Key Interactions
- **Developers:** aligns on testability, defect fixes, and regression coverage.
- **Product Managers (PdM):** confirms acceptance criteria are testable and complete.
- **Project Managers (PM):** communicates quality risks, blockers, and readiness.
- **Release Manager:** provides quality sign-off for deployment decisions.
- **UX/UI Designer:** validates UX behavior and accessibility in test scenarios.

---

## UX/UI Designer

### Role Summary
UX/UI Designers shape user experience, interaction patterns, and interface consistency so that delivered features are usable, accessible, and aligned to product goals.

### Responsibilities
- Produce wireframes, flows, prototypes, and UI specifications
- Define usability and accessibility expectations for feature work
- Partner with Developers during implementation to preserve design intent
- Incorporate user feedback into iterative design updates

### Goals
- Improve usability and task completion outcomes
- Reduce rework caused by unclear or late design decisions
- Ensure accessibility and UI consistency across releases

### Typical Communication
- Design reviews with Developers, PM, and PdM
- Annotated prototypes and acceptance notes in planning artifacts
- Feedback summaries from demos and support insights

### Key Interactions
- **Developers:** clarifies implementation details and edge-case behavior.
- **Product Managers (PdM):** aligns design decisions to user and business outcomes.
- **Project Managers (PM):** coordinates design milestones and dependencies.
- **QA/Test Lead:** aligns on test scenarios for UX and accessibility validation.
- **Support/Success Engineer:** reviews recurring user pain points for design improvements.

---

## Release Manager

### Role Summary
Release Managers coordinate release readiness, deployment execution, and cross-functional communication to ensure predictable, low-risk releases.

### Responsibilities
- Own release readiness and deployment checklists
- Coordinate release timing, cut scope, and go/no-go decisions
- Ensure rollback and incident-response readiness before deployment
- Publish release communications and hand-offs to stakeholders and support teams

### Goals
- Deliver reliable releases with minimal disruption
- Make release ownership and decision points explicit
- Improve deployment repeatability and traceability

### Typical Communication
- Release readiness updates and launch timelines
- Go/no-go decisions in release channels/meetings
- Post-release summaries and follow-up actions

### Key Interactions
- **Developers:** confirms deployable scope and technical readiness.
- **Product Managers (PdM):** confirms release scope and customer impact.
- **Project Managers (PM):** aligns release schedule, dependencies, and stakeholders.
- **QA/Test Lead:** consumes quality sign-off before production deployment.
- **Support/Success Engineer:** coordinates support readiness and escalation coverage.
- **Security Champion:** validates security controls and incident readiness for release.

---

## Support/Success Engineer

### Role Summary
Support/Success Engineers bridge delivery teams and users by triaging issues, capturing field feedback, and helping the team respond quickly after release.

### Responsibilities
- Triage customer-reported issues and route them to the right owners
- Maintain support runbooks and known-issue tracking
- Feed recurring support patterns into backlog refinement
- Support incident communication and post-release health monitoring

### Goals
- Reduce time-to-triage and time-to-resolution for customer-impacting issues
- Improve customer experience through clear, timely updates
- Turn support insights into product and process improvements

### Typical Communication
- Daily/weekly support trend summaries
- Escalation updates during incidents or post-release stabilization
- Input to retrospectives and planning sessions

### Key Interactions
- **Developers:** shares reproducible issue details and validates fixes.
- **Product Managers (PdM):** feeds user pain points and prioritization signals.
- **Project Managers (PM):** aligns on escalation status and stakeholder messaging.
- **Release Manager:** confirms support readiness and post-release monitoring.
- **QA/Test Lead:** shares defect patterns that should become regression tests.

---

## Security Champion

### Role Summary
Security Champions embed security practices into planning, execution, and release decisions, and coordinate security-focused escalation when incidents occur.

### Responsibilities
- Advise on threat modeling and secure design decisions
- Ensure security checks/scans are included in delivery workflows
- Review high-risk changes and coordinate remediation planning
- Lead security incident escalation coordination with PM and Release Manager

### Goals
- Reduce security risk before release
- Improve security awareness across the delivery team
- Ensure consistent, timely response to security incidents

### Typical Communication
- Security risk notes in planning and risk reviews
- CI/security scan status in release readiness checks
- Security incident updates and post-incident follow-ups

### Key Interactions
- **Developers:** provides secure coding and remediation guidance.
- **Product Managers (PdM):** aligns security requirements with product priorities.
- **Project Managers (PM):** escalates and tracks security risks and decisions.
- **Release Manager:** confirms security readiness before go-live.
- **Support/Success Engineer:** coordinates customer-facing updates for security incidents.
- **QA/Test Lead:** aligns on security-focused test coverage and validation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
