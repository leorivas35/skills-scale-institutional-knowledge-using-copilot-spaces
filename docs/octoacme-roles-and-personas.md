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

---

## Release Managers

### Role Summary
Release Managers plan and coordinate the safe delivery of changes to production. They own release readiness and the go/no-go process.

### Responsibilities
- Maintain the release calendar and release checklists
- Confirm acceptance criteria, testing, and approvals are complete before release
- Coordinate rollout, rollback plans, and release communications
- Lead release retrospectives and track release metrics

### Goals
- Ship predictable, low-risk releases
- Reduce failed or rolled-back deployments

### Decision Rights
- owns the go/no-go call for a release, informed by Developers and Security Reviewers.

### Interactions with Other Roles
- Works with Developers on build and deployment readiness
- Syncs with Project Managers on schedule and risks
- Informs Product Managers, Support / Operations Leads, and Technical Writers of release scope and timing

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Release notes and rollout status updates

---

## Technical Writers

### Role Summary
Technical Writers create and maintain clear, accurate documentation for users, operators, and contributors.

### Responsibilities
- Draft and review user guides, API docs, and process documentation
- Keep documentation in step with product changes
- Maintain style guides and documentation standards
- Flag unclear requirements discovered while documenting

### Goals
- Make documentation accurate, discoverable, and current
- Reduce support requests caused by missing or unclear docs

### Decision Rights
- owns documentation structure and style; approves docs as part of the definition of done.

### Interactions with Other Roles
- Interviews Developers and UX Designers to understand changes
- Receives scope from Product Managers and Release Managers
- Provides content to Support / Operations Leads

### Typical Communication
- Documentation reviews in pull requests
- Release notes and doc status updates

---

## UX Designers

### Role Summary
UX Designers shape how users experience the product through research, interaction design, and usability validation.

### Responsibilities
- Conduct user research and usability testing
- Produce wireframes, prototypes, and design specs
- Define and maintain design system guidelines
- Review implemented work for usability and accessibility

### Goals
- Deliver intuitive, accessible experiences
- Validate designs with real user feedback before build

### Decision Rights
- recommends interaction and visual design; trade-offs are agreed with Product Managers.

### Interactions with Other Roles
- Partners with Product Managers on problem definition and research
- Hands off designs to Developers and reviews implementation
- Shares UI changes with Technical Writers

### Typical Communication
- Design reviews and handoff sessions
- Design specs and prototype links in issues

---

## Security Reviewers

### Role Summary
Security Reviewers assess changes for security and compliance risk and guide teams toward secure-by-default practices.

### Responsibilities
- Perform threat modeling and security design reviews
- Review code, dependencies, and configuration for vulnerabilities
- Track and verify remediation of findings
- Advise on compliance and data-handling requirements

### Goals
- Prevent vulnerabilities from reaching production
- Make security a routine part of delivery

### Decision Rights
- can block a release for unresolved high-severity findings, escalating through the Project Manager.

### Interactions with Other Roles
- Advises Developers on fixes and secure design
- Provides security sign-off to Release Managers
- Raises risks with Project Managers and Business Sponsors

### Typical Communication
- Security review comments on pull requests and designs
- Findings reports and risk register entries

---

## Support / Operations Leads

### Role Summary
Support / Operations Leads represent the voice of the customer after release and keep services running reliably.

### Responsibilities
- Triage and escalate customer issues and incidents
- Maintain runbooks, on-call processes, and service-level targets
- Feed recurring issues and feedback back into the backlog
- Prepare support teams for upcoming releases

### Goals
- Resolve issues quickly and reduce repeat incidents
- Keep customer impact visible to the team

### Decision Rights
- owns incident severity and escalation; advocates for backlog priority of operational issues.

### Interactions with Other Roles
- Escalates defects to Developers
- Shares customer trends with Product Managers
- Coordinates readiness and incident communication with Release Managers and Project Managers

### Typical Communication
- Incident reports and post-incident reviews
- Support trend summaries in planning and retrospectives

---

## Data Analysts

### Role Summary
Data Analysts turn product and project data into insights that guide decisions and measure outcomes.

### Responsibilities
- Define and maintain metrics, dashboards, and reports
- Analyze usage, delivery, and quality trends
- Support experiment design and measure results
- Ensure data quality and consistent metric definitions

### Goals
- Enable data-driven prioritization and retrospectives
- Make outcomes measurable and transparent

### Decision Rights
- owns metric definitions and analysis methods; decisions based on the data remain with the relevant role.

### Interactions with Other Roles
- Supports Product Managers with success metrics and experiments
- Provides delivery metrics to Project Managers
- Works with Developers on instrumentation

### Typical Communication
- Regular metrics reviews and dashboards
- Ad hoc analysis requests in issues

---

## Business Sponsors

### Role Summary
Business Sponsors are senior stakeholders who fund and champion the work, and are accountable for the business outcome.

### Responsibilities
- Approve scope, budget, and strategic priorities
- Remove organizational blockers and resolve escalations
- Provide feedback at key milestones and sign off on outcomes
- Communicate business context and expectations

### Goals
- Ensure projects deliver measurable business value
- Keep work aligned with organizational strategy

### Decision Rights
- final authority on funding, scope changes, and priority conflicts that cannot be resolved by the team.

### Interactions with Other Roles
- Aligns with Product Managers on vision and outcomes
- Receives status and risk reports from Project Managers
- Hears escalations from Release Managers and Security Reviewers

### Typical Communication
- Milestone reviews and stakeholder briefings
- Executive summaries and escalation notes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

