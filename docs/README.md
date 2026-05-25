# OctoAcme Project Management Docs

## Overview

This folder contains living documentation of OctoAcme's standardized project management processes. These guides cover everything from project initiation through retrospectives and continuous improvement, providing step-by-step guidance for every phase of the project lifecycle.

## OctoAcme Project Management Approach

OctoAcme follows a structured, stage-gate project management methodology designed to balance rigorous planning with iterative delivery. The framework spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During Initiation, teams validate business need through a lightweight Project One-pager that captures the problem statement, success metrics, stakeholders, and initial timeline. Only after sponsor and stakeholder alignment is secured does the project advance to Planning, where work is broken into prioritized, estimated backlog items with defined acceptance criteria and a detailed release plan.

OctoAcme operates with clearly defined roles that balance product vision with execution capability. **Product Managers** define what should be built by owning the vision, prioritizing the backlog, and measuring outcomes through data-driven metrics. **Project Managers** coordinate delivery, manage risks and dependencies, and maintain transparency across stakeholders through regular status reporting and escalation protocols. **Developers** implement features collaboratively, write tests and documentation, and participate in design reviews. This separation of concerns ensures that strategic decisions, tactical coordination, and hands-on delivery each receive dedicated ownership and expertise.

Communication and risk management are woven throughout OctoAcme's execution rhythm. The team maintains a **daily standup** (15 minutes) focused on progress and blockers, a **weekly delivery sync** to review progress and flag risks, and **monthly stakeholder updates** to keep sponsors informed. A formal **Risk Register** tracks identified risks with assessed impact, likelihood, mitigation plans, and owners, reviewed continuously at weekly syncs. Quality is protected through a rigorous **pull request workflow** with automated testing, linting, and mandatory code review before merge, complemented by unit tests, integration tests, and smoke tests for critical flows. The process concludes with a structured **Retrospective & Continuous Improvement** phase where teams capture learnings and assign specific action items, creating a feedback loop that strengthens the methodology over time.

## Core Principles

- **Customer-first**: prioritize customer value and usability
- **Iterative delivery**: deliver small, testable increments
- **Clear ownership**: each project has named Product Manager and Project Lead
- **Data-informed decisions**: measure impact and iterate based on evidence
- **Psychological safety**: encourage feedback and learning

## Process Documentation

Navigate to the appropriate guide based on your project phase or role:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Initial steps to validate, authorize work, and align stakeholders |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how features are released to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities in OctoAcme projects |

## Quick Start for New Team Members

1. **Start here**: Read [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction
2. **Find your role**: Check [Roles and Personas](octoacme-roles-and-personas.md) to understand responsibilities
3. **Follow the lifecycle**: Work through documents in phase order (Initiation → Planning → Execution → Release → Retrospective)
4. **Reference templates**: Each document includes checklists, templates, and examples you can adapt for your project

## Key Artifacts & Deliverables

- **Project Charter / One-pager**: approved by sponsor and stakeholders
- **Backlog & Sprint Plans**: prioritized, estimated, with clear acceptance criteria
- **Risk Register**: maintained and reviewed weekly
- **Release Notes & Deployment Checklists**: documented before production release
- **Retrospective Notes & Action Items**: captured and tracked for continuous improvement

## Communication Cadence

- **Daily**: 15-minute standups (focus on progress, blockers, dependencies)
- **Weekly**: Delivery sync (PM + PdM + team leads to review progress and risks)
- **Monthly**: Stakeholder updates (status, metrics, risks)
- **Ad-hoc**: Escalations as needed

## For More Information

- See `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` for the issue template to propose updates to these docs
- Keep project charters updated in project repos
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to reference them as context

---

**Last Updated**: 2026-05-25  
**Questions or feedback?** Open an issue using the [Add Content to Project Management Process Docs](https://github.com/Nikhil2722/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) template.