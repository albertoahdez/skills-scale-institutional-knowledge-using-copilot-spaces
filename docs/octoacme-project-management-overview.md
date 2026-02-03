# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
For detailed role descriptions, responsibilities, and interaction patterns, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

- Project Manager (PM): coordinates delivery, schedules, risk, communications.
- Product Manager (PdM): defines outcomes, prioritizes backlog, and measures success.
- Developers: implement features, collaborate on design and testability.
- QA/Testing: validate quality and acceptance criteria.
- UX Designer: design user experiences and validate usability.
- Data Analyst: track metrics and provide insights.
- DevOps Engineer: manage CI/CD, infrastructure, and deployments.
- Technical Writer: create and maintain documentation.
- Customer Support: provide user support and collect feedback.
- Stakeholders: provide inputs and approvals.

See [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) for complete persona definitions including RACI guidance for common activities.

## Key Artifacts
Each artifact should have a **named owner** and **primary backup** to ensure accountability and continuity.

- Project Charter / One-pager (Owner: PM, Backup: PdM)
- Roadmap and Release Plan (Owner: PdM, Backup: PM)
- Sprint/Iteration Backlog (Owner: PM/Tech Lead, Backup: PdM)
- Acceptance Criteria & Definition of Done (Owner: PdM, Backup: Tech Lead)
- Risk Register (Owner: PM, Backup: Project Sponsor)
- Retrospective notes and action items (Owner: PM, Backup: Team Lead)

For templates and checklists, see [templates/](./templates/) and [checklists/](./checklists/).

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

For a detailed communication matrix template, see [templates/communication-matrix.md](./templates/communication-matrix.md).

## RACI Practices
RACI (Responsible, Accountable, Consulted, Informed) matrices help clarify who does what on project activities.

- **Responsible**: Does the work
- **Accountable**: Ultimately answerable for completion and quality (typically one person)
- **Consulted**: Provides input before decisions/actions
- **Informed**: Kept up-to-date on progress

**Where to document role assignments:**
- Include RACI or role assignments in your project README or one-pager
- Reference [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) for standard RACI guidance by role
- Customize based on your team structure and project needs

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
