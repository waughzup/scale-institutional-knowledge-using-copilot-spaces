# OctoAcme Project Management Documentation

## Overview

Welcome to OctoAcme's Project Management Process Documentation. This collection of guides provides a structured approach to planning, executing, and closing projects effectively. Our processes emphasize customer value, iterative delivery, clear ownership, data-driven decisions, and psychological safety.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Approach

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five core phases: **Initiation** (validating business need and aligning stakeholders), **Planning** (breaking work into shippable increments with defined acceptance criteria), **Execution** (day-to-day delivery with daily standups and continuous quality checks), **Release** (standardized deployment to production), and **Retrospective** (capturing learnings and driving continuous improvement). This phased approach is grounded in principles of psychological safety, data-informed decision-making, and transparent communication, ensuring that all projects maintain visibility and alignment from conception through post-release evaluation.

**Key roles and responsibilities** are clearly defined across three primary personas. **Project Managers** coordinate delivery activities, manage timelines, risks, and dependencies, and serve as the communication hub between teams and stakeholders. **Product Managers** own the product vision, prioritize the backlog, and measure outcomes through defined success metrics. **Developers** implement features, collaborate on design and testability, and help identify technical risks. This clear ownership structure reduces ambiguity and ensures accountability, with cross-functional alignment facilitated through a weekly sync between PM and Product Manager and twice-weekly team standups.

**Quality assurance and execution rigor** are embedded throughout the delivery process. The team maintains a prioritized backlog with defined acceptance criteria, uses a Definition of Done checklist, and enforces small pull requests (≤400 lines) with automated CI testing, linting, and security scanning before review. A three-level blocker escalation framework (team-level triage → PM escalation → sponsor-level escalation) ensures that risks and dependencies are surfaced quickly. Pre-release requirements include passing CI/security scans, prepared rollback plans, and smoke tests, while post-release verification and incident playbooks guard against production issues.

**Risk management and communication** are proactive and systematic. OctoAcme maintains a Risk Register throughout the project lifecycle, tracking ID, description, impact, likelihood, owner, and mitigation plans. Weekly stakeholder communication uses a standard template covering progress, next steps, risks, and decisions needed. Dependencies are marked on the project board and escalated during weekly syncs, and a blameless retrospective culture—held after each sprint, release, or incident—converts lessons learned into documented action items with clear owners and due dates.

## Quick Navigation

### Starting a New Project?
1. Begin with [Project Initiation Guide](octoacme-project-initiation.md)
2. Then move to [Project Planning](octoacme-project-planning.md)

### Managing Execution?
- See [Execution & Tracking](octoacme-execution-and-tracking.md)
- Check [Risk Management & Communication](octoacme-risks-and-communication.md)

### Preparing for Release?
- Reference [Release & Deployment Guide](octoacme-release-and-deployment.md)

### Capturing Learnings?
- Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

### Understanding Roles?
- See [Roles & Personas](octoacme-roles-and-personas.md)

## Complete Documentation Index

| Document | Purpose |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation](octoacme-project-initiation.md) | Initial steps to validate and authorize work, align stakeholders |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution management and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized approach to releasing features to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities in OctoAcme projects |

## Project Lifecycle

1. **Initiation** – Problem statement, stakeholders, high-level timeline
2. **Planning** – Scope, resources, milestones, dependencies
3. **Execution** – Build, test, review, iterate
4. **Release** – Deploy, verify, announce
5. **Close & Retrospective** – Capture learnings and next steps

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Using These Docs

- Keep the Project Charter updated in your project repo
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context
- Refer to these guides at each phase of your project to ensure alignment with OctoAcme standards
