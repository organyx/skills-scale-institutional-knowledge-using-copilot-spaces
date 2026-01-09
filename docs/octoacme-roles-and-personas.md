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

## QA/Testing

### Role Summary
QA/Testing professionals ensure product quality through systematic testing, validation of acceptance criteria, and early identification of defects. They work closely with developers and product teams to define quality standards and testing strategies.

### Responsibilities
- Design and execute test plans (manual and automated)
- Validate features against acceptance criteria
- Identify, document, and track defects
- Participate in sprint planning and backlog refinement
- Contribute to Definition of Done and quality standards

### Goals
- Minimize defects reaching production
- Improve test coverage and automation
- Reduce time from bug detection to resolution

### Typical Communication
- Daily standups and sprint ceremonies
- Bug reports and test case documentation
- Quality metrics and release readiness reports

### Interactions with Other Roles
- **Developers**: Collaborate on testability, reproduce bugs, review fixes
- **Product Managers**: Clarify acceptance criteria, prioritize bug fixes
- **Project Managers**: Report on quality status and testing progress
- **DevOps Engineers**: Integrate automated tests into CI/CD pipelines
- **UX Designers**: Validate user experience and accessibility standards

---

## UX Designer

### Role Summary
UX Designers create intuitive, accessible, and delightful user experiences. They conduct user research, design interfaces, create prototypes, and validate designs through testing and feedback.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define design systems and style guides
- Collaborate with product and engineering on feature design
- Ensure accessibility (WCAG) compliance
- Validate designs with user feedback and analytics

### Goals
- Improve user satisfaction and engagement
- Reduce friction in user workflows
- Ensure consistent, accessible experiences across products

### Typical Communication
- Design reviews and critiques
- User research findings and personas
- Prototype demonstrations and design specs

### Interactions with Other Roles
- **Product Managers**: Align on user needs, feature priorities, and success metrics
- **Developers**: Provide design specs, collaborate on feasibility and implementation
- **QA/Testing**: Partner on usability testing and acceptance criteria
- **Data Analysts**: Review user behavior data to inform design decisions
- **Customer Support Lead**: Gather feedback on pain points and usability issues

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, automation, and tooling that enables reliable, efficient delivery. They bridge development and operations, focusing on CI/CD, monitoring, and system reliability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage cloud infrastructure and deployment automation
- Implement monitoring, alerting, and observability
- Ensure system reliability, performance, and security
- Support incident response and post-mortems
- Optimize build times and deployment processes

### Goals
- Minimize deployment friction and lead time
- Maximize system uptime and reliability
- Enable rapid, safe releases through automation

### Typical Communication
- Infrastructure-as-code pull requests
- Incident reports and post-mortems
- Performance and reliability metrics dashboards

### Interactions with Other Roles
- **Developers**: Provide tooling, support builds, troubleshoot deployment issues
- **Security Champion**: Implement security controls, scanning, and compliance
- **Project Managers**: Report on infrastructure readiness and deployment timelines
- **QA/Testing**: Integrate automated testing into pipelines
- **Customer Support Lead**: Collaborate on production incident response

---

## Data Analyst

### Role Summary
Data Analysts collect, analyze, and interpret data to inform product and business decisions. They build dashboards, conduct experiments, and provide insights that guide prioritization and strategy.

### Responsibilities
- Define and track key performance indicators (KPIs)
- Build dashboards and reports for stakeholders
- Conduct A/B tests and analyze experiment results
- Provide data-driven insights for feature prioritization
- Ensure data quality and governance
- Support product teams with usage analytics

### Goals
- Enable data-driven decision making
- Improve measurement of product success
- Identify opportunities through data insights

### Typical Communication
- Analytics dashboards and metric reports
- Experiment results and recommendations
- Data quality and governance documentation

### Interactions with Other Roles
- **Product Managers**: Define success metrics, analyze feature performance
- **UX Designers**: Provide user behavior data and funnel analysis
- **Developers**: Instrument logging and analytics tracking
- **Project Managers**: Report on progress against success metrics
- **Customer Support Lead**: Analyze support trends and user pain points

---

## Customer Support Lead

### Role Summary
Customer Support Leads manage the support team, ensure customer issues are resolved effectively, and serve as the voice of the customer in product development. They identify trends, escalate critical issues, and drive support process improvements.

### Responsibilities
- Manage support team and response processes
- Triage and escalate customer issues
- Track support metrics (response time, resolution rate, CSAT)
- Provide customer feedback to product and engineering
- Create and maintain support documentation
- Coordinate on product launches and feature rollouts

### Goals
- Maximize customer satisfaction and retention
- Reduce mean time to resolution (MTTR)
- Proactively identify and address customer pain points

### Typical Communication
- Support ticket trends and escalations
- Customer feedback summaries
- Release readiness and known issues documentation

### Interactions with Other Roles
- **Product Managers**: Share customer feedback, influence roadmap priorities
- **Developers**: Escalate bugs, provide reproduction steps
- **UX Designers**: Highlight usability issues and friction points
- **DevOps Engineers**: Coordinate during incidents and outages
- **Project Managers**: Provide input on feature launches and communication plans

---

## Security Champion

### Role Summary
Security Champions embed security practices across the development lifecycle. They conduct threat modeling, security reviews, and vulnerability assessments while fostering a security-aware culture.

### Responsibilities
- Conduct security reviews and threat modeling
- Implement secure coding practices and guidelines
- Manage vulnerability scanning and remediation
- Ensure compliance with security policies and regulations
- Provide security training and awareness
- Respond to security incidents and coordinate fixes

### Goals
- Minimize security vulnerabilities in production
- Ensure compliance with security standards
- Build security awareness across the team

### Typical Communication
- Security review findings and recommendations
- Vulnerability reports and remediation plans
- Security incident communications

### Interactions with Other Roles
- **Developers**: Review code for security issues, provide secure coding guidance
- **DevOps Engineers**: Implement security scanning in CI/CD, harden infrastructure
- **Product Managers**: Assess security risks in new features, prioritize fixes
- **Project Managers**: Report on security readiness and compliance status
- **QA/Testing**: Collaborate on security testing and penetration tests

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

