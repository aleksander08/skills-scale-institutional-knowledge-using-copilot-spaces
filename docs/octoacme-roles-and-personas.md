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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and execution for projects. They design test plans, coordinate testing activities, and validate that features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define testing strategy and test plan for each project
- Coordinate manual and automated testing across features
- Validate acceptance criteria and sign-off on quality
- Identify and report defects with clear reproduction steps
- Collaborate on test automation and CI/CD integration
- Participate in retrospectives to improve testing processes

### Goals
- Ensure high-quality releases with minimal production defects
- Reduce cycle time from "in review" to "done"
- Build confidence in release readiness through clear test coverage metrics

### Interaction with Other Roles
- **Developers**: Provide feedback on PR quality, assist in debugging issues, validate fixes
- **Product Managers**: Clarify acceptance criteria, discuss test coverage priorities
- **Project Managers**: Report quality blockers and risks, participate in release planning
- **Technical Leads**: Advise on test automation architecture and testing tools

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction and strategic guidance for projects. They make or review major technical decisions, manage technical debt, and ensure solutions are scalable, maintainable, and aligned with platform standards.

### Responsibilities
- Review technical designs and architecture decisions
- Advise on technology choices and trade-offs
- Identify and prioritize technical debt and platform risks
- Mentor developers and conduct technical code reviews
- Ensure solutions meet performance, security, and scalability standards
- Participate in incident triage for complex technical issues

### Goals
- Deliver technically sound, maintainable solutions
- Build a shared technical vision and platform standards
- Reduce long-term maintenance burden through proactive debt management

### Interaction with Other Roles
- **Developers**: Provide technical guidance, review designs, mentor on best practices
- **Product Managers**: Advise on feasibility and technical trade-offs
- **Project Managers**: Flag technical risks and dependencies early
- **QA/Testing Leads**: Define test automation strategy and performance requirements

---

## Stakeholder/Sponsor

### Role Summary
Sponsors are executive or business stakeholders who champion projects, approve scope and budget, and provide strategic direction. They ensure alignment with organizational goals and serve as the final escalation point for project decisions.

### Responsibilities
- Approve project charter and funding
- Provide strategic direction and business priorities
- Resolve cross-functional dependencies and conflicts
- Receive and act on escalations from the PM
- Communicate project progress to leadership and customers
- Make go/no-go decisions at key gates (initiation, planning, release)

### Goals
- Maximize business value and ROI of projects
- Ensure alignment with organizational strategy
- Reduce escalation resolution time

### Interaction with Other Roles
- **Project Managers**: Receive regular status updates and escalations
- **Product Managers**: Review roadmap and business metrics
- **Developers/Leads**: Engaged for technical feasibility assessments at key gates

---

## Release Manager

### Role Summary
Release Managers coordinate and execute releases. They manage release planning, oversee deployment processes, and ensure post-release verification and rollback readiness.

### Responsibilities
- Plan release schedule and communication timeline
- Coordinate with teams on deployment readiness
- Execute or oversee deployment to staging and production
- Run post-deployment verification and smoke tests
- Manage rollback procedures if issues arise
- Communicate release status to stakeholders and support teams

### Goals
- Deliver releases with minimal risk and downtime
- Maintain clear communication throughout the release cycle
- Enable fast, confident deployments

### Interaction with Other Roles
- **Project Managers**: Coordinate release timing and stakeholder communication
- **Developers**: Validate deployment readiness and resolve deployment issues
- **QA/Testing Leads**: Ensure smoke tests pass before production release
- **Product Managers**: Communicate feature rollout and release notes

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They gather and document requirements, clarify acceptance criteria, and validate that delivered solutions achieve business outcomes.

### Responsibilities
- Conduct user research and gather business requirements
- Document acceptance criteria in clear, testable language
- Validate that features solve the stated business problem
- Support product managers in requirements refinement
- Assist in creating user stories and defining Definition of Done
- Participate in UAT (User Acceptance Testing) coordination

### Goals
- Ensure built solutions address real business needs
- Reduce rework due to misunderstood requirements
- Increase stakeholder satisfaction with delivered features

### Interaction with Other Roles
- **Product Managers**: Collaborate on requirement clarification and user research
- **Developers**: Clarify acceptance criteria and edge cases
- **QA/Testing Leads**: Ensure test cases cover all acceptance criteria
- **Stakeholders**: Validate business outcomes and gather feedback

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
