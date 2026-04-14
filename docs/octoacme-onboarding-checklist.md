# OctoAcme — Role-Specific Onboarding Checklists

This document provides onboarding checklists for each persona defined in
[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md).
Use these checklists when a new team member joins a project to ensure they have the
context, access, and contacts needed to be productive quickly.

Checklists were added as part of [issue #4](https://github.com/NhoxxKienn/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to address gaps in
onboarding clarity for cross-functional personas.

---

## General Onboarding Checklist (All Roles)

Complete the following for every new team member regardless of role:

- [ ] Provide access to the project repository and documentation (`docs/` folder)
- [ ] Share the [Project Management Overview](octoacme-project-management-overview.md)
- [ ] Share the [Roles & Personas](octoacme-roles-and-personas.md) document
- [ ] Add to the team communication channel (Slack / Teams / etc.)
- [ ] Schedule an introductory meeting with the Project Manager
- [ ] Add to recurring ceremonies (standup, sprint planning, retrospectives)
- [ ] Set up required tool access (project board, CI/CD dashboard, design tools, etc.)
- [ ] Confirm emergency / on-call contact list has been updated (if applicable)

---

## Developer Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Clone the project repository and verify local build & tests pass
- [ ] Review branching strategy and PR conventions documented in the repo README
- [ ] Confirm CI/CD pipeline access and understand the deployment flow
- [ ] Read the [Execution & Tracking](octoacme-execution-and-tracking.md) guide
- [ ] Review the Definition of Done (DoD) and coding standards
- [ ] Meet with the Security Lead to review secure-coding guidelines
- [ ] Meet with the DevOps Engineer to understand infrastructure and deployment process
- [ ] Complete first PR (e.g., a small bug fix or documentation improvement) for review

---

## Product Manager (PdM) Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Review current product roadmap and backlog in the project board
- [ ] Read the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md) docs
- [ ] Meet with the Project Manager to align on current sprint goals and timeline
- [ ] Meet with the UX/UI Designer to review current design status and pending research
- [ ] Meet with the Data Analyst to review KPIs, dashboards, and measurement framework
- [ ] Meet with the Customer Success Manager to understand current customer feedback themes
- [ ] Confirm stakeholder list and communication schedule
- [ ] Review and understand the acceptance criteria format used by the team

---

## Project Manager (PM) Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Review the full `docs/` folder to understand all project management processes
- [ ] Review the current project plan, milestones, and risk register
- [ ] Meet with the Product Manager to understand roadmap priorities and open trade-offs
- [ ] Meet with the DevOps Engineer to understand the release schedule and deployment process
- [ ] Meet with the Security Lead to understand outstanding security risks or compliance requirements
- [ ] Read the [Risk Management & Communication](octoacme-risks-and-communication.md) guide
- [ ] Confirm stakeholder contact list and communication cadence
- [ ] Take over or schedule the next project status update

---

## UX/UI Designer Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Gain access to the design tool (Figma / Sketch / etc.) and team design library
- [ ] Review the existing design system, component library, and brand guidelines
- [ ] Review accessibility standards (WCAG) currently targeted by the project
- [ ] Meet with the Product Manager to understand user personas, current features, and roadmap
- [ ] Review any existing user research findings, usability test results, or analytics reports
- [ ] Meet with the lead Developer to understand technical constraints and component reuse patterns
- [ ] Meet with the Data Analyst to learn about current usability and engagement metrics
- [ ] Identify the first design task and schedule a design review with PdM and Developers

---

## DevOps Engineer Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Review the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [ ] Gain access to CI/CD tooling, cloud infrastructure consoles, and monitoring dashboards
- [ ] Review existing pipeline configurations, IaC files, and infrastructure documentation
- [ ] Review current on-call rotation and incident response runbook
- [ ] Meet with the Security Lead to understand required security controls in the pipeline
- [ ] Meet with the lead Developer to understand build dependencies and deployment requirements
- [ ] Meet with the Project Manager to understand upcoming release windows and communication process
- [ ] Validate all pipeline stages (build, test, staging deploy) are functioning correctly
- [ ] Confirm alerting and notification channels are configured correctly

---

## Customer Success Manager Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Review the product documentation, feature list, and recent release notes
- [ ] Gain access to customer communication platforms (CRM, support ticketing system, etc.)
- [ ] Review existing customer feedback themes, surveys, and recurring support issues
- [ ] Meet with the Product Manager to understand the current roadmap and upcoming features
- [ ] Meet with the Project Manager to understand the release schedule and communication timelines
- [ ] Meet with the Data Analyst to align on customer success metrics and dashboards
- [ ] Shadow at least one customer onboarding or check-in call to understand current processes
- [ ] Confirm the process for escalating critical customer issues to the development team

---

## Security Lead Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Review existing threat models, security policies, and previous security audit reports
- [ ] Gain access to security tooling (SAST/DAST scanners, dependency checkers, secret scanning)
- [ ] Review the CI/CD pipeline with the DevOps Engineer to assess current security controls
- [ ] Conduct an initial architecture review to identify security risk areas
- [ ] Meet with the Project Manager to understand upcoming milestones and security review gates
- [ ] Meet with the lead Developer to communicate secure-coding standards and review process
- [ ] Review compliance or regulatory requirements applicable to the project
- [ ] Schedule the first security review session with the team

---

## Data Analyst Onboarding Checklist

- [ ] Complete the [General Onboarding Checklist](#general-onboarding-checklist-all-roles)
- [ ] Gain access to analytics platforms, data warehouses, and existing dashboards
- [ ] Review the current KPI definitions and measurement framework with the Product Manager
- [ ] Review existing event-logging schemas and data pipeline documentation
- [ ] Meet with the lead Developer to understand the data collection approach and logging conventions
- [ ] Meet with the UX/UI Designer to understand usability metrics and planned user research
- [ ] Meet with the Customer Success Manager to understand qualitative signals and customer feedback themes
- [ ] Review available data sources and identify any gaps in instrumentation
- [ ] Deliver a first data summary or dashboard review within the first sprint

---

## Onboarding Timeline Guidance

| Day | Milestone |
|-----|-----------|
| Day 1 | Complete general checklist, meet PM, get tool access |
| Days 2–3 | Complete role-specific checklist, meet key collaborators |
| Week 1 | Shadow key ceremonies; identify first meaningful contribution |
| Week 2 | Complete first deliverable; seek early feedback |
| Week 4 | Fully integrated; contributing independently |
