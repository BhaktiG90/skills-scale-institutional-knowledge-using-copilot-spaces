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

## Quality Assurance / Test Engineer

### Role Summary
Quality Assurance and Test Engineers protect the quality of releases by defining test strategies, executing validation, and providing evidence that work meets agreed criteria.

### Responsibilities
- Define test plans and establish quality gates
- Execute testing and coordinate defect triage
- Maintain regression and release-readiness evidence
- Identify quality risks and communicate go/no-go concerns

### Goals
- Prevent defects from reaching users
- Improve confidence in release readiness
- Strengthen traceability between requirements and validation

### Typical Communication
- Test plans and defect reports
- Quality readiness updates in delivery meetings
- Acceptance review with Product and Project Managers

### Interactions with Existing Roles
- Collaborates with **Developers** to reproduce defects and verify fixes.
- Works with **Product Managers** to clarify acceptance criteria and prioritize quality risks.
- Coordinates with **Project Managers** on test milestones, blockers, and release readiness.

---

## Release / Deployment Manager

### Role Summary
Release and Deployment Managers coordinate controlled delivery of approved changes into the appropriate environments.

### Responsibilities
- Plan release windows and deployment sequences
- Coordinate approvals, rollout, and rollback readiness
- Track deployment dependencies and release evidence
- Facilitate go/no-go decisions

### Goals
- Deliver releases safely and predictably
- Minimize deployment-related disruption
- Maintain clear recovery and rollback plans

### Typical Communication
- Release plans and deployment checklists
- Go/no-go reviews and rollout status updates
- Post-deployment verification summaries

### Interactions with Existing Roles
- Coordinates with **Developers** on build, configuration, and technical readiness.
- Aligns with **Product Managers** on release scope and customer impact.
- Works with **Project Managers** on schedules, approvals, and stakeholder communications.
- Partners with Quality Assurance and Operations/SRE roles on verification and production readiness.

---

## Operations / Site Reliability Engineer

### Role Summary
Operations and Site Reliability Engineers ensure that delivered services are observable, resilient, supportable, and operationally ready.

### Responsibilities
- Establish monitoring, alerting, and operational runbooks
- Manage incident response and reliability reviews
- Assess capacity and operational risks
- Coordinate corrective actions and post-incident improvements

### Goals
- Maintain reliable, scalable, and observable services
- Reduce incident frequency and recovery time
- Improve operational readiness before release

### Typical Communication
- Operational readiness reviews
- Incident reports and reliability updates
- Capacity and monitoring recommendations

### Interactions with Existing Roles
- Works with **Developers** on instrumentation, failure modes, and corrective fixes.
- Partners with **Product Managers** to balance reliability priorities with product value.
- Supports **Project Managers** by identifying operational milestones, risks, and dependencies.
- Coordinates with Release and Quality Assurance roles during deployment and validation.

---

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads identify security and regulatory requirements, assess risks, and ensure appropriate controls and evidence are maintained.

### Responsibilities
- Define security and compliance requirements
- Conduct threat reviews and control assessments
- Coordinate remediation and risk acceptance
- Maintain audit evidence and policy requirements

### Goals
- Reduce security and compliance risk
- Integrate controls into delivery work
- Provide clear and timely risk decisions

### Typical Communication
- Threat and compliance assessments
- Remediation plans and exception records
- Security readiness reviews

### Interactions with Existing Roles
- Advises **Developers** on secure implementation and required remediation.
- Works with **Product Managers** on scope, trade-offs, and risk acceptance.
- Keeps **Project Managers** informed of security gates, dependencies, and deadlines.
- Coordinates with Quality Assurance and Release roles on validation and release controls.

---

## UX / Research Lead

### Role Summary
UX and Research Leads represent customer needs and validate that proposed experiences are understandable, usable, and aligned with measured outcomes.

### Responsibilities
- Plan and conduct user research
- Create experience requirements and usability guidance
- Test concepts and prototypes with users
- Interpret findings and communicate customer evidence

### Goals
- Improve usability and customer satisfaction
- Reduce uncertainty about customer needs
- Ensure product decisions reflect validated user evidence

### Typical Communication
- Research plans and findings
- UX specifications and usability reviews
- Customer insight summaries

### Interactions with Existing Roles
- Partners with **Product Managers** to define problems, priorities, and success measures.
- Works with **Developers** on feasibility and implementation of experience requirements.
- Supports **Project Managers** by identifying research and validation milestones.
- Helps Quality Assurance define usability expectations and validation activities.

---

## Customer Success / Support Lead

### Role Summary
Customer Success and Support Leads represent customer experience, readiness, and feedback across planning and delivery.

### Responsibilities
- Collect and prioritize recurring customer feedback
- Prepare support teams for releases and known issues
- Coordinate customer communications and adoption support
- Escalate product issues and customer impact

### Goals
- Improve customer adoption and satisfaction
- Reduce support disruption during releases
- Ensure customer feedback influences product decisions

### Typical Communication
- Customer feedback summaries
- Support readiness and known-issue updates
- Adoption and post-release reports

### Interactions with Existing Roles
- Shares customer priorities and feedback with **Product Managers**.
- Works with **Developers** and Quality Assurance on reproducible defects and support fixes.
- Coordinates rollout communications and customer impact updates with **Project Managers**.
- Partners with Release and Operations roles on customer-facing readiness and incident communication.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads define how project outcomes are measured, ensure data quality, and translate evidence into actionable insights.

### Responsibilities
- Define measurement and reporting plans
- Validate instrumentation and data quality
- Produce outcome and adoption reports
- Interpret findings and communicate recommendations

### Goals
- Improve the accuracy of delivery and outcome measurements
- Enable data-driven decisions
- Establish consistent reporting for stakeholders

### Typical Communication
- Measurement plans and dashboards
- Data quality findings
- Outcome and experiment reports

### Interactions with Existing Roles
- Works with **Product Managers** to define success metrics and interpret outcomes.
- Partners with **Developers** on instrumentation and event design.
- Supports **Project Managers** with reporting milestones and evidence for status updates.
- Coordinates with UX/Research and Customer Success roles to combine qualitative and quantitative evidence.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
