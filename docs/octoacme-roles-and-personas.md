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

## Release Manager

### Role Summary
Release Managers oversee release planning, coordinate deployments, and ensure smooth delivery to production. They own the release process end-to-end, including rollback planning, incident communication, and stakeholder alignment during releases.

### Responsibilities
- Plan and schedule releases in coordination with development and QA teams
- Ensure rollback and mitigation plans are documented and tested
- Communicate release status, timelines, and incidents to stakeholders
- Coordinate with Dev, QA, and Support to triage critical issues during releases
- Maintain release notes and deployment documentation
- Monitor post-deployment health and trigger incident response when needed

### Goals
- Deliver stable, low-risk releases on schedule
- Minimize deployment failures and rollbacks
- Maintain clear communication with all stakeholders during release windows
- Continuously improve release processes based on lessons learned

### Typical Communication
- Release planning meetings with Dev, QA, and Product teams
- Pre-release and post-release announcements to stakeholders
- Incident status updates during deployment issues
- Coordination with Support for go-live handoffs

---

## QA Lead

### Role Summary
QA Leads define and own the quality assurance strategy, ensuring that products meet acceptance criteria and quality standards before release. They coordinate testing activities, manage defect tracking, and provide release signoff.

### Responsibilities
- Define test strategy, standards, and acceptance criteria
- Coordinate manual and automated testing efforts across the team
- Track defect metrics, manage bug triage, and prioritize fixes
- Provide release signoff based on quality gates
- Collaborate with Developers and Product Managers on quality trade-offs
- Maintain test documentation and ensure test coverage for critical flows

### Goals
- Ensure high product quality and reliability
- Reduce escaped defects to production
- Improve test coverage and automation over time
- Enable fast, confident release decisions

### Typical Communication
- Daily standup participation with focus on testing status
- Bug triage meetings with Dev and Product teams
- Test status reports and release readiness assessments
- Quality metrics dashboards and trend analysis

---

## UX Designer

### Role Summary
UX Designers establish user experience standards, ensure accessibility compliance, and collaborate with Product and Development teams to deliver intuitive, user-friendly interfaces. They advocate for the end user throughout the design and development process.

### Responsibilities
- Define UX standards, design patterns, and accessibility goals
- Create wireframes, mockups, and prototypes for new features
- Conduct user research and usability testing
- Collaborate with Product Managers on requirements and prioritization
- Work with Developers to ensure UI implementation matches design intent
- Review designs and provide feedback during development

### Goals
- Deliver intuitive, accessible user experiences
- Ensure consistency across product interfaces
- Incorporate user feedback into design decisions
- Reduce user friction and improve task completion rates

### Typical Communication
- Design reviews with Product and Development teams
- User research readouts and usability test findings
- Design documentation and pattern library updates
- Accessibility audit reports and remediation plans

---

## Support Lead

### Role Summary
Support Leads own post-release monitoring, incident response, and user feedback triage. They serve as the bridge between users, development teams, and stakeholders, ensuring production issues are addressed promptly and feedback is incorporated into future work.

### Responsibilities
- Own post-release monitoring and incident response coordination
- Triage user feedback, bug reports, and production issues
- Escalate critical issues to Development and Release Manager
- Provide status updates to Project Manager and stakeholders
- Maintain support documentation and runbooks
- Coordinate with QA on defect prioritization and regression testing

### Goals
- Minimize user impact from production issues
- Ensure timely resolution of support tickets and incidents
- Capture and communicate user feedback to inform product decisions
- Maintain high customer satisfaction and trust

### Typical Communication
- Incident response coordination and status updates
- Weekly support metrics and trend reports
- Handoff meetings with Development and QA teams
- Customer communication for critical issues

---

## Technical Writer

### Role Summary
Technical Writers maintain process and user documentation, ensuring that knowledge is captured, organized, and accessible. They work across teams to document updates, new workflows, and best practices, and distill lessons learned into actionable improvements.

### Responsibilities
- Maintain process documentation, user guides, and runbooks
- Work with teams to document new features, workflows, and changes
- Distill feedback and lessons learned into documentation updates
- Ensure documentation is accurate, up-to-date, and easy to find
- Collaborate with Product and Development on release notes and announcements
- Review and improve documentation based on user feedback

### Goals
- Ensure comprehensive, accurate documentation across projects
- Reduce onboarding time for new team members
- Improve knowledge transfer and reduce repeated questions
- Maintain documentation as a living, evolving resource

### Typical Communication
- Documentation reviews with subject matter experts
- Release notes and announcement drafts
- Documentation update requests and change logs
- Onboarding sessions and knowledge transfer meetings

---

## Role Interaction Matrix

The following matrix shows typical interactions between personas during key project phases:

| Phase | Roles Involved | Key Interactions |
|-------|---------------|------------------|
| **Initiation** | Project Manager, Product Manager, UX Designer | Requirements gathering, stakeholder alignment, initial UX concepts |
| **Planning** | Project Manager, Product Manager, Developers, QA Lead, UX Designer | Sprint planning, test strategy definition, design reviews |
| **Execution** | Developers, QA Lead, UX Designer, Technical Writer | Development, testing, design implementation, documentation updates |
| **Release** | Release Manager, QA Lead, Developers, Support Lead | Release coordination, final QA signoff, deployment, support handoff |
| **Post-Release** | Support Lead, Release Manager, Project Manager, Technical Writer | Incident response, user feedback triage, lessons learned documentation |

---

## Practical Checklists and Handoff Templates

### Release Checklist

Use this checklist when preparing for a release:

- [ ] All acceptance criteria met and PRs merged
- [ ] QA Lead has provided release signoff
- [ ] Release notes drafted and reviewed (Technical Writer)
- [ ] Rollback/mitigation plan documented (Release Manager)
- [ ] Support Lead briefed on new features and known issues
- [ ] Deployment window scheduled and communicated to stakeholders
- [ ] Smoke tests prepared and staging deployment verified
- [ ] Post-deploy verification plan in place
- [ ] Stakeholder announcement prepared

### Support Handoff Template

Use this template when handing off a release to Support:

```
Release Name/Version:
Release Date:
Summary of Changes:
- Feature 1: [description]
- Feature 2: [description]
- Bug fixes: [list key fixes]

Known Issues:
- [Issue 1]: [workaround if applicable]
- [Issue 2]: [workaround if applicable]

Escalation Contacts:
- Release Manager: [name]
- QA Lead: [name]
- On-call Developer: [name]

Support Runbook Updates:
- [Link to updated runbook or documentation]

Rollback Plan:
- [Brief description or link to rollback procedure]
```

### QA Signoff Template

Use this template for formal QA release signoff:

```
Release Name/Version:
QA Lead: [name]
Signoff Date:

Test Summary:
- Total Test Cases: [number]
- Passed: [number]
- Failed: [number]
- Blocked: [number]

Outstanding Issues:
- [Issue ID]: [severity] - [status/plan]

Recommendation:
[ ] Approved for Release
[ ] Approved with Conditions (see notes)
[ ] Not Approved (see blockers)

Notes:
[Additional context or conditions for release]
```

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The Role Interaction Matrix helps understand how different personas collaborate during project phases.
- Checklists and templates provide practical guidance for handoffs and key process milestones.

