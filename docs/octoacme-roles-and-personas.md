# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Assign roles according to project size and context; one person may cover multiple roles, but ownership and decision boundaries should remain explicit.

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

## UX / Product Designers

### Role Summary
UX/Product Designers research user needs and shape accessible, usable experiences, translating product goals into designs that the team can implement and validate.

### Responsibilities
- Conduct or synthesize user research and identify usability needs
- Create user flows, prototypes, interaction and visual designs, and design guidance
- Validate designs through usability feedback and iterate on findings
- Document accessibility considerations and design decisions

### Collaboration and decision boundaries
- Partner with the Product Manager to connect user needs to product goals, scope, and acceptance criteria; the Product Manager remains accountable for prioritization and product outcomes.
- Work with Developers and the Tech Lead / Architect to assess feasibility and resolve design trade-offs.
- Coordinate with QA/Testing to make designs and accessibility expectations testable and to review usability findings.
- Share research and design decisions with the Project Manager for planning, dependencies, and stakeholder updates.

---

## Tech Leads / Architects

### Role Summary
Tech Leads / Architects guide technical direction and help the team make maintainable, secure, and scalable engineering decisions. The role may be shared or combined with a senior Developer on smaller teams.

### Responsibilities
- Facilitate technical design and document significant architecture decisions
- Identify technical risks, dependencies, and integration constraints
- Guide engineering standards, code review, and technical quality
- Advise on estimates and technical options without owning product priority

### Collaboration and decision boundaries
- Work with Developers on implementation choices, reviews, and technical problem solving; Developers remain responsible for delivering and maintaining their code.
- Coordinate with the Product Manager on technical trade-offs that affect scope, outcomes, or acceptance criteria.
- Keep the Project Manager informed of technical risks, dependencies, and estimates for the plan and risk register.
- Partner with DevOps / Release Engineers and QA/Testing on system quality, environments, and release readiness.

---

## DevOps / Release Engineers

### Role Summary
DevOps / Release Engineers enable reliable delivery and operation of software through deployment automation, environment management, and observability. This role may be provided by a platform or operations team.

### Responsibilities
- Maintain or advise on CI/CD pipelines, deployment practices, and delivery environments
- Support monitoring, alerting, and operational readiness
- Define and validate rollback or mitigation approaches with the delivery team
- Identify infrastructure and release risks and communicate constraints

### Collaboration and decision boundaries
- Partner with Developers and the Tech Lead / Architect to make build and deployment workflows reliable and supportable.
- Coordinate with QA/Testing on test environments and release verification.
- Work with the Project Manager on deployment timing, dependencies, and release risks; the Project Manager coordinates the plan while operational owners retain authority over their systems.
- Advise the Product Manager on release implications that may affect scope, availability, or customer impact.

---

## Customer Support / Operations Representatives

### Role Summary
Customer Support / Operations Representatives bring customer-facing and day-to-day operational needs into project decisions and prepare the people and processes that support a change after release.

### Responsibilities
- Surface recurring customer issues, support needs, and operational workflows
- Identify support, training, documentation, and service-readiness requirements
- Prepare support teams for changes and establish routes for feedback and issue escalation
- Report post-release feedback and operational signals to the project team

### Collaboration and decision boundaries
- Work with the Product Manager to connect customer feedback and support trends to priorities and success measures; the Product Manager owns product prioritization.
- Coordinate with the Project Manager on stakeholder communications, readiness tasks, and release handoffs.
- Collaborate with Developers, the Tech Lead / Architect, and DevOps / Release Engineers on operational requirements, known limitations, and escalation paths.
- Partner with QA/Testing to ensure important customer and operational scenarios are considered in validation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to project size and context; when a person covers multiple roles, make ownership and decision boundaries explicit.
