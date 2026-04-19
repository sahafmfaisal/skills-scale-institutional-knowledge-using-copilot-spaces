# OctoAcme — Role Interaction and Ownership Matrix

## Purpose
Clarify who owns, approves, contributes to, or is informed of key activities across the OctoAcme project lifecycle. Use this matrix to reduce ambiguity at role handoffs and to define clear escalation paths.

## Legend

| Symbol | Meaning |
|--------|---------|
| **O** | Owner — accountable for the activity; drives completion |
| **A** | Approver — must sign off before the activity can be considered complete |
| **C** | Contributor — provides input, completes sub-tasks, or reviews |
| **I** | Informed — receives updates but does not need to act |

## Roles Abbreviation Key

| Abbreviation | Role |
|---|---|
| PM | Project Manager |
| PdM | Product Manager |
| Dev | Developer |
| QA | QA/Test Engineer |
| BA | Business Analyst |
| UX | UX Designer |
| SM | Scrum Master |
| SP | Sponsor |
| CL | Compliance/Legal Reviewer |

---

## Lifecycle Activity Ownership Matrix

### Phase 1 — Initiation

| Activity | PM | PdM | Dev | QA | BA | UX | SM | SP | CL |
|---|---|---|---|---|---|---|---|---|---|
| Define problem statement and project goals | C | O | I | I | C | I | I | A | I |
| Draft project charter / one-pager | O | C | I | I | C | I | I | A | I |
| Identify stakeholders and communication plan | O | C | I | I | C | I | I | I | I |
| Identify compliance/regulatory requirements | C | C | I | I | C | I | I | I | O |
| Approve project initiation (go/no-go) | C | C | I | I | I | I | I | A | C |
| Define initial risk list | O | C | C | I | C | I | I | I | C |

### Phase 2 — Planning

| Activity | PM | PdM | Dev | QA | BA | UX | SM | SP | CL |
|---|---|---|---|---|---|---|---|---|---|
| Create and maintain project plan and timeline | O | C | C | I | I | I | C | I | I |
| Define and prioritize backlog | C | O | C | I | C | I | C | I | I |
| Write user stories and acceptance criteria | C | C | C | C | O | C | I | I | C |
| Create UX wireframes and prototypes | I | C | C | I | C | O | I | I | I |
| Define test strategy and test plan | C | I | C | O | C | I | I | I | C |
| Identify resource needs and confirm team | O | C | C | I | I | I | I | A | I |
| Sprint planning facilitation | C | C | C | C | C | C | O | I | I |

### Phase 3 — Execution

| Activity | PM | PdM | Dev | QA | BA | UX | SM | SP | CL |
|---|---|---|---|---|---|---|---|---|---|
| Feature development and code reviews | I | I | O | C | I | C | I | I | I |
| Daily standup facilitation | I | I | C | C | I | I | O | I | I |
| Blocker identification and resolution | C | C | C | C | C | C | O | C | I |
| Requirement clarification during development | I | C | C | I | O | C | I | I | I |
| UX design review and fidelity verification | I | C | C | I | I | O | I | I | I |
| Defect logging and triage | I | C | C | O | C | C | I | I | I |
| Status reporting and stakeholder updates | O | C | I | I | I | I | I | I | I |
| Risk monitoring and escalation | O | C | C | C | C | I | C | C | I |

### Phase 4 — Release

| Activity | PM | PdM | Dev | QA | BA | UX | SM | SP | CL |
|---|---|---|---|---|---|---|---|---|---|
| Pre-release readiness assessment | O | C | C | C | I | C | I | I | C |
| Final QA sign-off | I | I | C | O | I | C | I | I | C |
| Compliance/legal sign-off | C | C | I | C | I | I | I | A | O |
| Release notes drafting | O | C | C | C | C | I | I | I | C |
| Deployment execution | C | I | O | C | I | I | I | I | I |
| Post-deploy verification | C | I | C | O | I | C | I | I | I |
| Release announcement to stakeholders | O | C | I | I | I | I | I | I | I |
| Rollback / incident decision | O | C | C | C | I | I | I | A | I |

### Phase 5 — Retrospective & Close

| Activity | PM | PdM | Dev | QA | BA | UX | SM | SP | CL |
|---|---|---|---|---|---|---|---|---|---|
| Facilitate retrospective | C | C | C | C | C | C | O | I | I |
| Capture learnings and action items | O | C | C | C | C | C | C | I | I |
| Update process documentation | O | C | C | C | C | C | C | I | I |
| Communicate outcomes to sponsor/stakeholders | O | C | I | I | I | I | I | I | I |
| Archive project artifacts | O | I | C | C | C | I | I | I | C |

---

## Key Handoff Points

| Handoff | From | To | Trigger | Artifact / Signal |
|---|---|---|---|---|
| Requirements to development | BA / PdM | Dev | Sprint planning complete | Refined user stories with acceptance criteria |
| Design to development | UX | Dev | Design review approved | Finalized design specs (e.g., Figma link) |
| Development to QA | Dev | QA | PR merged / feature branch ready | PR link + test environment URL |
| QA sign-off to release | QA | PM / PdM | All test cases passed, no blocking defects | QA release readiness report |
| Compliance review to release | CL | PM | Compliance checks complete | Written compliance sign-off |
| Release to operations | Dev / PM | On-call / Support | Deploy complete | Release notes + post-deploy verification |
| Retrospective actions to next cycle | SM / PM | Whole team | Retrospective complete | Action items logged in project board |

---

## Escalation Paths

| Situation | First Escalation | Second Escalation |
|---|---|---|
| Sprint blocker unresolved > 1 day | Scrum Master → Project Manager | Project Manager → Sponsor |
| Scope change requested mid-sprint | Product Manager decides | Sponsor approves if significant impact |
| Critical defect blocks release | QA + PM assess risk and options | Sponsor makes go/no-go call |
| Compliance concern raised | Compliance/Legal Reviewer + PM | Sponsor and/or Legal leadership |
| Key team member unavailable | Project Manager reallocates | Sponsor approves resource changes |
| Customer-impacting incident | PM + Dev triage | Sponsor notified; Incident Lead coordinates |

---

## Related Documents

- [Roles and Personas](octoacme-roles-and-personas.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Role Handoff Checklist](octoacme-role-handoff-checklist.md)
