# OctoAcme — Role Handoff Checklist

## Purpose
Provide a reusable checklist to ensure clean, complete handoffs between roles at key transition points in the project lifecycle. Complete a copy of the relevant section each time a handoff occurs.

---

## How to Use
1. Copy the relevant section below into your project board, PR description, or shared doc.
2. Assign the checklist to the responsible owner.
3. Both the sending and receiving roles should confirm completion.
4. File the completed checklist with the project artifacts.

---

## 1 — Requirements to Development Handoff

**Trigger:** Sprint planning complete; stories accepted into sprint.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | All user stories in the sprint are written with clear, testable acceptance criteria | Business Analyst / Product Manager | ☐ |
| 2 | Story dependencies identified and noted | Business Analyst | ☐ |
| 3 | UI/UX design specs linked or attached (for UI-facing stories) | UX Designer | ☐ |
| 4 | Compliance or regulatory constraints documented on relevant stories | Compliance/Legal Reviewer | ☐ |
| 5 | Developers have reviewed stories and confirmed they are understood | Development Lead | ☐ |
| 6 | Definition of Done agreed upon for this sprint | Scrum Master | ☐ |
| 7 | Test cases drafted for critical stories | QA/Test Engineer | ☐ |

**Sign-off:**
- Sending: Business Analyst / Product Manager — Name: ___________ Date: ___________
- Receiving: Development Lead — Name: ___________ Date: ___________

---

## 2 — Design to Development Handoff

**Trigger:** Design review approved; feature ready for implementation.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | Final design specs exported/linked (e.g., Figma URL, annotated wireframes) | UX Designer | ☐ |
| 2 | Responsive and accessibility requirements documented | UX Designer | ☐ |
| 3 | Edge cases and error states covered in designs | UX Designer | ☐ |
| 4 | Design reviewed and accepted by Product Manager | Product Manager | ☐ |
| 5 | Developers attended design handoff session or async review confirmed | Development Lead | ☐ |
| 6 | Open design questions logged with resolution owners | UX Designer | ☐ |

**Sign-off:**
- Sending: UX Designer — Name: ___________ Date: ___________
- Receiving: Development Lead — Name: ___________ Date: ___________

---

## 3 — Development to QA Handoff

**Trigger:** PR merged; feature available in test environment.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | Feature branch merged and deployed to test environment | Developer | ☐ |
| 2 | Test environment URL and credentials provided to QA | Developer | ☐ |
| 3 | Unit and integration test results passing (CI link attached) | Developer | ☐ |
| 4 | Known limitations or deferred items documented in PR or ticket | Developer | ☐ |
| 5 | Acceptance criteria confirmed met by Developer before handing off | Developer | ☐ |
| 6 | QA test plan reviewed and test cases ready | QA/Test Engineer | ☐ |
| 7 | Test data requirements confirmed | QA/Test Engineer | ☐ |

**Sign-off:**
- Sending: Developer — Name: ___________ Date: ___________
- Receiving: QA/Test Engineer — Name: ___________ Date: ___________

---

## 4 — QA to Release Handoff

**Trigger:** All test cases passed; no blocking defects remain.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | All acceptance criteria verified and documented in test results | QA/Test Engineer | ☐ |
| 2 | No P1/P2 defects open; P3 defects documented with risk assessment | QA/Test Engineer | ☐ |
| 3 | Regression suite passed (automated or manual) | QA/Test Engineer | ☐ |
| 4 | UX/accessibility acceptance criteria verified | QA/Test Engineer | ☐ |
| 5 | Compliance test cases executed and results recorded | QA/Test Engineer | ☐ |
| 6 | QA release readiness report shared with Project Manager and Product Manager | QA/Test Engineer | ☐ |
| 7 | Compliance/Legal sign-off received (if required) | Compliance/Legal Reviewer | ☐ |
| 8 | Release notes drafted and reviewed | Project Manager / Product Manager | ☐ |
| 9 | Rollback plan documented | Project Manager / Developer | ☐ |

**Sign-off:**
- Sending: QA/Test Engineer — Name: ___________ Date: ___________
- Sending: Compliance/Legal Reviewer (if applicable) — Name: ___________ Date: ___________
- Receiving: Project Manager — Name: ___________ Date: ___________

---

## 5 — Release to Post-Release / Operations Handoff

**Trigger:** Deployment to production complete.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | Deployment executed and post-deploy verifications complete | Developer | ☐ |
| 2 | Monitoring and alerting confirmed active for new features | Developer | ☐ |
| 3 | Release notes published to stakeholders | Project Manager | ☐ |
| 4 | Support team briefed on new functionality and known issues | Project Manager / Product Manager | ☐ |
| 5 | On-call rotation aware of changes and escalation path | Project Manager | ☐ |
| 6 | Rollback plan accessible and on-call knows how to trigger it | Developer / Project Manager | ☐ |

**Sign-off:**
- Sending: Project Manager — Name: ___________ Date: ___________
- Receiving: On-Call / Support Lead — Name: ___________ Date: ___________

---

## 6 — Retrospective Close Handoff

**Trigger:** Retrospective complete; action items assigned.

| # | Checklist Item | Owner | Done? |
|---|---|---|---|
| 1 | Retrospective notes documented and shared with team | Scrum Master | ☐ |
| 2 | Action items logged with owners and target dates | Scrum Master / Project Manager | ☐ |
| 3 | Process improvements identified and added to next sprint backlog | Product Manager / Project Manager | ☐ |
| 4 | Project artifacts archived | Project Manager | ☐ |
| 5 | Final outcome summary shared with Sponsor | Project Manager | ☐ |

**Sign-off:**
- Sending: Scrum Master — Name: ___________ Date: ___________
- Receiving: Project Manager — Name: ___________ Date: ___________

---

## Escalation Quick Reference

If a handoff cannot be completed, escalate using the paths defined in the [Role Interaction and Ownership Matrix](octoacme-role-interaction-and-ownership-matrix.md).

## Related Documents

- [Roles and Personas](octoacme-roles-and-personas.md)
- [Role Interaction and Ownership Matrix](octoacme-role-interaction-and-ownership-matrix.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
