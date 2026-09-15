# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

### Interactions with Other Roles
- **Product Managers**: Collaborate on acceptance criteria and feature specifications
- **Project Managers**: Provide estimates and progress updates
- **QA/Testing Leads**: Work together on testability and Definition of Done
- **Technical Architects**: Consult on design decisions and technical standards
- **Security Officers**: Implement security requirements and participate in code reviews
- **Support/Operations Leads**: Coordinate on observability and deployment concerns

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

### Interactions with Other Roles
- **Developers**: Define features and validate acceptance criteria
- **Project Managers**: Align on priorities and timelines
- **QA/Testing Leads**: Collaborate on quality standards and test planning
- **Sponsors/Stakeholders**: Present outcomes and business metrics
- **Technical Architects**: Discuss feasibility and technical trade-offs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

### Interactions with Other Roles
- **All roles**: Serve as central coordinator and communication hub
- **Scrum Masters/Agile Coaches**: Partner on process facilitation and impediment resolution
- **Sponsors/Stakeholders**: Provide executive updates and manage escalations
- **Product Managers**: Align on delivery timelines and prioritization

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads ensure product quality through comprehensive testing strategies, acceptance validation, and quality metrics. They work closely with developers and product managers to define and enforce quality standards.

### Responsibilities
- Define and maintain test strategy and approach for the project
- Create and execute test plans aligned with acceptance criteria
- Perform manual QA for feature acceptance and edge cases
- Collaborate on Definition of Done and quality gates
- Track quality metrics and identify quality trends
- Escalate quality risks and blockers

### Goals
- Catch defects early and prevent production incidents
- Ensure features meet acceptance criteria and usability standards
- Provide confidence in release readiness

### Typical Communication
- Sprint planning and acceptance criteria review
- Quality reports and metrics dashboards
- Pre-release verification and smoke test execution

### Interactions with Other Roles
- **Developers**: Collaborate on testability, test cases, and acceptance criteria
- **Product Managers**: Define quality standards and acceptance criteria
- **Project Managers**: Report on quality metrics and release readiness
- **Support/Operations Leads**: Coordinate on production smoke tests and validation
- **Scrum Masters/Agile Coaches**: Incorporate quality practices into team ceremonies

---

## Technical Architect / Technical Lead

### Role Summary
Technical Architects and Leads guide architectural decisions, technical strategy, and long-term system health. They ensure solutions are scalable, maintainable, and aligned with organizational technical standards.

### Responsibilities
- Conduct technical design reviews and architecture assessments
- Identify and mitigate technical risks and debt
- Mentor developers on best practices and design patterns
- Collaborate on technology selection and integration strategies
- Ensure compliance with technical standards and security guidelines

### Goals
- Deliver technically sound solutions that scale
- Reduce technical debt and maintenance burden
- Build team technical capabilities

### Typical Communication
- Technical design discussions and code reviews
- Architecture review boards and technical advisories
- Escalations on technical feasibility or risk

### Interactions with Other Roles
- **Developers**: Provide guidance on design patterns and technical decisions
- **Product Managers**: Discuss feasibility and trade-offs
- **Project Managers**: Escalate technical risks and dependencies
- **Security Officers**: Collaborate on security architecture and compliance
- **Support/Operations Leads**: Design for operability and observability

---

## Security Officer

### Role Summary
Security Officers integrate security practices, compliance requirements, and risk management into the project lifecycle. They partner with teams to ensure security by design.

### Responsibilities
- Define security requirements and acceptance criteria
- Review designs and code for security vulnerabilities
- Conduct or coordinate security assessments and scanning
- Guide incident response and breach escalation
- Ensure compliance with regulatory and organizational standards

### Goals
- Prevent security incidents and data breaches
- Meet compliance requirements
- Build security awareness across teams

### Typical Communication
- Security requirements review during planning
- Security scanning results and code review feedback
- Incident response coordination

### Interactions with Other Roles
- **Product Managers**: Define security requirements during planning
- **Developers**: Review code and provide security guidance
- **Technical Architects**: Collaborate on security architecture
- **QA/Testing Leads**: Include security test cases and scanning in QA
- **Project Managers**: Escalate security blockers and compliance risks
- **Sponsors/Stakeholders**: Report on compliance status and security posture

---

## Support/Operations Lead

### Role Summary
Support and Operations Leads ensure solutions are operationally sound, observable, and maintainable in production. They bridge development and operational concerns.

### Responsibilities
- Define observability and monitoring requirements
- Ensure runbooks and operational documentation are created
- Validate deployability and rollback procedures
- Coordinate on-call and incident response practices
- Provide feedback on operational pain points

### Goals
- Ensure smooth production operations and quick incident resolution
- Reduce Mean Time to Recovery (MTTR)
- Improve system observability and reliability

### Typical Communication
- Operational requirements definition during planning
- Deployment verification and go/no-go decisions
- Post-incident retrospectives and runbook updates

### Interactions with Other Roles
- **Developers**: Collaborate on observability, logging, and deployability
- **Technical Architects**: Design for operational resilience and runability
- **QA/Testing Leads**: Participate in smoke tests and deployment validation
- **Project Managers**: Provide go/no-go feedback before production release
- **Scrum Masters/Agile Coaches**: Incorporate operational readiness into Definition of Done

---

## Sponsor / Business Stakeholder

### Role Summary
Sponsors represent the business, fund the project, and make strategic approval decisions. They own the business outcome and validate alignment with organizational goals.

### Responsibilities
- Approve project charter and business case
- Make go/no-go decisions at key gates
- Prioritize competing resource requests
- Review progress against success metrics
- Escalate organizational or business blockers

### Goals
- Achieve target business outcomes and ROI
- Ensure strategic alignment
- Remove high-level organizational blockers

### Typical Communication
- Project approval and gate reviews
- Monthly stakeholder updates and business outcome tracking
- Escalation for resource conflicts or strategic decisions

### Interactions with Other Roles
- **Product Managers**: Validate business alignment and outcomes
- **Project Managers**: Receive executive updates and approve gate decisions
- **All delivery team members**: Engage through milestone reviews and decision gates

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches enable team effectiveness by facilitating processes, removing impediments, and coaching teams on continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies and planning activities
- Identify and help resolve team blockers and impediments
- Coach teams on agile practices and retrospectives
- Track and address process improvements
- Guard against scope creep and maintain focus

### Goals
- Maximize team velocity and predictability
- Foster a culture of continuous improvement
- Reduce process friction and wait times

### Typical Communication
- Daily standups and ceremony facilitation
- Retrospective facilitation and action item tracking
- One-on-ones and team coaching sessions

### Interactions with Other Roles
- **Project Managers**: Partner on process facilitation and issue resolution
- **All team members**: Coach on agile practices and continuous improvement
- **Developers, Product Managers, QA Leads**: Facilitate ceremonies and remove blockers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When planning a project, ensure representation from multiple personas based on project complexity and scope.
- Use the interactions sections to understand cross-functional dependencies and communication needs.
