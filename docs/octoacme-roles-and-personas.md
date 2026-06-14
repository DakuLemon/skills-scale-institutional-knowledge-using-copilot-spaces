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

### Interactions
- Works closely with Tech Lead on implementation approach and code quality standards
- Collaborates with UX/Product Designer to ensure feature usability
- Partners with QA/Testing to define acceptance conditions
- Engages with Security Engineer during code review for security considerations

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

### Interactions
- Works with UX/Product Designer to define user outcomes and acceptance criteria
- Collaborates with Data Analyst on success metrics definition and measurement
- Partners with Engineering Lead and Tech Leads on technical feasibility and trade-offs
- Escalates risks and blockers to Project Manager and stakeholders

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

### Interactions
- Works with Engineering Lead on technical risks and dependencies
- Coordinates with Release Engineer on deployment schedules and readiness
- Partners with Support Lead on production readiness and customer impact communication
- Escalates business-impacting issues to sponsor and stakeholders

---

## Engineering Lead

### Role Summary
Senior technical owner responsible for overall architecture, technical trade-offs, and delivery quality. Drives system-level decisions and mentors technical leads.

### Responsibilities
- Drive system-level design decisions and ensure alignment with architecture goals
- Coordinate cross-team technical dependencies and integration points
- Mentor Tech Leads and support engineering estimates and prioritization
- Own quality standards and technical debt management strategy
- Participate in planning to translate product goals into technical scope

### Goals
- Deliver scalable, maintainable architecture
- Enable consistent technical excellence across the team
- Reduce technical debt and improve system health

### Typical Communication
- Technical design reviews and architecture discussions
- Weekly syncs with Product Manager and Project Manager
- Code review escalations and technical mentoring
- Risk escalation to Product Lead and Project Manager

### Interactions
- Works with PM/PdM to translate product goals into technical scope and trade-offs
- Collaborates with QA on non-functional requirements and test strategies
- Partners with Release Engineer on deployment readiness and infrastructure needs
- Escalates technical blockers and security concerns through proper escalation channels

---

## Tech Lead

### Role Summary
Day-to-day technical lead for a specific squad or component. Owns implementation approach, code quality, and sprint-level technical execution.

### Responsibilities
- Own implementation approach, code quality, and sprint-level technical tasks
- Review designs and PRs; ensure adherence to coding standards and best practices
- Identify technical debt and propose mitigation strategies
- Unblock developers and coordinate with other teams on integration points
- Estimate work and provide technical input to sprint planning

### Goals
- Deliver high-quality code on schedule
- Foster a culture of code excellence and continuous improvement
- Reduce technical debt incrementally

### Typical Communication
- Daily standups and code reviews
- Sprint planning and backlog refinement
- Technical design discussions with developers
- Escalation to Engineering Lead on architectural or cross-team issues

### Interactions
- Partners with Developers to unblock implementation and ensure quality
- Works with QA/Testing to define acceptance conditions and test strategies
- Collaborates with UX/Product Designer on implementation feasibility
- Reports progress and technical risks to the Engineering Lead and PM

---

## UX / Product Designer

### Role Summary
Responsible for user research, interaction design, and ensuring usability of features. Bridges customer needs with technical implementation.

### Responsibilities
- Conduct user research and usability testing to validate design decisions
- Deliver wireframes, prototypes, and acceptance criteria for user-facing work
- Incorporate user feedback and iterate on designs
- Ensure accessibility and consistency across product experiences
- Collaborate with developers to ensure designs are implementable and testable

### Goals
- Maximize user satisfaction and usability
- Reduce rework through early validation and clear specifications
- Ensure consistent, accessible user experiences

### Typical Communication
- Design reviews and feedback sessions
- Collaboration with developers on implementation details
- User research findings and insights
- Acceptance criteria specification in backlog items

### Interactions
- Works closely with PdM to define user outcomes and acceptance criteria
- Collaborates with Developers to ensure designs are implementable and testable
- Partners with Data Analyst on user behavior metrics and validation
- Engages with Tech Lead on technical constraints and feasibility

---

## Security Engineer / Security SME

### Role Summary
Ensures security considerations are integrated into design and delivery. Advises on threat mitigation and validates security controls.

### Responsibilities
- Perform threat modeling and security architecture reviews during planning
- Review code and designs for security vulnerabilities and compliance risks
- Define required security scans, controls, and validation steps
- Advise on secure coding practices and security tooling
- Triage and advise on remediations for security findings

