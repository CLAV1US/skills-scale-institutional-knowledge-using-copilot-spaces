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

### Interactions with Other Personas
- Collaborate with Product Managers on feasibility and acceptance criteria.
- Coordinate with Project Managers on estimates, dependencies, and delivery risks.
- Work with QA/Testing, Security Leads, and UX personas to validate quality and usability.

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

### Interactions with Other Personas
- Align with Project Managers on scope, delivery constraints, and stakeholder decisions.
- Partner with UX, Data, Support/Operations, and Security personas to shape evidence-based requirements.

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

### Interactions with Other Personas
- Coordinate Product Managers on priorities and outcomes.
- Coordinate Developers and QA/Testing on delivery readiness and constraints.
- Connect Release, Security, Compliance, Support/Operations, and Delivery Facilitation roles to the project plan and escalation paths.

---

## Release Manager

### Role Summary
Release Managers own release readiness and coordinate safe, observable deployments to production.

### Responsibilities
- Define and coordinate deployment windows and release plans
- Confirm acceptance criteria, passing checks, rollback readiness, and operational approvals
- Lead go/no-go decisions and record release exceptions
- Coordinate stakeholder and support announcements
- Facilitate release verification and post-deployment follow-up

### Goals
- Deliver predictable releases with minimal operational risk
- Ensure rollback and mitigation plans are actionable
- Improve release communication and observability

### Typical Communication
- Release readiness reviews and go/no-go meetings
- Deployment plans and status updates
- Rollback notices and post-release summaries

### Interactions with Other Personas
- Works with Project Managers on scheduling, risks, dependencies, and escalation.
- Works with Developers and QA/Testing on merge readiness and verification.
- Coordinates with Security Leads and Support/Operations Liaisons on controls and operational readiness.
- Provides release outcomes and risks to stakeholders.

---

## Security Lead

### Role Summary
Security Leads establish security expectations, review high-risk changes, and guide secure delivery and incident response.

### Responsibilities
- Define required security controls and review high-risk or sensitive changes
- Guide threat modeling, remediation, and residual-risk decisions
- Coordinate security testing and incident procedures
- Track security dependencies and escalations

### Goals
- Reduce security risk without blocking necessary delivery
- Ensure controls and incident processes are understood and applied
- Communicate residual risk clearly to decision-makers

### Typical Communication
- Security reviews and remediation planning
- Threat-model and incident updates
- Risk acceptance or escalation records

### Interactions with Other Personas
- Advises Developers on secure implementation and remediation.
- Partners with QA/Testing on security validation and evidence.
- Works with Product and Project Managers to prioritize findings and communicate residual risk.
- Coordinates with Compliance/Operations roles and stakeholders on required controls and approvals.

---

## Support/Operations Liaison

### Role Summary
Support/Operations Liaisons represent production operations and customer-support needs throughout delivery and after release.

### Responsibilities
- Translate operational and support requirements into project readiness criteria
- Prepare runbooks, support documentation, monitoring, and escalation contacts
- Surface recurring customer issues and production feedback
- Participate in operational acceptance and post-release verification

### Goals
- Reduce preventable incidents and support escalation volume
- Improve operational readiness and troubleshooting speed
- Connect customer experience feedback to product decisions

### Typical Communication
- Operational readiness reviews
- Support readiness and incident handoff updates
- Production feedback summaries

### Interactions with Other Personas
- Shares customer and operational impact with Product Managers and stakeholders.
- Works with Developers on observability, diagnostics, and troubleshooting.
- Collaborates with QA/Testing on operational acceptance.
- Coordinates with Release Managers on launch readiness and with Project Managers on risks and support dependencies.

---

## UX Designer/Researcher

### Role Summary
UX Designers/Researchers turn customer needs into usable experiences and validate design assumptions through research and evidence.

### Responsibilities
- Conduct or synthesize user research
- Define interaction, accessibility, and usability requirements
- Create prototypes or design specifications
- Participate in usability validation and acceptance reviews

### Goals
- Improve usability, accessibility, and customer value
- Base product decisions on evidence rather than assumptions
- Resolve design trade-offs early in delivery

### Typical Communication
- Research findings and design critiques
- Prototype reviews and usability sessions
- Updated user flows and acceptance guidance

### Interactions with Other Personas
- Partners with Product Managers on problem framing and prioritization.
- Works with Developers on feasibility and implementation details.
- Collaborates with QA/Testing on usability and acceptance criteria.
- Presents findings to stakeholders and incorporates feedback into the backlog.

---

## Data Analyst

### Role Summary
Data Analysts define, measure, and interpret project outcomes to support evidence-based decisions.

### Responsibilities
- Define success metrics and reporting approaches
- Analyze delivery and customer outcome data
- Identify trends, limitations, and measurement risks
- Recommend follow-up actions based on evidence

### Goals
- Improve the accuracy and usefulness of success metrics
- Turn project data into clear decisions and improvements
- Reduce reliance on anecdotal evidence

### Typical Communication
- Metric definitions and dashboards
- Analysis summaries and experiment results
- Stakeholder reporting and recommendation reviews

### Interactions with Other Personas
- Aligns success metrics with Product Managers and stakeholders.
- Works with Project Managers on progress and outcome reporting.
- Coordinates with Developers on instrumentation and data quality.
- Shares findings with QA/Testing and Support/Operations when issues or trends affect quality or adoption.

---

## Scrum Master / Delivery Facilitator

### Role Summary
Scrum Masters and Delivery Facilitators improve team flow by facilitating ceremonies and removing delivery impediments.

### Responsibilities
- Facilitate planning, standups, reviews, and retrospectives
- Identify and remove team-level blockers
- Improve workflow, capacity, and delivery predictability
- Encourage follow-through on retrospective actions

### Goals
- Reduce cycle time and avoidable interruptions
- Strengthen team collaboration and psychological safety
- Improve predictable, sustainable delivery

### Typical Communication
- Team ceremonies and impediment reviews
- Flow and capacity summaries
- Retrospective action tracking

### Interactions with Other Personas
- Works with Project Managers on delivery risks and cross-team impediments.
- Helps Developers and QA/Testing improve flow, capacity, and readiness.
- Supports Product Managers by clarifying backlog readiness and team constraints.
- Escalates persistent cross-team risks to stakeholders or project leadership as appropriate.

---

## Risk/Compliance Owner

### Role Summary
Risk/Compliance Owners ensure that regulatory, contractual, and organizational obligations are identified and addressed throughout delivery.

### Responsibilities
- Maintain obligation, risk, and control evidence
- Identify compliance dependencies and required approvals
- Coordinate remediation and residual-risk decisions
- Monitor status and escalate missed or overdue requirements

### Goals
- Prevent compliance gaps and avoidable audit findings
- Make control responsibilities and evidence explicit
- Support timely, informed risk decisions

### Typical Communication
- Compliance and risk reviews
- Control evidence and action tracking
- Approval and escalation records

### Interactions with Other Personas
- Works with Project Managers to maintain the risk register and delivery plan.
- Coordinates with Security Leads on control implementation.
- Collaborates with QA/Testing and Developers on validation and evidence.
- Raises unresolved obligations to stakeholders and obtains required approvals.

---

## Small-Team Role Assignment

One person may cover multiple personas or responsibilities, especially in a small team. Combined roles should use the responsibility, decision, and escalation boundaries above to make ownership explicit and avoid relying on implicit assumptions. Teams should document role assignments in the project charter and raise conflicts or capacity constraints to the Project Manager.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
