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

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and coach the team on iterative delivery practices. They serve the team rather than direct it, protecting the team's focus and pace.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Coach team members on agile principles and practices
- Shield the team from external interruptions during a sprint
- Track sprint velocity and help forecast delivery capacity

### Goals
- Maintain a healthy, self-organizing team cadence
- Reduce waste and improve flow across sprints
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Blocker escalations to Project Managers
- Retrospective action-item tracking

### Interactions with Other Roles
- **Developers:** Protects sprint commitments, resolves blockers, facilitates technical discussions during ceremonies.
- **Product Managers:** Coordinates backlog refinement sessions; ensures stories are ready before sprint planning.
- **Project Managers:** Escalates risks and cross-team dependencies that exceed the team's ability to resolve independently.
- **Business Analysts:** Aligns on story readiness criteria before each sprint.
- **Lifecycle touchpoints:** Planning, Execution, Retrospective.

---

## Business Analyst

### Role Summary
Business Analysts act as the bridge between business stakeholders and the delivery team, ensuring requirements are clearly documented, understood, and testable before development begins.

### Responsibilities
- Elicit, document, and validate requirements with stakeholders
- Write user stories and acceptance criteria in collaboration with Product Managers
- Support backlog refinement by clarifying feature details
- Participate in sprint reviews to validate delivered functionality against requirements
- Maintain a requirements traceability matrix for regulated features

### Goals
- Ensure the team builds the right thing by grounding work in well-defined requirements
- Reduce rework caused by late-breaking requirement changes
- Provide clear, shared understanding across business and engineering

### Typical Communication
- Requirement workshops and stakeholder interviews
- Written user stories and acceptance criteria documents
- Sprint review feedback sessions

### Interactions with Other Roles
- **Product Managers:** Translate high-level product goals into detailed, testable user stories; collaborate on prioritization.
- **Developers:** Clarify requirements during implementation; answer questions without changing scope mid-sprint.
- **QA/Test Engineers:** Provide acceptance criteria that form the basis of test cases.
- **Scrum Masters:** Flag unclear stories before sprint planning to prevent mid-sprint scope changes.
- **Lifecycle touchpoints:** Initiation, Planning, Execution.

---

## UX Designer

### Role Summary
UX Designers define and validate the user experience for product features, ensuring that what is built is intuitive, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research (interviews, usability tests, surveys)
- Create wireframes, prototypes, and final design specifications
- Collaborate with Developers on implementation feasibility and design fidelity
- Validate designs with real users prior to and after release
- Maintain a shared design system and style guide

### Goals
- Deliver experiences that are usable, accessible, and delightful
- Reduce user-reported usability issues post-release
- Ensure design decisions are grounded in evidence

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Usability test reports and recommendations
- Design specs delivered via a shared design tool (e.g., Figma)

### Interactions with Other Roles
- **Product Managers:** Align on user problems to solve before starting design; present research findings to inform prioritization.
- **Developers:** Hand off design specs; answer implementation questions; review built UI for design fidelity.
- **Business Analysts:** Collaborate on user story acceptance criteria to include UX pass/fail conditions.
- **QA/Test Engineers:** Define UX acceptance criteria (visual, accessibility) that QA can verify.
- **Lifecycle touchpoints:** Initiation (research), Planning (design), Execution (review & handoff), Release (post-release usability review).

---

## Sponsor

### Role Summary
The Sponsor is the executive champion who funds the project, aligns it with organizational strategy, and provides final authority on major decisions and escalations. They are accountable for the project's business outcomes.

### Responsibilities
- Approve the project charter and budget allocation
- Remove organizational blockers that escalate beyond the Project Manager's authority
- Make final go/no-go decisions at key lifecycle gates (initiation, release)
- Communicate project status and outcomes to senior leadership
- Champion the project's value internally to secure ongoing support

### Goals
- Ensure the project delivers measurable business value
- Maintain executive alignment and secure necessary resources
- Protect the project from organizational headwinds

### Typical Communication
- Monthly executive status briefings from Project Managers
- Decision requests via escalation paths when key risks materialize
- Charter and milestone approval sign-offs

### Interactions with Other Roles
- **Project Managers:** Primary point of contact for escalations and major decisions; receives periodic status reports.
- **Product Managers:** Aligns on business outcomes and strategic priorities; approves major scope changes.
- **Compliance/Legal Reviewers:** Reviews and approves compliance sign-offs for high-risk releases.
- **Lifecycle touchpoints:** Initiation (charter approval), Release (go/no-go), Retrospective (outcome review).

---

## Compliance/Legal Reviewer

### Role Summary
Compliance/Legal Reviewers ensure that project deliverables meet applicable regulatory, legal, and organizational policy requirements. They provide sign-off at key lifecycle gates to reduce legal and compliance risk.

### Responsibilities
- Review features and release artifacts for regulatory compliance (e.g., GDPR, SOC 2, accessibility standards)
- Identify and document compliance requirements during project initiation
- Provide sign-off on release readiness from a compliance perspective
- Flag legal risks early and recommend mitigations
- Maintain compliance documentation and audit trails

### Goals
- Prevent compliance violations that could expose the organization to risk
- Enable the team to move quickly with clear compliance guardrails
- Provide timely reviews that do not block delivery unnecessarily

### Typical Communication
- Asynchronous review of release notes and compliance checklists
- Scheduled review sessions at key lifecycle gates
- Written sign-off documentation for audit trails

### Interactions with Other Roles
- **Product Managers:** Engage early in planning to surface compliance requirements that affect scope or design.
- **Project Managers:** Coordinate review timelines to prevent last-minute release blockers.
- **Developers:** Clarify technical implementation requirements for compliance controls.
- **Sponsors:** Escalate unresolved compliance risks that require executive decision.
- **Lifecycle touchpoints:** Initiation (requirements), Planning (constraints), Release (sign-off).

---

## QA/Test Engineer

### Role Summary
QA/Test Engineers design and execute testing strategies to validate that deliverables meet acceptance criteria and quality standards before release. They are the final quality gate before production.

### Responsibilities
- Define test plans and test cases based on acceptance criteria
- Execute functional, regression, integration, and exploratory testing
- Log, triage, and track defects through resolution
- Collaborate with Developers on testability and test automation
- Provide release readiness assessments and sign-off

### Goals
- Prevent defects from reaching production
- Increase test automation coverage to accelerate delivery
- Provide objective quality signals to the team and stakeholders

### Typical Communication
- Test status reports and defect summaries during execution
- Release readiness sign-off communicated to Project Managers
- Automated test results integrated into CI/CD pipelines

### Interactions with Other Roles
- **Developers:** Collaborate on unit test coverage and automated integration tests; triage defects together.
- **Business Analysts:** Use acceptance criteria as the basis for test case design.
- **Product Managers:** Communicate quality risks that may affect release scope or timelines.
- **Project Managers:** Report test progress and escalate blocking defects.
- **UX Designers:** Validate UX acceptance criteria including accessibility checks.
- **Compliance/Legal Reviewers:** Execute compliance-specific test cases where required.
- **Lifecycle touchpoints:** Planning (test planning), Execution (testing), Release (sign-off).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role Interaction and Ownership Matrix](octoacme-role-interaction-and-ownership-matrix.md) for RACI-style ownership across lifecycle phases.
- See [Role Handoff Checklist](octoacme-role-handoff-checklist.md) for a reusable cross-role coordination template.

