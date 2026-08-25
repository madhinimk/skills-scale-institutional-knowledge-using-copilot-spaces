# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management guide. This documentation provides standardized processes and practices for running projects across our organization.

## Quick Overview

OctoAcme follows a structured project lifecycle with five key phases:

1. **Initiation** - Validate business need, align stakeholders, define success criteria
2. **Planning** - Break work into shippable increments, identify dependencies and risks
3. **Execution** - Build, test, review, and iterate with clear tracking and communication
4. **Release** - Deploy to production with quality assurance and rollback readiness
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Management Processes Overview

OctoAcme operates a structured, five-phase project lifecycle designed to deliver customer value through iterative, data-informed processes. The lifecycle begins with **Initiation**, where business needs are validated and stakeholders are aligned around a lightweight Project One-pager defining success metrics and timelines. This moves into **Planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are identified, and a prioritized backlog is established. The **Execution** phase emphasizes daily standups, PR-based workflows with automated CI/CD, and continuous tracking against project milestones. Teams follow a **Release** process that includes pre-release verification, smoke testing, and rollback planning to minimize production risk. Finally, **Close & Retrospective** captures learnings and converts them into actionable improvements, embodying OctoAcme's commitment to psychological safety and continuous iteration.

Clear ownership and role definition are central to OctoAcme's effectiveness. **Project Managers** coordinate schedules, manage risks and dependencies, and ensure transparent stakeholder communication. **Product Managers** define outcomes, prioritize the backlog, and measure success against data. **Developers** implement features, maintain test coverage, and collaborate on design decisions. **QA/Testing** validates acceptance criteria and quality standards. This multi-disciplinary structure is reinforced by a consistent communication cadence: daily standups and twice-weekly team syncs for delivery coordination, weekly PM-PdM alignment meetings, and monthly stakeholder updates. Risk escalation follows a clear path from team-level triage to PM, Product Lead, and sponsor involvement, ensuring blockers surface quickly without overwhelming the organization.

Quality and execution discipline run throughout OctoAcme's processes. Pull requests are kept small (≤400 lines when possible) with linked issues and clear acceptance criteria, requiring at least one approval before merge. Automated testing—including unit, integration, and end-to-end smoke tests—runs in CI alongside security scanning before any code reaches production. The project board (GitHub Projects) maintains visibility across Backlog, Ready, In Progress, In Review, QA, and Done columns. Risk management is proactive: risks are formally tracked with ID, description, impact, probability, owner, and mitigation strategy, with status reviewed weekly. This combination of lightweight governance, clear workflows, strong automation, and continuous feedback ensures OctoAcme delivers reliably while maintaining team morale and learning.

## Process Documentation

### Project Lifecycle
- [Project Management Overview](./octoacme-project-management-overview.md) - High-level lifecycle, roles, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate work and authorize projects
- [Project Planning](./octoacme-project-planning.md) - Creating actionable plans and prioritized backlogs
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution and progress tracking
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized release processes
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings

### Cross-cutting Processes
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Managing risks, dependencies, and stakeholder communication
- [Roles & Personas](./octoacme-roles-and-personas.md) - Definitions of key project roles and responsibilities

## Quick Start by Role

**Project Managers** - Start with [Project Management Overview](./octoacme-project-management-overview.md), then [Project Initiation Guide](./octoacme-project-initiation.md)

**Product Managers** - Review [Project Planning](./octoacme-project-planning.md) and [Execution & Tracking](./octoacme-execution-and-tracking.md)

**Developers** - Check [Execution & Tracking](./octoacme-execution-and-tracking.md) for workflows and quality standards

**Stakeholders** - See [Risk Management & Communication](./octoacme-risks-and-communication.md) for status and escalation

## How to Use These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Use the [Issue Template for Process Doc Updates](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) when proposing changes or additions
