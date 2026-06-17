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

## Engineering Lead

### Role Summary
Engineering Leads provide technical direction and mentorship for development teams. They make architecture decisions, ensure code quality, and coordinate cross-team technical dependencies to enable smooth delivery.

### Responsibilities
- Define technical direction and architecture for projects
- Conduct code reviews and maintain code quality standards
- Mentor developers and facilitate knowledge sharing
- Identify and mitigate technical risks
- Coordinate dependencies with other technical teams
- Advocate for technical debt paydown and infrastructure investments

### Goals
- Maintain high code quality and system reliability
- Reduce technical risk and rework
- Develop team capability and reduce knowledge silos
- Enable fast, confident deployments

### Interactions with Other Roles
- Works with **Product Managers** on feasibility assessment and trade-offs
- Collaborates with **Developers** on design reviews and technical decisions
- Partners with **SRE** on observability, reliability, and performance tuning
- Coordinates with **QA** on test strategy and quality gates
- Escalates architectural concerns to **Product Operations** or sponsors

### Typical Communication
- Technical design reviews and RFC processes
- Code review comments and architecture discussions
- One-on-ones with developers for mentorship
- Dependency coordination in weekly technical syncs

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers validate user needs, create prototypes, and ensure solutions are usable and accessible. They partner with Product Managers to translate research into acceptance criteria and design handoffs for developers.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and design systems
- Validate accessibility standards (WCAG compliance)
- Provide acceptance criteria based on user needs
- Create design documentation and handoffs for development

### Goals
- Ensure solutions address real user needs
- Maximize usability and accessibility of delivered features
- Reduce rework through early validation
- Build consistent, reusable design patterns

### Interactions with Other Roles
- Partners with **Product Managers** to define user outcomes and success metrics
- Works with **Developers** to ensure designs are implemented correctly
- Collaborates with **QA** on usability test scenarios
- Provides input to **Engineering Lead** on performance and technical feasibility

### Typical Communication
- Research findings and user interview summaries
- Design specs and component documentation
- Prototype reviews and feedback sessions
- Design hand-off meetings with developers

---

## Site Reliability Engineer (SRE) / On-call Engineer

### Role Summary
Site Reliability Engineers ensure production systems are reliable, performant, and observable. They own runbooks, coordinate incident response, and work with developers to build reliable systems.

### Responsibilities
- Design and maintain monitoring, alerting, and observability
- Create and update incident response runbooks
- Lead incident triage and blameless post-mortems
- Identify and resolve performance bottlenecks
- Ensure security patches and updates are applied
- Advise developers on reliability patterns and observability instrumentation

### Goals
- Maintain high system availability and performance
- Minimize incident impact and mean time to recovery
- Enable fast, safe deployments
- Build a culture of reliability and continuous improvement

### Interactions with Other Roles
- Works with **Developers** on observability requirements and reliability design
- Collaborates with **Release Manager** on deployment runbooks and rollback plans
- Partners with **Product Manager** and **Project Manager** during incident response
- Provides alerts and dashboards to **Data Analysts** for health metrics
- Coordinates with **Security Engineer** on security incident response

### Typical Communication
- On-call schedules and incident alerts
- Post-incident retrospectives and action items
- Runbook documentation and updates
- Observability and monitoring reviews

---

## Data Analyst / Product Analyst

### Role Summary
Data Analysts and Product Analysts instrument features, build dashboards, and analyze data to measure success and inform prioritization decisions.

### Responsibilities
- Define instrumentation requirements for features
- Build and maintain dashboards and reports
- Analyze experiment results and A/B test outcomes
- Track success metrics and KPIs
- Provide data-driven insights to inform prioritization
- Document data schemas and metric definitions

### Goals
- Enable data-driven decision making
- Measure impact of features and initiatives
- Identify improvement opportunities through data
- Ensure data quality and consistency

