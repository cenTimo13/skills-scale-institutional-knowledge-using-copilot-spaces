# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- **Daily standups** (15 min, facilitated by Scrum Master) — focus on progress, blockers, dependencies
- **Weekly delivery sync** (PM and Technical Lead) — show progress, updates, and flagged risks
- **Demo/Review** at the end of each sprint or milestone (all roles, presented to stakeholders)
- **Backlog refinement** (PdM, Business Analyst, Developers, QA Lead, UX Designer)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- **Unit tests** for new logic (Developers)
- **Integration tests** where applicable (Developers with QA Lead guidance)
- **End-to-end smoke tests** for critical flows before release (QA Lead)
- **Security scanning** in CI (Technical Lead ensures configuration)
- **Manual QA** for feature acceptance when needed (QA Lead coordinates)
- **Usability testing** for user-facing features (UX Designer with QA Lead)

See [Roles and Personas](octoacme-roles-and-personas.md) for detailed testing responsibilities.

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
Clear escalation paths ensure blockers are resolved quickly:

- **Level 1: Team-level triage** in daily standup (Scrum Master facilitates)
  - Technical blockers → Technical Lead
  - Requirements clarity → Business Analyst or Product Manager
  - Resource/capacity → Scrum Master and PM
- **Level 2: Cross-team escalation** (PM escalates to Product Lead and dependent teams)
  - Organizational impediments → PM with Scrum Master
  - Stakeholder decisions → Stakeholder Champion
- **Level 3: Executive escalation** for business-impacting issues (PM to Sponsor)

For communication templates, see [Risk Management & Communication](octoacme-risks-and-communication.md).

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint (Technical Lead)
- [ ] Regular demos scheduled (Scrum Master or PM)
- [ ] Risk register updated weekly (PM)
- [ ] Quality gates defined (QA Lead)
- [ ] Design handoff process established (UX Designer)

---

**Process Improvement**: Execution clarity and role assignments enhanced per [Issue #4](https://github.com/cenTimo13/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
