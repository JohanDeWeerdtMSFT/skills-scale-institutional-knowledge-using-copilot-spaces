# OctoAcme — Role Collaboration Checklist

## Purpose
A practical reference for Project Managers (PM) and Product Managers (PdM) to confirm the right roles are engaged at the right time. Use this alongside the [Roles and Personas](./octoacme-roles-and-personas.md) doc.

---

## Initiation

- [ ] **PM/PdM**: Draft project one-pager (see [Project Initiation Guide](./octoacme-project-initiation.md))
- [ ] **Stakeholder Liaison**: Identify and list all key stakeholders; confirm communication plan
- [ ] **UX Designer**: Provide available user research or pain-point data to inform the problem statement
- [ ] **Customer Support Lead**: Share known customer pain points relevant to the proposed scope
- [ ] **Security Champion**: Flag any early security or compliance considerations
- [ ] **DevOps Engineer**: Identify infrastructure or pipeline constraints that may affect feasibility
- [ ] **PM**: Confirm team availability and role assignments before moving to planning

---

## Planning

- [ ] **PdM**: Finalize prioritized backlog with acceptance criteria
- [ ] **UX Designer**: Complete initial wireframes or design flows; schedule design review with PM and Developers
- [ ] **Security Champion**: Conduct or schedule threat modeling session for new features
- [ ] **DevOps Engineer**: Document pipeline, environment, and infra needs; flag any new tooling requirements
- [ ] **Stakeholder Liaison**: Confirm stakeholder alignment on scope and milestones
- [ ] **Customer Support Lead**: Review backlog for items surfaced from customer feedback; confirm prioritization
- [ ] **QA**: Review planned work for testability; flag gaps in acceptance criteria
- [ ] **PM**: Update risk register with inputs from all roles (see [Risks & Communication](./octoacme-risks-and-communication.md))

---

## Execution & Tracking

- [ ] **PM**: Run regular standups; track blockers and escalate as needed
- [ ] **UX Designer**: Review implemented UI against design specs; provide timely feedback to Developers
- [ ] **Security Champion**: Review security-sensitive PRs or features during code review
- [ ] **DevOps Engineer**: Monitor CI/CD pipelines; resolve build or environment issues promptly
- [ ] **Stakeholder Liaison**: Send regular status updates; collect stakeholder feedback between milestones
- [ ] **QA**: Execute test plans; report and track defects; flag scope or criteria changes
- [ ] **PdM**: Refine upcoming stories; accept or reject completed work against criteria

---

## Release & Deployment

- [ ] **PM**: Confirm release readiness across all roles before scheduling deployment
- [ ] **PdM**: Sign off that scope and acceptance criteria are met
- [ ] **UX Designer**: Confirm UI matches approved design intent
- [ ] **Security Champion**: Review security scan results; sign off on release from a security perspective
- [ ] **DevOps Engineer**: Execute or coordinate deployment; run post-deploy smoke tests (see [Release & Deployment Guide](./octoacme-release-and-deployment.md))
- [ ] **QA**: Confirm all acceptance criteria verified; provide final sign-off
- [ ] **Customer Support Lead**: Prepare support team with release notes, known issues, and expected customer impact
- [ ] **Stakeholder Liaison**: Notify stakeholders of the release; distribute release summary

---

## Retrospective & Continuous Improvement

- [ ] **PM**: Facilitate retrospective session (see [Retrospective Guide](./octoacme-retrospective-and-continuous-improvement.md))
- [ ] **PdM**: Review outcomes against success metrics; update roadmap as needed
- [ ] **UX Designer**: Share usability learnings and any outstanding design debt
- [ ] **Security Champion**: Review security posture; add any new findings to the risk register
- [ ] **DevOps Engineer**: Review pipeline and deployment performance; document improvements
- [ ] **Customer Support Lead**: Present customer support trends and feedback for the sprint/release
- [ ] **Stakeholder Liaison**: Summarize stakeholder feedback from the period
- [ ] **PM**: Document action items and owners; track to completion in next planning cycle

---

## Quick Reference: Who to Involve for Key Activities

| Activity | Key Roles |
|---|---|
| Design review | UX Designer, PdM, Developers |
| Threat modeling | Security Champion, PdM, Developers |
| Release readiness review | PM, PdM, QA, DevOps Engineer, Security Champion, Customer Support Lead |
| Support readiness | Customer Support Lead, PM, PdM |
| Stakeholder communications | Stakeholder Liaison, PM, PdM |
| Incident response | DevOps Engineer, Security Champion, PM |
| Backlog grooming | PdM, Customer Support Lead, Developers, QA |
