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

## QA / Testing

### Role Summary
QA Engineers validate that features meet acceptance criteria, quality standards, and performance expectations before release.

### Responsibilities
- Write and execute test plans and test cases
- Report, track, and verify defects
- Collaborate with Developers on testability and test coverage
- Participate in release readiness decisions

### Goals
- Prevent regressions and defects from reaching production
- Ensure acceptance criteria are fully verified
- Improve overall quality feedback loops

### Typical Communication
- Sprint reviews and defect triage sessions
- Test reports and sign-off confirmations
- Coordination with DevOps on test pipeline coverage

---

## UX Designer

### Role Summary
UX Designers create user interfaces and experience flows that align with product vision and meet user needs. They bridge product requirements and engineering implementation.

### Responsibilities
- Design wireframes, prototypes, and final UI specifications
- Conduct usability testing and synthesize user feedback
- Collaborate with Product Managers on acceptance criteria and user stories
- Review implemented UI and flag deviations from design intent

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce rework by aligning design and engineering early
- Ensure user needs are represented throughout the lifecycle

### Typical Communication
- Design review sessions with PM and Developers
- Figma/design tool handoffs with annotated specs
- Usability test summaries and feedback synthesis

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain build pipelines, deployment automation, and infrastructure reliability. They enable teams to release quickly and safely.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Coordinate with Developers and QA on release processes
- Ensure operational reliability, monitoring, and alerting
- Respond to incidents and lead post-deployment verifications

### Goals
- Minimize deployment risk and time-to-production
- Maintain high system availability and observability
- Enable self-service releases with appropriate guardrails

### Typical Communication
- Release planning meetings and deployment windows
- Incident post-mortems and runbook updates
- Pipeline status notifications and on-call rotations

---

## Security Champion

### Role Summary
Security Champions advocate for secure development practices within the team and act as the first line of defense for identifying and mitigating security risks.

### Responsibilities
- Conduct threat modeling and security reviews for new features
- Collaborate with Developers and DevOps on secure coding and pipeline hardening
- Track security findings and coordinate remediation
- Coordinate with incident response when security issues arise

### Goals
- Reduce security risk throughout the development lifecycle
- Build security awareness and practices within the team
- Ensure compliance with applicable security policies

### Typical Communication
- Threat modeling sessions during planning or design
- Security review sign-offs before major releases
- Vulnerability reports and remediation tracking

---

## Stakeholder Liaison

### Role Summary
Stakeholder Liaisons serve as the primary contact for external or internal stakeholders, ensuring their inputs are captured and communicated back to the team.

### Responsibilities
- Gather and communicate stakeholder requirements, concerns, and feedback
- Provide regular project status updates to stakeholders
- Ensure stakeholder feedback is integrated into planning and retrospectives
- Manage escalation paths for stakeholder issues

### Goals
- Maintain stakeholder trust and engagement throughout the project
- Prevent misalignment between stakeholder expectations and delivery
- Facilitate timely decisions when stakeholder input is needed

### Typical Communication
- Monthly (or more frequent) stakeholder briefings
- Summary emails after key milestones or decisions
- Intake forms or structured feedback channels

---

## Customer Support Lead

### Role Summary
Customer Support Leads monitor customer feedback and support activity, translating user pain points into actionable inputs for the product and engineering teams.

### Responsibilities
- Monitor support tickets, customer feedback, and common escalations
- Collaborate with Product Managers and Developers to prioritize fixes and improvements
- Provide customer insight during retrospectives and planning
- Help ensure documentation and release notes address common customer questions

### Goals
- Reduce repeat support issues through product and documentation improvements
- Ensure releases are customer-centric and well-communicated
- Close the loop between customer experience and development priorities

### Typical Communication
- Weekly ticket trend summaries shared with PM and PdM
- Retrospective contributions with customer impact data
- Support readiness review before major releases

---

## Interaction Points

The table below provides a lightweight overview of how roles engage across the project lifecycle. It is intended to improve clarity on handoffs, not to replace judgment.

| Lifecycle Phase | PM | PdM | UX Designer | DevOps Engineer | Security Champion | Stakeholder Liaison | Customer Support Lead | Developers | QA |
|---|---|---|---|---|---|---|---|---|---|
| **Initiation** | Leads | Defines goals & metrics | Provides UX research inputs | Advises on infra constraints | Flags early security considerations | Engages stakeholders, captures needs | Provides customer pain-point data | Advises on feasibility | — |
| **Planning** | Coordinates | Prioritizes backlog | Designs flows & wireframes | Plans pipeline and infra needs | Conducts threat modeling | Ensures stakeholder alignment | Flags customer-impacting risks | Estimates and reviews design | Reviews testability |
| **Execution & Tracking** | Tracks progress, manages blockers | Refines acceptance criteria | Reviews UI implementation, iterates | Maintains pipelines, unblocks CI issues | Reviews code/PRs for security issues | Communicates status updates | — | Implements features | Tests and reports defects |
| **Release & Deployment** | Coordinates release readiness | Signs off on scope | Confirms UI meets design intent | Leads deployment, verifies production | Signs off security scan results | Notifies stakeholders of release | Prepares support team & documentation | Supports deployment | Confirms acceptance criteria met |
| **Retrospective & Improvement** | Facilitates | Reviews outcomes vs. metrics | Shares usability learnings | Reviews pipeline performance | Reviews security posture | Reports stakeholder feedback | Shares customer support trends | Contributes technical learnings | Shares quality metrics |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Collaboration Checklist](./octoacme-role-collaboration-checklist.md) for a practical guide to engaging the right roles at the right time.

