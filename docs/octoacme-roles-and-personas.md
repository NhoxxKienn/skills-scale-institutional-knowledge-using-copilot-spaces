# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
It was expanded as part of [issue #4](https://github.com/NhoxxKienn/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to include additional cross-functional personas
that reflect modern project team structures and to clarify hand-offs between roles.

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

### Interactions & Hand-offs
- **← Product Managers**: receive acceptance criteria and feature specs; flag technical feasibility concerns early.
- **← UX/UI Designer**: receive wireframes and final UI assets; implement designs and raise feasibility issues.
- **← Security Lead**: act on security review feedback; consult on secure coding practices.
- **→ DevOps Engineer**: hand off build/deployment requirements; coordinate on CI/CD pipeline changes.
- **↔ QA/Testing**: share code for testing; address defects and review test plans.

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

### Interactions & Hand-offs
- **← Customer Success Manager**: receive customer feedback and pain points to inform roadmap decisions.
- **← Data Analyst**: receive usage analysis and KPI reports to guide prioritization.
- **→ Developers**: provide prioritized backlog items with clear acceptance criteria.
- **→ UX/UI Designer**: brief on user needs and feature requirements; review design proposals.
- **↔ Project Manager**: align on capacity, timeline, and scope trade-offs.

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

### Interactions & Hand-offs
- **← Security Lead**: receive risk alerts; escalate security blockers appropriately.
- **← DevOps Engineer**: receive deployment status and incident notifications; coordinate release windows.
- **→ All roles**: distribute status updates, decisions, and action items.
- **↔ Product Manager**: negotiate scope, timeline, and priority changes.
- **↔ Stakeholders**: manage expectations; surface issues and request decisions.

---

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for designing user interfaces and delivering high-quality user experiences. They translate product requirements into intuitive, accessible designs and validate them with real users before implementation begins.

### Responsibilities
- Develop wireframes, mockups, prototypes, and final UI assets
- Conduct user research and usability testing; integrate findings into designs
- Uphold accessibility (WCAG) and usability standards
- Maintain and evolve the design system and component library
- Document design decisions and interaction specifications

### Goals
- Deliver experiences that are intuitive, accessible, and visually consistent
- Reduce rework by resolving design questions before implementation begins
- Bridge the gap between user needs and technical feasibility

### Typical Communication
- Design reviews with Product Manager and Developers before each sprint
- Usability testing reports shared with PM and PdM
- Annotated design files and interaction specs for Developers

### Interactions & Hand-offs
- **← Product Manager**: receive feature briefs and user-need summaries; review designs against requirements.
- **→ Developers**: deliver annotated UI assets and interaction specs; answer implementation questions.
- **→ QA/Testing**: provide acceptance criteria for visual and interaction quality.
- **↔ Data Analyst**: collaborate on defining usability metrics and interpreting user-behaviour data.

---

## DevOps Engineer

### Role Summary
DevOps Engineers enable reliable, automated software delivery by maintaining the CI/CD pipeline, managing infrastructure, and ensuring system observability. They act as the bridge between development and production operations.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and release automation
- Manage infrastructure as code (IaC) and cloud resources
- Monitor production systems; own incident detection and initial triage
- Define and enforce deployment standards and rollback procedures
- Collaborate on deployment planning and capacity management

### Goals
- Maximize release frequency while minimizing deployment risk
- Ensure high system availability and fast incident recovery
- Reduce manual toil through automation

### Typical Communication
- Release coordination meetings with PM before each deployment window
- Incident notifications (alerts, status-page updates) to all stakeholders
- Infrastructure and pipeline documentation in the project repo

### Interactions & Hand-offs
- **← Developers**: receive build and deployment requirements; integrate automated tests into pipelines.
- **← Security Lead**: implement security controls (scanning, secret management) in pipelines.
- **→ Project Manager**: provide deployment status and incident updates; flag release blockers.
- **→ All stakeholders**: issue incident communications and post-mortem summaries.
- **↔ QA/Testing**: coordinate staging environments and test-data management.

---

## Customer Success Manager

### Role Summary
Customer Success Managers act as the voice of the customer post-launch. They onboard customers to new features, gather ongoing feedback, and translate real-world usage into actionable insights for the product team.

### Responsibilities
- Onboard customers to new features and help them realise value quickly
- Collect, document, and categorise customer feedback and pain points
- Identify recurring issues and escalate to the appropriate team
- Provide customer success metrics and insights to PdM for roadmap input
- Coordinate customer communications around releases and outages

### Goals
- Increase product adoption and reduce customer churn
- Ensure customer voices are represented in the product roadmap
- Minimise time-to-value for new features

### Typical Communication
- Regular customer check-in calls and feedback surveys
- Bi-weekly insight summaries shared with PdM and PM
- Escalation tickets logged for recurring technical issues

### Interactions & Hand-offs
- **→ Product Manager**: provide synthesised customer feedback and feature requests to inform the roadmap.
- **→ Developers**: log recurring bug reports or usability issues for triage.
- **← Project Manager**: receive advance notice of upcoming releases to prepare customer communications.
- **↔ Data Analyst**: share qualitative customer signals to complement quantitative usage data.

---

## Security Lead

### Role Summary
The Security Lead ensures that security considerations are integrated throughout the entire project lifecycle — from design to deployment and operations. They serve as the primary point of contact for security risk, compliance, and incident response.

### Responsibilities
- Review architecture designs and code for security vulnerabilities
- Conduct and oversee threat modelling and risk assessments
- Define and enforce secure development standards and guidelines
- Coordinate security-related incident response
- Provide ongoing security training and awareness for the team

### Goals
- Reduce security risk exposure across the project lifecycle
- Embed a "security-by-default" culture within the team
- Ensure compliance with applicable regulatory and organisational standards

### Typical Communication
- Security review sign-off before major releases
- Risk advisories and remediation guidance for Developers and PM
- Post-incident security retrospectives

### Interactions & Hand-offs
- **→ Developers**: provide security review feedback; advise on secure coding practices and remediation.
- **→ DevOps Engineer**: specify security pipeline controls (SAST, DAST, secret scanning, image scanning).
- **→ Project Manager**: raise critical security risks that may affect timeline or scope.
- **← All roles**: receive notifications of potential security issues or incidents for triage.

---

## Data Analyst

### Role Summary
Data Analysts define, track, and interpret usage, product, and business metrics. They validate project outcomes against success criteria and communicate data-driven insights to guide future iterations.

### Responsibilities
- Collaborate with PdM to define KPIs and measurement frameworks
- Instrument features for tracking (work with Developers on event logging)
- Build and maintain dashboards and reports
- Analyse data and surface actionable insights for the team
- Validate that delivered features meet their stated success metrics

### Goals
- Ensure product decisions are grounded in evidence, not assumptions
- Reduce time from data collection to actionable insight
- Provide a single source of truth for product and project metrics

### Typical Communication
- Sprint-end data summaries shared with PM and PdM
- Dashboard links and alert thresholds documented in the project repo
- Ad-hoc analysis requests responded to within an agreed SLA

### Interactions & Hand-offs
- **← Product Manager**: receive KPI definitions and measurement priorities.
- **← Developers**: coordinate on event-logging schemas and data pipeline requirements.
- **→ Product Manager**: deliver usage analysis, KPI reports, and roadmap recommendations.
- **→ Project Manager**: provide metrics that inform milestone reviews and retrospectives.
- **↔ Customer Success Manager**: share quantitative usage data to complement qualitative customer feedback.
- **↔ UX/UI Designer**: collaborate on defining and interpreting usability and engagement metrics.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [octoacme-onboarding-checklist.md](octoacme-onboarding-checklist.md) for role-specific onboarding checklists.

