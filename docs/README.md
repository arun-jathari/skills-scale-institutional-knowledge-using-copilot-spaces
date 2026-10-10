# OctoAcme Project Management Documentation

## Overview

OctoAcme runs projects using a proven, customer-first methodology focused on iterative delivery, clear ownership, and data-informed decisions. This documentation centralizes all processes, roles, and best practices to ensure consistent, repeatable project execution across the organization.

OctoAcme's project management approach is built around a clear lifecycle: initiate the work with a one-pager and stakeholder alignment, plan the delivery with backlog prioritization and milestone mapping, execute in iterative increments with visible ownership, and then release and retrospect. The process emphasizes turning ideas into measurable outcomes, defining success metrics early, and using lightweight artifacts like project charters, risk registers, and definition-of-done checklists to keep planning and execution aligned. This gives teams a consistent way to move from problem definition to delivery without losing visibility into scope, dependencies, or stakeholder expectations.

The operating model centers on distinct roles and responsibilities. Product managers define business value, prioritize the backlog, and measure outcomes; project managers coordinate timelines, communications, risks, and dependencies; developers build and test features; QA validates acceptance criteria; and stakeholders provide input, approvals, and business context. The framework is intentionally cross-functional, with a strong expectation that each project has named owners and that work is tracked through a shared project board. This makes accountability clear while supporting iterative delivery.

Quality assurance is treated as part of delivery, not a final checkpoint. Teams are expected to document acceptance criteria, use testing at multiple levels (unit, integration, and end-to-end smoke tests), run CI checks including linting and security scans, and review work through pull requests. Together, these practices create a disciplined but practical model for delivering customer value with visibility, accountability, and continuous improvement.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Ship small, testable increments
- **Clear ownership**: Every project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle & Guides

1. **[Project Initiation](octoacme-project-initiation.md)** — Validate ideas and authorize work
   - Confirm business need and measurable outcomes
   - Identify stakeholders and champions
   - Define success criteria and initial timeline

2. **[Project Planning](octoacme-project-planning.md)** — Break work into actionable backlog
   - Create prioritized backlog with acceptance criteria
   - Identify dependencies and integration points
   - Define Definition of Done and release plan

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery
   - Use project board with standard columns
   - Follow pull request workflow with automated testing
   - Track velocity and key metrics

4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Deploy to production safely
   - Pre-release requirements and checklist
   - Deployment procedures and rollback plans
   - Release notes and post-deploy verification

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings
   - Conduct retrospectives after sprints and releases
   - Track and measure action item impact
   - Foster continuous improvement culture

## Key References

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level framework, core roles, and key artifacts
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Handle risks, dependencies, and stakeholder updates
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and goals by role (Developer, Product Manager, Project Manager)

## Communication Cadence

- **Daily standups** (15 min) — Progress, blockers, dependencies
- **Weekly PM sync** — Alignment and risk review between PM and Product Lead
- **Twice-weekly delivery team standups** — Status and next steps (or as agreed)
- **Monthly stakeholder updates** — High-level progress and key signals
- **Ad-hoc escalations** — For blockers and business-impacting issues

## Key Artifacts

- **Project Charter / One-pager** — Problem statement, goals, success metrics, stakeholders
- **Project Backlog** — Prioritized list of work with acceptance criteria and estimates
- **Risk Register** — Tracked risks with impact, likelihood, owner, and mitigation plan
- **Project Board** — Visible tracking with columns: Backlog, Ready, In Progress, In Review, QA, Done
- **Release Plan** — Timeline and milestones for delivery
- **Retrospective Notes** — Learnings and action items from sprints and releases

## How to Use These Docs

- **Onboarding**: Start with the Project Management Overview to understand OctoAcme's framework
- **Starting a new project**: Follow the Initiation and Planning guides in sequence
- **During execution**: Refer to Execution & Tracking and Risk Management & Communication for day-to-day guidance
- **Before releasing**: Check the Release & Deployment guide for pre-release requirements
- **After completion**: Use the Retrospective guide to capture learnings
- **Project repository**: Keep your Project Charter updated in your project repo and link to relevant guides in your project README or `.copilot/` folder

## Contributing

To propose updates, additions, or clarifications to these process docs, use the **[Process Doc Update issue template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)**.

When proposing updates, consider:
- Is this addressing a gap or improving clarity?
- Does it align with existing OctoAcme principles?
- Have relevant stakeholders reviewed it?

---

*Last updated: October 2026*
*For questions or feedback, open an issue using the Process Doc Update template.*
