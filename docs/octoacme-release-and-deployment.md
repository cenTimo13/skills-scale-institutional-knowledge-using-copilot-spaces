# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged (validated by QA Lead and Product Manager)
- Passing CI and security scans (Technical Lead verifies)
- Release notes drafted (PM with input from Product Manager)
- Rollback / mitigation plan documented (Technical Lead and PM)
- Smoke tests prepared (QA Lead)
- User-facing documentation updated (UX Designer and Technical Writer, if applicable)
- Stakeholder communication plan ready (Stakeholder Champion and PM)

## Deployment Checklist
- [ ] Deployment window scheduled (if needed) — PM coordinates
- [ ] Backup or snapshot (if applicable) — Technical Lead ensures
- [ ] Deploy to staging and run smoke tests — QA Lead validates
- [ ] Deploy to production (automated pipeline preferred) — Technical Lead oversees
- [ ] Run post-deploy verifications — QA Lead and Developers
- [ ] Announce release to stakeholders and support — Stakeholder Champion and PM
- [ ] Monitor initial usage and error rates — Technical Lead and Developers

For role details, see [Roles and Personas](octoacme-roles-and-personas.md).

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (Technical Lead coordinates)
  - Rollback to last known-good release if necessary (Technical Lead executes)
  - Triage root cause and capture action items (Technical Lead, QA Lead, Developers)
  - Communicate status to stakeholders (PM and Stakeholder Champion)
  - Post-incident blameless retrospective scheduled (Scrum Master facilitates)

For escalation paths, see [Risk Management & Communication](octoacme-risks-and-communication.md).

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

---

**Process Improvement**: Release role accountability enhanced per [Issue #4](https://github.com/cenTimo13/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
