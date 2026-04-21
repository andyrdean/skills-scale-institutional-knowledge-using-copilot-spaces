# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (Owner: PdM + Developers)
- Passing CI and security scans (Owner: Developers + Security Champion)
- QA sign-off recorded (Owner: QA/Test Lead)
- Release notes drafted (Owner: Release Manager)
- Rollback / mitigation plan documented (Owner: Release Manager + PM)
- Smoke tests prepared (Owner: QA/Test Lead + Developers)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — Owner: Release Manager
- [ ] Backup or snapshot (if applicable) — Owner: Developers
- [ ] Deploy to staging and run smoke tests — Owner: Developers + QA/Test Lead
- [ ] Deploy to production (automated pipeline preferred) — Owner: Release Manager + Developers
- [ ] Run post-deploy verifications — Owner: QA/Test Lead + Support/Success Engineer
- [ ] Announce release to stakeholders and support — Owner: Release Manager + PM

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Owner: Release Manager)
  - Rollback to last known-good release if necessary (Owner: Developers + Release Manager)
  - Route security-impacting incidents to Security Champion immediately (Owner: Security Champion)
  - Triage root cause and capture action items (Owner: PM + Support/Success Engineer)

## Release Communication Ownership
- Internal launch update: Release Manager
- Stakeholder status update: PM + PdM
- Support readiness and known issues update: Support/Success Engineer
- Security update for security-impacting releases/incidents: Security Champion

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
