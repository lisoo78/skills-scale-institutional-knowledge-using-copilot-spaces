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

## Additional Project Roles

These roles clarify common responsibilities and handoffs across OctoAcme projects. Not every project needs a separate person for each role; on smaller teams, one person may cover multiple roles. Regardless of staffing, make ownership and decision authority explicit.

### Project Sponsors

#### Role Summary
Project Sponsors provide strategic direction and support for the project. They help ensure the work remains aligned with organizational priorities and resolve escalations that are beyond the delivery team's authority.

#### Responsibilities
- Confirm strategic alignment and support key business decisions.
- Help secure or prioritize funding, capacity, and organizational support.
- Make or escalate decisions that affect scope, priority, or business outcomes.
- Review progress and major risks at agreed checkpoints.

#### How They Work with Existing Roles
- Partner with the Project Manager (PM) on escalations, constraints, and status updates.
- Align with the Product Manager on desired outcomes and priority trade-offs.
- Rely on Developers and technical leads for technical context when decisions have engineering implications.

### Engineering Leads / Technical Leads

#### Role Summary
Engineering Leads guide technical design and engineering readiness while supporting Developers in delivering maintainable solutions.

#### Responsibilities
- Guide technical approach, architecture, and engineering standards.
- Support implementation planning, estimation, and technical decision-making.
- Identify technical risks, dependencies, and operational concerns.
- Help ensure work is ready for integration, testing, and release.

#### How They Work with Existing Roles
- Collaborate with Developers on design, implementation, reviews, and technical problem-solving.
- Work with the Product Manager to clarify feasibility and explain technical trade-offs.
- Coordinate with the PM on dependencies, estimates, risks, and delivery forecasts.
- Partner with QA and the release owner on testability and operational readiness.

### Designers / UX Researchers

#### Role Summary
Designers and UX Researchers bring user needs and usability evidence into product decisions and delivery.

#### Responsibilities
- Conduct or synthesize user research and communicate relevant findings.
- Create and validate user flows, interaction designs, and prototypes.
- Identify usability and accessibility considerations.
- Support evaluation of delivered experiences against user needs.

#### How They Work with Existing Roles
- Partner with the Product Manager on discovery, problem definition, and acceptance criteria.
- Work with Developers and Engineering Leads to assess feasibility and clarify design intent.
- Coordinate with QA on usability and accessibility validation.
- Share research and design decisions with the PM so they can be reflected in plans and stakeholder updates.

### QA / Test Engineers

#### Role Summary
QA / Test Engineers help the team prevent defects and verify that the product meets acceptance criteria and quality expectations.

#### Responsibilities
- Develop test strategies and identify appropriate levels of testing.
- Create and maintain test cases, automation, and quality checks as appropriate.
- Verify acceptance criteria and report defects with clear reproduction details.
- Communicate quality risks and readiness findings before release.

#### How They Work with Existing Roles
- Collaborate with Developers throughout implementation to improve testability and diagnose defects.
- Work with the Product Manager to clarify acceptance criteria and expected behavior.
- Coordinate with the PM on quality status, blockers, and readiness reporting.
- Partner with the release owner on smoke tests and post-deployment verification.

### DevOps / Site Reliability / Release Owners

#### Role Summary
This role coordinates operational readiness and safe, observable deployment of project changes. Depending on the team, these responsibilities may be shared among engineering, operations, and release personnel.

#### Responsibilities
- Identify deployment, infrastructure, reliability, and monitoring requirements.
- Coordinate release readiness, deployment steps, and rollback or mitigation plans.
- Ensure appropriate operational safeguards and observability are in place.
- Support post-deployment verification and incident response when needed.

#### How They Work with Existing Roles
- Coordinate with Developers and Engineering Leads on deployment needs and operational risks.
- Work with QA on smoke tests and release verification.
- Align with the PM on release timing, dependencies, and status communication.
- Consult the Product Manager on customer impact and release scope.

### Business / Operations Stakeholders and Subject-Matter Experts

#### Role Summary
These stakeholders contribute domain knowledge, operational constraints, and validation of whether proposed changes fit real business processes.

#### Responsibilities
- Explain business rules, user workflows, and operational constraints.
- Identify dependencies, compliance considerations, or process impacts in their area.
- Review relevant requirements and decisions.
- Validate that delivered changes support intended workflows.

#### How They Work with Existing Roles
- Partner with the Product Manager to clarify needs, outcomes, and priorities.
- Coordinate with the PM on reviews, decisions, dependencies, and timelines.
- Provide Developers and QA with domain context needed to implement and validate the work.
- Raise operational risks or readiness concerns through the PM and appropriate project leads.

### Support / Customer Success Representatives

#### Role Summary
Support and Customer Success Representatives bring customer feedback into project work and help prepare teams to support changes after release.

#### Responsibilities
- Share recurring customer questions, feedback, and support trends.
- Identify documentation, training, and service-readiness needs.
- Help prepare customer-facing communications and support guidance.
- Report post-release issues and customer impact to the project team.

#### How They Work with Existing Roles
- Work with the Product Manager to connect customer feedback to product priorities.
- Coordinate with the PM on launch communications, readiness, and follow-up.
- Partner with the release owner on timing and known-issue information.
- Share customer-reported issues with Developers and QA through the agreed intake process.

## Role Assignment and Accountability

Projects may combine these roles or use different role titles. At project initiation or planning, document who owns each relevant responsibility, who can make or approve key decisions, and how handoffs will occur. Combining roles should not leave responsibilities or decision authority ambiguous.
