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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## New Personas

Below are additional personas that commonly participate in OctoAcme projects. Each entry describes responsibilities and how the persona interacts with existing roles.

### QA Lead

Role Summary
The QA Lead designs and drives the test strategy for features and releases to ensure product quality and acceptance criteria are met.

Responsibilities
- Define test plans, test cases, and acceptance criteria alignment
- Coordinate manual and automated testing efforts
- Triage and prioritize defects with the team
- Advocate for testability and quality early in planning

Goals
- Reduce escaped defects in production
- Increase automation coverage for critical flows
- Ensure repeatable, measurable verification steps for releases

Typical Communication
- Attend sprint planning, feature reviews, and demos
- Report test status in weekly delivery syncs
- Collaborate in PR reviews for testability and acceptance

Interaction with existing roles
- Works closely with Developers to ensure test coverage and define acceptance criteria.
- Partners with the Project Manager to schedule testing windows and report quality risks.
- Aligns with the Product Manager on acceptance criteria and release readiness.

---

### DevOps / SRE

Role Summary
DevOps/SRE engineers own build, deployment, and operational reliability for services and infrastructure supporting OctoAcme projects.

Responsibilities
- Maintain CI/CD pipelines, infrastructure as code, and deployment automation
- Define and run release verification and rollback procedures
- Monitor production health and respond to incidents
- Improve system reliability and observability

Goals
- Ensure reliable, repeatable deployments
- Reduce mean time to recovery (MTTR)
- Maintain secure and compliant infrastructure

Typical Communication
- Coordinate with Developers on build failure resolution and deployment readiness
- Provide deployment windows and runbooks for Project Managers
- Share operational dashboards with stakeholders

Interaction with existing roles
- Partners with Developers to automate tests and ensure CI passes before merge.
- Works with the QA Lead to run production smoke tests and validate releases.
- Informs Project Manager and Product Manager of operational risks and mitigation plans.

---

### Design Lead (UX)

Role Summary
The Design Lead focuses on user research, interaction design, and ensuring product usability and accessibility.

Responsibilities
- Conduct user research and synthesize insights
- Produce wireframes, prototypes, and design specs
- Define usability acceptance criteria and accessibility checks
- Participate in design reviews and usability testing

Goals
- Improve user satisfaction and task success metrics
- Reduce rework caused by usability issues
- Ensure accessible and consistent design patterns

Typical Communication
- Present design concepts during kickoff and reviews
- Work with Product Managers to validate hypotheses
- Collaborate with Developers during implementation and QA

Interaction with existing roles
- Works with Product Manager to define user needs and acceptance criteria.
- Collaborates with Developers and QA Lead to ensure designs are implementable and verifiable.
- Shares research findings with the Project Manager and stakeholders to inform priorities.

---

### Engineering Manager

Role Summary
Engineering Managers provide technical leadership, people management, and help align engineering efforts with product goals.

Responsibilities
- Mentor and grow engineering team members
- Remove organizational and technical blockers
- Drive technical roadmap and ensure engineering quality standards
- Participate in hiring and performance conversations

Goals
- Improve team throughput and technical capability
- Maintain a healthy engineering culture and career growth
- Ensure delivery aligns with technical strategy

Typical Communication
- Regular 1:1s with team members and leads
- Technical trade-off discussions during planning
- Cross-team syncs for platform and dependency coordination

Interaction with existing roles
- Supports Developers in technical decisions and capacity planning.
- Works with Project Manager to align resourcing and timelines.
- Collaborates with Product Manager and Design Lead on long-term technical vision and trade-offs.

---

### Data Analyst

Role Summary
The Data Analyst helps define, measure, and interpret success metrics to inform product decisions and validate outcomes.

Responsibilities
- Define analytics events and instrumentation needs
- Create dashboards and reports for success metrics
- Perform ad‑hoc analysis to answer product questions
- Validate that releases meet success criteria

Goals
- Provide clear, actionable insights to stakeholders
- Reduce time to insight for product experiments
- Ensure measurement integrity for decisions

Typical Communication
- Share dashboards in weekly syncs and roadmap reviews
- Partner with Product Manager to define experiments and metrics
- Provide analysis for retrospectives and post-release reviews

Interaction with existing roles
- Works with Developers and DevOps to ensure accurate instrumentation.
- Partners with Product Manager to define success metrics and evaluate outcomes.
- Provides findings to Project Manager to inform risks and next steps.

---

## Notes on usage
- Keep persona definitions concise and aligned to project needs; add project-specific persona variants when necessary.
- Use these personas as inputs for scenario planning, role-based review checklists, and Copilot Spaces persona prompts.
