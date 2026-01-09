# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, security, compliance)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Include Customer Support Lead in feature launches and breaking changes
- Notify Security Champion of security-related changes or risks
- Share UX research findings and design decisions with relevant stakeholders

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **General issues**: Team-level -> PM -> Product Lead -> Sponsor
- **Security incidents**: Immediately notify Security Champion -> Security on-call -> Follow security incident runbook
- **Customer-impacting incidents**: Customer Support Lead -> PM -> Product Lead -> Customer communications
- **Infrastructure/reliability issues**: DevOps Engineer -> Engineering Lead -> Infrastructure team escalation
- **Data/privacy concerns**: Data Analyst -> Security Champion -> Compliance/Legal as needed
