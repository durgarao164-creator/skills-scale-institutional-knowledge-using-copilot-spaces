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

## QA / Test Lead

### Role Summary
QA / Test Leads establish the quality strategy, verify acceptance criteria, and help ensure releases are ready for customers without avoidable defects or regressions.

### Responsibilities
- Define the testing strategy and critical quality gates for each milestone or release
- Review acceptance criteria and identify gaps in validation coverage
- Coordinate test planning, defect triage, and regression validation
- Track release readiness and communicate quality risks to Project Managers and Product Managers
- Partner with Developers to improve automated and manual test coverage

### Goals
- Reduce preventable defects and release risk
- Improve confidence in feature readiness and operational stability
- Align validation work with customer impact and business priorities

### Typical Communication
- Test plans, release readiness reviews, and defect triage discussions
- QA signoff checkpoints in sprint or release meetings
- Direct updates to Developers, Product Managers, and Project Managers on blockers or quality risks

### Interaction with Existing Roles
- Works with Developers to confirm expected behavior, testability, and defect ownership
- Partners with Product Managers on acceptance criteria, user impact, and release decisions
- Keeps Project Managers informed of quality risks, blockers, and readiness status during delivery planning and release windows

---

## UX / UI Designer or Researcher

### Role Summary
UX / UI Designers and Researchers translate customer needs into usable experiences and design decisions that support product outcomes and adoption.

### Responsibilities
- Gather user feedback, pain points, and behavioral insights
- Create workflows, wireframes, prototypes, and design specifications
- Validate usability, accessibility, and clarity with users and stakeholders
- Collaborate with Product Managers on problem framing and prioritized improvements
- Support Developers with implementation details and edge-case design decisions

### Goals
- Improve usability, accessibility, and customer satisfaction
- Make product experiences understandable and consistent
- Ensure design decisions are grounded in evidence and user needs

### Typical Communication
- User interviews, research summaries, design reviews, and prototype walkthroughs
- Feedback loops with Product Managers and Developers during planning and iteration
- Product and stakeholder presentations that explain user impact

### Interaction with Existing Roles
- Works closely with Product Managers to refine outcomes, target audiences, and experience priorities
- Partners with Developers to ensure design intent is feasible and implemented accurately
- Supports Project Managers by clarifying dependencies, design review timing, and milestone readiness for user-facing work

---

## Technical Lead / Architect

### Role Summary
Technical Leads or Architects guide the technical direction, protect system quality, and help the team make sound implementation decisions that support long-term maintainability.

### Responsibilities
- Define technical standards, design patterns, and architecture guardrails
- Review technical trade-offs, dependencies, and cross-team integration risks
- Help estimate complexity and identify delivery or scalability constraints
- Support design reviews, technical decision-making, and incident learning
- Guide Developers in implementation consistency, reliability, and maintainability

### Goals
- Keep the solution scalable, resilient, and aligned with platform strategy
- Reduce avoidable technical debt and integration complexity
- Improve decision quality across product and engineering teams

### Typical Communication
- Architecture discussions, design reviews, dependency planning, and technical risk reviews
- Regular check-ins with Developers and Project Managers during milestones and escalations
- Coordination with Product Managers on trade-offs between scope, time, and technical constraints

### Interaction with Existing Roles
- Advises Developers on technical direction, risk mitigation, and architectural decisions
- Works with Product Managers to clarify feasibility, sequencing, and trade-off impacts
- Helps Project Managers understand technical dependencies, milestone risk, and escalation paths that affect delivery

---

## Release Manager / DevOps / Site Reliability Engineer

### Role Summary
Release Managers, DevOps engineers, and SREs coordinate the operational readiness of features, infrastructure changes, and production rollouts to reduce disruption and improve recovery time.

### Responsibilities
- Prepare deployment plans, rollout steps, monitoring, and rollback readiness
- Manage environment readiness, configuration, automation, and observability
- Coordinate release windows, deployment verification, and production health checks
- Support incident triage, recovery, and post-release follow-up
- Partner with Developers and QA Leads on operational readiness and validation

