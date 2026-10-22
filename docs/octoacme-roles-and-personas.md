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

## Security / Compliance Lead

### Role Summary
Security and Compliance Leads protect the organization from technical, operational, and regulatory risk throughout the lifecycle of a project. They partner with product, engineering, and project leadership to ensure that requirements, implementation choices, and release decisions meet policy and trust expectations.

### Responsibilities
- Review security risks, compliance obligations, and regulatory requirements
- Define security controls, review gates, and acceptable-risk thresholds
- Support threat modeling and risk assessments for new features and integrations
- Validate that deployments and data handling meet standards for privacy, security, and compliance
- Help coordinate escalation for incidents, vulnerabilities, and policy exceptions

### Goals
- Reduce exposure to security and compliance risks
- Increase confidence in product decisions and release readiness
- Balance speed of delivery with safety, governance, and user trust

### Typical Communication
- Design reviews and architecture discussions
- Risk register updates and escalation notices
- Security sign-off checkpoints before major releases or high-risk changes

### Interaction with existing roles
- Works closely with Developers to review implementation choices and technical controls.
- Partners with Project Managers to surface risk, dependencies, and mitigation timing.
- Provides input to Product Managers and Stakeholders on trade-offs between delivery speed, regulatory obligations, and business goals.

---

## UX Researcher

### Role Summary
UX Researchers help the team understand user needs, behaviors, and pain points. They turn findings into actionable insights that support product decisions, reduce rework, and improve usability.

### Responsibilities
- Plan and conduct user research, interviews, and usability studies
- Synthesize insights into opportunities, pain points, and recommendations
- Validate assumptions with evidence before building or changing features
- Help define user-oriented acceptance criteria and success measures
- Communicate findings clearly to Product Managers, Designers, and Developers

### Goals
- Increase product usability and customer satisfaction
- Ensure decisions are grounded in user evidence, not just internal preference
- Reduce risk of building the wrong feature or experience

### Typical Communication
- Research plans and summaries
- Feedback loops during discovery and validation
- Collaboration in backlog refinement and acceptance criteria discussions

### Interaction with existing roles
- Works with Product Managers to shape priorities and outcomes based on user impact.
- Partners with Developers on clarifying edge cases, user flows, and feature validation.
- Supports Project Managers by highlighting dependencies between research, design, and delivery milestones.

---

## Data / Analytics Lead

### Role Summary
Data and Analytics Leads define key measurements, instrumentation, and reporting needed to evaluate whether the project is creating value. They translate product outcomes into measurable signals for teams and stakeholders.

### Responsibilities
- Define success metrics, KPIs, and instrumentation requirements
- Ensure data quality, event tracking, and reporting consistency
- Analyze trends, adoption, behavior, and performance against project goals
- Support product and business decision-making with evidence
- Communicate risks, anomalies, and opportunities to leadership and delivery teams

### Goals
- Make performance and impact visible and measurable
- Improve decision-making with reliable, actionable data
- Reduce ambiguity in project success and product learning

### Typical Communication
- Metrics dashboards and regular reporting updates
- Review meetings on outcomes, adoption, and trends
- Briefings to PM, Product Managers, and Sponsors on business impact

### Interaction with existing roles
- Collaborates with Product Managers to define metrics that align to product goals.
- Partners with Developers and Platform/DevOps Engineers to ensure instrumentation and observability are in place.
- Helps Project Managers identify whether delivery is on track based on measurable outcomes, not only completion status.

---

## Platform / DevOps Engineer

### Role Summary
Platform and DevOps Engineers ensure the project can be deployed, monitored, scaled, and recovered reliably. They reduce operational friction and improve team velocity by maintaining the systems needed for stable delivery.

### Responsibilities
- Manage environments, CI/CD pipelines, and infrastructure configuration
- Improve deployment automation, observability, and operational resilience
- Support incident response, rollback planning, and service recovery
- Help developers ship changes with safe, repeatable workflows
- Monitor production health and reliability signals for key services

### Goals
- Improve release confidence and service reliability
- Reduce manual work and operational bottlenecks
- Enable faster, safer, and more consistent delivery

### Typical Communication
- Release readiness reviews and deployment checklists
- Incident and postmortem follow-ups
- Platform health and capacity discussions with engineering and PM stakeholders

### Interaction with existing roles
- Works with Developers to ensure environments, pipelines, and deployment standards are operationally sound.
- Coordinates with Project Managers and Release Manager/Support Liaison on deployment windows, rollbacks, and release risk.
- Supports Product and Stakeholder communication by providing reliable delivery signals and operational status.

---

## Customer Success / Business Sponsor

### Role Summary
Customer Success and Business Sponsor roles connect project delivery to business outcomes, adoption, and customer value. They help keep the roadmap aligned with stakeholder expectations and real-world customer needs.

### Responsibilities
- Represent business goals, customer feedback, and adoption priorities
- Validate whether planned changes meet business and customer expectations
- Support stakeholder alignment and decision-making across the project lifecycle
- Help identify commercial risks, dependencies, and opportunities for improvement
- Communicate progress, impact, and trade-offs to leadership and cross-functional teams

### Goals
- Ensure the project contributes to real customer and business value
- Keep stakeholders informed and aligned on outcomes, risks, and priorities
- Reduce gaps between internal execution and external expectations

### Typical Communication
- Business meetings, stakeholder briefings, and roadmap updates
- Feedback loops on quality, adoption, and customer experience
- Escalation of risks that impact outcomes, commitments, or satisfaction

### Interaction with existing roles
- Works with Product Managers and Project Managers to align priorities, timing, and stakeholder expectations.
- Provides feedback to Developers and UX Researcher about customer usage and business impact.
- Helps ensure that project decisions remain grounded in customer value and overall business strategy.

---

## Release Manager / Support Liaison

### Role Summary
Release Managers or Support Liaisons coordinate the communication and readiness around launches, updates, and post-release support. This role is especially important when projects involve multiple teams, dependencies, or customer-facing changes.

### Responsibilities
- Coordinate release planning, go-live readiness, and communication timing
- Align deployment activities with support, operations, and stakeholder expectations
- Ensure launch documentation, rollback guidance, and support handoff are complete
- Track post-release issues and support needs after deployment
- Help escalate critical problems and coordinate remediation priorities

### Goals
- Reduce release-related disruption and confusion
- Improve customer communication and support readiness
- Increase confidence in rollout safety and operational continuity

### Typical Communication
- Deployment checklists and release notes
- Stakeholder alerts and post-deployment status updates
- Support coordination for issues, defects, and customer escalations

### Interaction with existing roles
- Works with Project Managers and Platform/DevOps Engineers on timing, rollout strategy, and safety checks.
- Supports Developers and Product Managers by helping validate whether a release is ready and how it should be communicated.
- Helps Stakeholders and Customer Success teams understand what changed, what risks remain, and how to support users after launch.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- These expanded roles support clearer ownership, stronger cross-functional collaboration, and more complete project governance across product, engineering, operations, and business outcomes.

