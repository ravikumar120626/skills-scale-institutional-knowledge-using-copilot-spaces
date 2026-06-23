# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This directory contains our standardized processes, templates, and guidance for running projects from initiation through delivery and continuous improvement.

## Overview of OctoAcme Processes

OctoAcme follows a structured project lifecycle designed to maximize customer value, ensure clear ownership and communication, and deliver work iteratively. Our approach is grounded in these core principles:

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Project Lifecycle

1. **Initiation**: Define the problem, identify stakeholders, confirm business need, and create a lightweight one-pager to authorize planning.
2. **Planning**: Turn approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, and milestones.
3. **Execution & Tracking**: Build, test, and review using project boards, small PRs, CI checks, daily standups, and weekly delivery syncs.
4. **Release & Deployment**: Meet pre-release requirements, run smoke tests, deploy to production, and follow rollback playbooks.
5. **Retrospectives & Continuous Improvement**: Capture learnings, identify action items, and measure the impact of improvements.
6. **Risk & Communication**: Maintain a risk register, communicate weekly status, escalate blockers, and keep stakeholders informed.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, measures success
- **Developers**: Implement features, write tests, participate in design and code reviews
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and business context

For detailed role descriptions, see [octoacme-roles-and-personas.md](#octoacme-roles-and-personasmd).

## Documentation Structure

| Document | Purpose |
|----------|---------|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level introduction to OctoAcme processes, roles, artifacts, and how to use these docs |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Project initiation guide, one-pager template, and decision gates |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Planning activities, backlog template, sprint planning, and checklists |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Team rhythm, workflows, PR guidelines, QA approach, and execution checklist |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release types, pre-release requirements, deployment checklist, and rollback playbook |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, action item tracking, and continuous improvement culture |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk register, risk lifecycle, stakeholder communication, and escalation paths |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Detailed role descriptions and personas used throughout the exercises |

## Quick Links

- **Starting a new project?** Begin with [octoacme-project-initiation.md](./octoacme-project-initiation.md)
- **Planning your work?** See [octoacme-project-planning.md](./octoacme-project-planning.md)
- **Tracking progress?** Use [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)
- **Ready to release?** Review [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)
- **Completing a project?** Run a retrospective using [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)
- **Managing risks or communicating status?** Reference [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)

## Key Templates

Throughout these documents you'll find templates for common artifacts:

- **Project One-pager**: Problem, goal, success metrics, stakeholders, timeline, risks, team roles
- **Backlog Item**: Title, description, acceptance criteria, priority, estimate, owner
- **Definition of Done**: Agreed standards for what "complete" means
- **Risk Register**: ID, description, impact, likelihood, owner, mitigation, status
- **Weekly Status**: Progress, next steps, risks & blockers, decisions needed
- **Release Notes**: Release name, date, summary, changes, migrations, known issues

## Using These Docs in Copilot Spaces

These documents are designed to be used as grounded context in Copilot Spaces. Add them to your Copilot Space configuration to:

- Get role-specific guidance based on your persona (PM, Developer, Product Manager)
- Reference process checklists and templates when working on issues or PRs
- Standardize how your team plans, executes, and delivers work

See [octoacme-project-management-overview.md](./octoacme-project-management-overview.md#how-to-use-these-docs) for more details on integrating these docs with Copilot Spaces.

## Getting Started

1. **New team member?** Start with [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for a complete overview
2. **Starting a project?** Follow the workflow in [octoacme-project-initiation.md](./octoacme-project-initiation.md)
3. **Need a specific template?** Search for "Template" in the relevant document
4. **Have a question about roles?** Check [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)

## Contributing

To suggest updates or additions to these process documents:

1. Open an issue using the "Add Content to Project Management Process Docs" template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`
2. Describe the content you want to add and why it's needed
3. Submit a pull request with the proposed changes for team review

---

**Last Updated**: 2026-06-23  
**Maintained by**: OctoAcme Project Management Team
