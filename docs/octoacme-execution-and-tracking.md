# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (SAST, dependency checks, container scanning)
- Accessibility testing for user-facing features (WCAG compliance)
- Performance and load testing for high-traffic features
- Manual QA for feature acceptance when needed
- Usability testing with real users (coordinated with UX Designer)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager (with Data Analyst)
- Use dashboards for key signals (errors, latency, usage)
- Track user feedback and satisfaction scores (CSAT, NPS)
- Monitor security vulnerabilities and remediation status
- Review accessibility compliance metrics
- Analyze support ticket trends and resolution times

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security escalations**: Follow security incident runbook, notify Security Champion and on-call immediately
- **Customer-impacting issues**: Coordinate with Customer Support Lead for communication and mitigation

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