### Goals
- Minimize security vulnerabilities in production
- Embed security into the development lifecycle
- Maintain compliance with security standards and regulations

### Typical Communication
- Security reviews during planning and code review phases
- Threat modeling sessions and architecture discussions
- Security incident communication and triage
- Guidance on required controls and mitigations

### Interactions
- Engages with Engineering Lead and Tech Lead during planning for security architecture
- Reviews code with Developers and provides security guidance
- Communicates required controls to PM and Engineering Lead
- Escalates security blockers through incident/escalation paths as needed
- Coordinates with Release Engineer on security readiness before deployment

---

## Data Analyst / Data Engineer

### Role Summary
Supports measurement, instrumentation, and analysis to validate success metrics. Enables data-driven decision-making.

### Responsibilities
- Define required events, metrics, and data collection strategy
- Create dashboards and analytics to track success metrics
- Validate data integrity and support experimentation
- Provide analysis and insights for retrospectives and release reviews
- Collaborate with developers on instrumentation implementation

### Goals
- Enable data-driven validation of product decisions
- Provide actionable insights to inform prioritization
- Maintain high-quality data for decision-making

### Typical Communication
- Metrics definition and dashboard reviews
- Analysis and insights in retrospectives and reviews
- Collaboration with developers on instrumentation
- Data quality and measurement strategy discussions

### Interactions
- Works with PdM on success metrics definition and measurement strategy
- Collaborates with Developers to implement instrumentation and event tracking
- Partners with Tech Lead on data architecture and performance considerations
- Provides analysis for retrospectives and release reviews

---

## Release Engineer / SRE (Release-focused)

### Role Summary
Oversees deployment pipelines, release automation, and rollback procedures. Ensures safe, reliable deployments and operational readiness.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Run release rehearsals and coordinate release windows
- Own post-deploy verifications and smoke tests
- Coordinate communication with stakeholders and support teams during releases
- Document and maintain runbooks for deployment and rollback procedures
- Collaborate with engineering on infrastructure and deployment concerns

### Goals
- Enable fast, safe deployments with minimal risk
- Reduce mean time to recovery (MTTR) for incidents
- Increase deployment reliability and automation

### Typical Communication
- Release planning and coordination
- Deployment status updates and incident communication
- Runbook and procedure documentation
- Infrastructure and tooling collaboration

### Interactions
- Works with PM and Engineering Lead to schedule releases and plan deployment windows
- Coordinates with Support/On-call teams for readiness and incident response
- Partners with Tech Lead on deployment requirements and infrastructure needs
- Collaborates with Security Engineer on security readiness before deployment

---

## Support Lead / Customer Success Liaison

### Role Summary
Primary interface for support-related feedback and operational issues. Advocates for customer impact and production reliability.

### Responsibilities
- Triage production issues and collect reproducible error reports
- Coordinate with engineering on prioritization and fixes for customer-impacting issues
- Track customer impact and communicate status updates
- Feed customer insights and learnings back into product prioritization
- Participate in incident postmortems and capture action items
- Communicate release and feature changes to support teams

### Goals
- Minimize customer impact from production issues
- Ensure fast resolution of critical issues
- Improve product reliability based on real-world usage patterns

### Typical Communication
- Production issue triage and escalation
- Customer impact and incident communication
- Postmortem participation and follow-up actions
- Release notes and feature communication to support teams

### Interactions
- Communicates customer-impacting issues to PM/PdM and Engineering for prioritization
- Works with Engineering Lead and Tech Lead on root cause analysis and fixes
- Participates in incident postmortems and retrospectives
- Partners with Project Manager on escalation and stakeholder communication
- Engages with Release Engineer on release readiness and support team communication

---

## When to Involve Each Persona

- **Engineering Lead**: During planning for all projects; for architecture decisions; when cross-team dependencies exist
- **Tech Lead**: Sprint planning, estimation, code review, and day-to-day execution
- **UX/Product Designer**: Early in planning for user-facing features; during design reviews and acceptance criteria definition
- **Security Engineer**: Planning phase for features handling PII or sensitive data; code review for critical components; pre-release security readiness
- **Data Analyst**: When defining success metrics; before and after feature release for validation
- **Release Engineer**: Planning phase for deployment requirements; pre-release coordination and post-deploy verification
- **Support Lead**: Planning for customer-impacting features; incident response; retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interactions to understand cross-functional collaboration and escalation paths in OctoAcme projects.