### Interactions with Other Roles
- Partners with **Product Managers** to define success metrics and KPIs
- Works with **Developers** to ensure correct telemetry is instrumented
- Collaborates with **SRE** on dashboards for system health and performance
- Provides insights to **Project Managers** for project health tracking
- Supports **Retrospectives** with quantitative learnings

### Typical Communication
- Metric definitions and data documentation
- Dashboards and analytics reports
- Experiment analysis and recommendations
- Weekly or sprint-based analytics syncs

---

## Release Manager / Deployment Owner

### Role Summary
Release Managers coordinate release activities, ensure quality gates are met, and own the deployment process to production. They work with technical teams to minimize deployment risk.

### Responsibilities
- Schedule and coordinate release windows
- Verify all acceptance criteria and quality gates are met
- Create and maintain release notes and deployment runbooks
- Coordinate with SRE on deployment and monitoring
- Plan and document rollback procedures
- Track post-deployment verification and sign-off

### Goals
- Deliver releases on schedule with predictability
- Minimize deployment risk and incidents
- Ensure transparency and traceability in releases
- Enable rapid response to deployment issues

### Interactions with Other Roles
- Works with **Project Manager** and **Product Manager** on release timeline and scope
- Coordinates with **Developers** on release preparation and testing
- Partners with **SRE** on deployment execution and post-deploy monitoring
- Works with **QA** to verify quality gates before release
- Communicates with **Product Operations** on release process improvements

### Typical Communication
- Release checklists and deployment plans
- Release notes and deployment runbooks
- Post-deployment status and verification reports
- Release retrospectives and lessons learned

---

## Product Operations / Delivery Lead

### Role Summary
Product Operations and Delivery Leads enable cross-team collaboration, maintain project cadence, and drive process improvements. They support Project Managers and Product Managers in keeping projects on track.

### Responsibilities
- Facilitate cross-team coordination and dependency management
- Maintain project dashboards and health indicators
- Ensure OKR alignment across teams
- Identify and drive process improvements
- Maintain CI/CD tooling and delivery infrastructure
- Facilitate retrospectives and capture learnings
- Coordinate escalations and unblock teams

### Goals
- Improve project predictability and delivery consistency
- Reduce friction in cross-team collaboration
- Enable faster iteration cycles
- Build institutional knowledge of processes and lessons learned

### Interactions with Other Roles
- Supports **Project Managers** in maintaining project cadence and escalations
- Works with **Product Managers** on roadmap alignment and OKR tracking
- Collaborates with **Developers** and **Engineering Lead** on velocity and capacity planning
- Partners with **SRE** on deployment and infrastructure tooling
- Provides **Data Analysts** with project health metrics

### Typical Communication
- Project dashboards and health reports
- Process improvement recommendations
- Escalation notifications and updates
- Retrospective facilitation and action tracking

---

## Security Engineer / Compliance Owner

### Role Summary
Security Engineers and Compliance Owners ensure features and systems meet security and regulatory requirements. They conduct threat modeling, review designs, and advise teams on security trade-offs.

### Responsibilities
- Conduct threat modeling and security reviews
- Assess security and compliance requirements
- Triage and prioritize vulnerability fixes
- Review code and architecture for security risks
- Maintain security runbooks and incident procedures
- Advise on secure development practices and tools

### Goals
- Prevent security breaches and data leaks
- Ensure compliance with regulations and policies
- Build security into development from the start
- Enable teams to move fast safely

### Interactions with Other Roles
- Works with **Developers** and **Engineering Lead** on secure design and code review
- Partners with **Product Managers** on security-related trade-offs and prioritization
- Collaborates with **SRE** on security incident response and patching
- Coordinates with **Release Manager** on security validation before deployment
- Advises **Project Manager** on security risks and mitigation plans

### Typical Communication
- Security review findings and recommendations
- Threat modeling sessions and documentation
- Vulnerability reports and remediation tracking
- Security incident response and post-mortems

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when defining acceptance criteria, responsibilities, and communication flows in project planning.
- When onboarding new team members, use these definitions to clarify roles and reduce dependency on any single person.