### Goals
- Enable safe, repeatable, observable releases
- Reduce operational surprise and incident impact
- Improve the speed and confidence of deployments without sacrificing reliability

### Typical Communication
- Deployment checklists, release readiness reviews, and post-deploy follow-ups
- Incident communication and recovery updates during production issues
- Coordination with Project Managers and Product Managers on launch timing and communications

### Interaction with Existing Roles
- Works with Developers to confirm environment requirements, deployability, and rollback plans
- Supports QA / Test Leads in smoke testing, validation, and monitoring during release windows
- Provides Project Managers with operational risk assessment, deployment risks, and mitigation timing

---

## Security and Privacy Partner

### Role Summary
Security and Privacy Partners help teams evaluate risk, protect sensitive data, and make sure work complies with required controls and privacy considerations.

### Responsibilities
- Review features, data handling, and integrations for security and privacy risks
- Participate in threat modeling, controls review, and secure design discussions
- Define guardrails for sensitive information handling, access, and incident response
- Partner with Product Managers on risk acceptance and compliance decisions
- Support the team with remediation planning and follow-up validation

### Goals
- Reduce security and privacy risk before products reach customers
- Support safe delivery without introducing unnecessary delays or compliance issues
- Build trust through secure, privacy-aware product decisions

### Typical Communication
- Security reviews, privacy impact assessments, and risk escalation meetings
- Required approvals or signoff checkpoints before release to production
- Coordination with engineering and cross-functional leaders on control gaps or mitigation steps

### Interaction with Existing Roles
- Advises Developers and Technical Leads on secure design choices and implementation requirements
- Helps Product Managers assess risk trade-offs and prioritize controls needed for customer trust and compliance
- Keeps Project Managers aware of security or privacy concerns that affect release timing or stakeholder communications

---

## Customer or Support Representative

### Role Summary
Customer or Support Representatives contribute user-facing insight, operational reality, and adoption context to improve delivery quality and customer experience.

### Responsibilities
- Share customer feedback, support trends, and recurring pain points
- Validate whether proposed changes solve real user needs and reduce operational friction
- Help define support readiness, training needs, and rollout communication requirements
- Collaborate with Product Managers and Project Managers on release messaging and adoption readiness
- Identify gap areas where implementation may create support burden or customer confusion

### Goals
- Improve customer value and supportability
- Reduce confusion, churn, and avoidable service escalations
- Ensure product changes align with real-world usage and operational needs

### Typical Communication
- Customer calls, support summaries, feedback review sessions, and stakeholder updates
- Input to roadmap and release planning from frontline customer knowledge
- Coordination with Product and delivery teams on adoption and support readiness

### Interaction with Existing Roles
- Provides Product Managers with customer evidence that shapes prioritization and outcomes
- Helps Developers understand operational realities, edge cases, and user friction that may need to be addressed
- Supports Project Managers on communications, dependency planning, and release readiness for customer-facing work

---

## Business Sponsor / Executive Stakeholder

### Role Summary
Business Sponsors and Executive Stakeholders provide strategic direction, funding support, and decision authority for high-impact initiatives.

### Responsibilities
- Confirm business case, strategic alignment, and priority of work
- Resolve escalated trade-offs, budget considerations, and major dependency issues
- Support resource decisions, executive communication, and sponsorship at critical milestones
- Review project status at key decision points and approve go/no-go actions when needed
- Partner with Product Managers and Project Managers to keep work aligned with business outcomes

### Goals
- Maximize business value and strategic impact
- Keep initiatives aligned to organizational goals and customer needs
- Enable timely decisions and accountability for major project outcomes

### Typical Communication
- Steering committee updates, milestone reviews, and decision checkpoints
- High-level status summaries and issue escalation communication
- Executive briefings on risks, priorities, and required decisions

### Interaction with Existing Roles
- Works with Product Managers on prioritization, outcome measures, and strategic trade-offs
- Coordinates with Project Managers on timing, scope decisions, and escalation needs
- Sets the context for the broader team by clarifying business intent and acceptable risk levels

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- This expanded set helps teams clarify accountability, cross-functional handoffs, decision rights, and release readiness.


