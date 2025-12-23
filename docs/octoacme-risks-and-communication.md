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
- **Identify**: during planning and ongoing execution (all roles contribute)
- **Assess**: estimate impact and likelihood (PM with Technical Lead, QA Lead)
- **Mitigate**: reduced via actions, contingency plans (role-specific owners assigned)
- **Monitor**: review at weekly syncs and update status (PM tracks, Scrum Master facilitates)

### Role-Specific Risk Ownership
- **Technical risks**: Technical Lead
- **Quality risks**: QA Lead  
- **User experience risks**: UX Designer
- **Requirements/scope risks**: Business Analyst and Product Manager
- **Stakeholder/organizational risks**: Stakeholder Champion and PM
- **Delivery/schedule risks**: PM and Scrum Master

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Stakeholder Champion** coordinates feedback loops and ensures stakeholder voices are heard
- **PM** maintains the communication plan and status updates
- **Business Analyst** translates technical details into business context for stakeholders

For stakeholder roles and responsibilities, see [Roles and Personas](octoacme-roles-and-personas.md).

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
Clear escalation paths with role accountability:

### Technical Escalation
- Developer → Technical Lead → PM → Product Manager (PdM) → Sponsor

### Quality/Release Escalation
- QA Lead → Technical Lead → PM → Product Manager (PdM) → Sponsor

### Requirements/Scope Escalation
- Developer/Designer → Business Analyst → Product Manager (PdM) → PM → Sponsor

### Organizational/Blockers Escalation
- Team member → Scrum Master → PM → Product Manager (PdM) → Sponsor

### Stakeholder Concerns
- Stakeholder Champion → PM → Product Manager (PdM) → Sponsor

### Security Incidents
- For security incidents, follow the security incident runbook and notify Security on-call
- Immediately escalate to Technical Lead and PM

---

**Process Improvement**: Escalation paths and role clarity enhanced per [Issue #4](https://github.com/cenTimo13/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4).
