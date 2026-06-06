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

## UX Designer

### Role Summary
UX Designers conduct user research, create wireframes and prototypes, and validate usability to ensure features deliver excellent user experiences. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research and validate assumptions through interviews and testing
- Create wireframes, prototypes, and design specs
- Collaborate with Product Managers to translate user needs into actionable requirements
- Work with Developers to ensure design feasibility and handoff clarity
- Participate in design reviews and incorporate feedback
- Validate designs through usability testing and iterate based on findings

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce design-to-development friction
- Align team decisions with user data and feedback
- Minimize design rework and post-launch usability issues

### Typical Communication
- Design specifications and component libraries shared with Developers
- User research findings and insights shared with Product Managers
- Design QA feedback from QA team
- Design critique sessions and feedback loops with cross-functional team

### Interactions
- **Product Managers**: Collaborate on requirements, user stories, and success metrics
- **Developers**: Provide design handoff, answer implementation questions, incorporate feedback
- **QA**: Design QA validation and usability testing coordination

---

## Data Analyst

### Role Summary
Data Analysts define and maintain success metrics, validate data quality, and surface actionable insights to inform product and business decisions. They work across teams to ensure data-driven decision-making.

### Responsibilities
- Define and track success metrics aligned with project goals
- Perform data validation and quality checks
- Design experiments and A/B tests to validate hypotheses
- Create dashboards and reports for stakeholders and leadership
- Provide insights and recommendations based on data analysis
- Collaborate on instrumentation requirements for new features

### Goals
- Enable data-driven decision-making across the organization
- Provide clear, actionable insights from complex data sets
- Measure impact and return on investment for features and initiatives
- Identify trends and opportunities for improvement

### Typical Communication
- Weekly metrics reports and dashboards shared with stakeholders
- Data insights and recommendations to Product Managers and Project Managers
- Instrumentation requirements and data needs discussed with Developers
- Ad-hoc analysis and deep dives as needed

### Interactions
- **Product Managers**: Align on success metrics and validate product impact
- **Project Managers**: Provide reporting and progress tracking metrics
- **Developers**: Define instrumentation and data collection requirements

---

## Technical Writer

### Role Summary
Technical Writers create and maintain clear, accurate documentation for features, including user guides, release notes, and process docs. They ensure documentation quality and supports user adoption and team knowledge sharing.

### Responsibilities
- Draft and maintain feature documentation and user guides
- Create and update release notes with clear, user-friendly language
- Develop and refine internal process documentation and onboarding guides
- Coordinate with Developers and Product Managers for technical accuracy
- Participate in QA to validate documentation against actual feature behavior
- Maintain documentation standards and style guides

### Goals
- Reduce support burden through clear, comprehensive documentation
- Accelerate user adoption and feature usage
- Enable efficient team onboarding and knowledge sharing
- Maintain high documentation quality and consistency

### Typical Communication
- Feature documentation shared with team and users
- Release notes and announcements to customers and stakeholders
- Documentation feedback from QA and Developers
- Process improvement suggestions from team retrospectives

### Interactions
- **Developers**: Receive technical details, implementation insights, and API specifications
- **Product Managers**: Understand feature specs, use cases, and customer messaging
- **QA**: Validate documentation accuracy against actual feature behavior

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD infrastructure, manage deployment reliability, and advise teams on infrastructure best practices. They enable fast, safe, and automated delivery to production.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Configure and manage cloud infrastructure and environments (dev, staging, prod)
- Implement security scanning and compliance checks in the pipeline
- Advise Developers on infrastructure best practices and deployment strategies
- Ensure rollback procedures and incident response readiness
- Monitor deployment logs and post-release verification

### Goals
- Enable fast, reliable, and safe deployments to production
- Reduce manual work and human error in release processes
- Minimize deployment incidents and recovery time
- Support team scaling and infrastructure reliability

### Typical Communication
- CI/CD pipeline documentation and runbooks shared with Developers
- Deployment readiness checklists reviewed with Project Managers and QA
- Infrastructure requirements and constraints discussed with Developers
- Post-incident reviews and process improvements with teams

### Interactions
- **Developers**: Provide CI/CD guidance, deployment troubleshooting, and infrastructure requirements
- **QA**: Coordinate release gates, staging environment setup, and smoke test execution
- **Project Managers**: Update on deployment timelines, risks, and release readiness

---

## Cross-Functional Collaboration Matrix

| Role | Works Closely With | Key Handoffs | Communication Frequency |
|------|---|---|---|
| **Developer** | Product Manager, QA, DevOps, Tech Writer | Code PRs, Technical specs, Implementation questions | Daily standup, PR reviews |
| **Product Manager** | Developers, UX Designer, Data Analyst, Project Manager | Requirements, Success metrics, Prioritization | Weekly alignment |
| **Project Manager** | All roles | Timeline updates, Risk registers, Status reports | Daily standup, Weekly sync |
| **UX Designer** | Product Manager, Developers, QA | Design specs, Wireframes, Usability feedback | Design reviews, Handoff meetings |
| **Data Analyst** | Product Manager, Project Manager, Developers | Metrics definitions, Dashboards, Insights | Weekly reports, Ad-hoc analysis |
| **Technical Writer** | Developers, Product Manager, QA | Feature docs, Release notes, User guides | During feature development, Before release |
| **DevOps Engineer** | Developers, QA, Project Manager | CI/CD setup, Deployment runbooks, Infrastructure | As needed, Release week |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the collaboration matrix to understand handoffs and communication patterns for specific scenarios.
- When planning cross-functional initiatives, consult the "Interactions" section of each role to identify required stakeholders and communication touch points.
