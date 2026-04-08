# OctoAcme Project Management Documentation

Welcome! This README provides an overview of how OctoAcme manages projects, with direct links to comprehensive process guidance.

## OctoAcme Project Management Approach

OctoAcme uses a structured, lifecycle-based project management methodology grounded in **five core phases**: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement. The approach emphasizes **customer-first prioritization**, **iterative delivery** of shippable increments, **clear ownership** with named Project Managers and Product Leads, **data-informed decision-making**, and a culture of **psychological safety** and continuous learning.

### Key Principles
- **Customer-first:** Prioritize customer value and usability in every decision
- **Iterative delivery:** Ship small, testable increments and gather feedback
- **Clear ownership:** Every project has named Project Manager (PM) and Product Lead (PdM)
- **Data-informed:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback, learning, and blameless retrospectives

### Core Roles & Personas
- **Project Managers:** Coordinate delivery, manage schedules, risks, and communications
- **Product Managers:** Define what to build, prioritize backlog, measure success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs, context, and approvals

### Communication Cadence
- **Daily:** 15-minute standups (focus: progress, blockers, dependencies)
- **Weekly:** PM-PdM sync for alignment and risk review
- **Twice-weekly:** Delivery team standups and demos
- **Monthly:** Stakeholder updates and announcements
- **Ad-hoc:** Escalations and incident communications

---

## Process Documentation

### Phase 1: Initiation
**[Project Initiation Guide](octoacme-project-initiation.md)**

Validate business need, align stakeholders, and authorize the project to move into planning.

**Deliverables:**
- Project One-pager (Problem, Goal, Success Metrics)
- Stakeholder list & communication plan
- High-level timeline and milestones
- Initial risk list and resource needs

**Decision Gate:** Move to planning when success metrics are clear, stakeholders align on priority, and team availability is confirmed.

---

### Phase 2: Planning
**[Project Planning](octoacme-project-planning.md)**

Turn an approved initiative into an actionable plan and backlog for delivery.

**Key Activities:**
- Project kickoff with stakeholders and team
- Create prioritized backlog with acceptance criteria
- Estimate scope and define Definition of Done
- Identify dependencies and integration points
- Create release plan and milestone map

**Key Artifact:** Prioritized backlog with clear acceptance criteria and estimates.

---

### Phase 3: Execution & Tracking
**[Execution & Tracking](octoacme-execution-and-tracking.md)**

Manage day-to-day execution, quality, and progress toward project milestones.

**Team Rhythm:**
- Daily standups (15 min)
- Weekly delivery syncs
- End-of-sprint demos and reviews

**Quality Standards:**
- Small PRs (≤ 400 lines)
- Automated tests and linting in CI
- Manual QA for feature acceptance
- Security scanning before merge

**Blocker Escalation:** Team triage → PM escalation → Sponsor escalation

---

### Phase 4: Release & Deployment
**[Release & Deployment Guide](octoacme-release-and-deployment.md)**

Standardize releases to production to reduce risk and improve observability.

**Pre-Release Requirements:**
- All acceptance criteria met
- Passing CI and security scans
- Release notes and rollback plan drafted
- Smoke tests prepared

**Release Types:**
- **Patch:** Critical hotfixes
- **Minor:** Incremental features and improvements
- **Major:** Significant functionality or breaking changes

**Post-Deploy:** Run verifications and announce to stakeholders.

---

### Phase 5: Retrospective & Continuous Improvement
**[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**

Capture learnings and convert them into actionable improvements.

**Timing:** After each sprint, release, or important milestone (also after incidents).

**Structure:**
- What went well
- What could be improved
- 2–3 prioritized action items with owners and due dates
- Follow-up on previous improvements

---

## Supporting Processes

### Risk Management & Communication
**[Risk Management & Communication](octoacme-risks-and-communication.md)**

Identify, manage, and communicate risks and dependencies throughout the project lifecycle.

**Key Artifact:** Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation Plan)

**Escalation Paths:**
- Team-level → PM → Product Lead → Sponsor
- Security incidents follow security incident runbook

**Stakeholder Communication:** Weekly status updates, incident notifications, and milestone announcements.

---

### Roles & Personas
**[Roles & Personas](octoacme-roles-and-personas.md)**

Detailed descriptions of key personas, responsibilities, goals, and typical communication patterns:
- Developers
- Product Managers
- Project Managers

---

## Quick Reference: Project Management Overview
**[Project Management Overview](octoacme-project-management-overview.md)**

A concise, shareable introduction to OctoAcme's approach, principles, core roles, key artifacts, and how to use this documentation.

---

## Using These Docs

### For New Team Members
1. Start with the **Project Management Overview** for a 5-minute introduction
2. Read the phase-specific docs as you enter each project stage
3. Reference **Roles & Personas** to understand team structure
4. Bookmark **Risk Management & Communication** for ongoing guidance

### For Project Managers
1. Use the **Project Initiation Guide** to kick off new projects
2. Follow the **Planning** checklist to create a project backlog
3. Use **Execution & Tracking** for daily standups and progress reporting
4. Reference **Risk Management & Communication** for escalations and status updates
5. Run **Retrospectives** at key milestones and sprints

### For Product Managers
1. Create a **Project One-pager** during initiation
2. Build and prioritize the backlog during planning
3. Define acceptance criteria and success metrics
4. Review metrics and feedback during execution
5. Participate in retrospectives to inform backlog refinement

### For Developers & QA
1. Review **Planning** to understand acceptance criteria
2. Follow the PR and code review guidelines in **Execution & Tracking**
3. Coordinate with PM/PdM on clarifications
4. Participate in daily standups and retrospectives
5. Use **Release & Deployment** when preparing for production

---

## Key Artifacts

Maintain these artifacts throughout your project:

| Artifact | Created In | Updated | Owner |
|----------|-----------|---------|-------|
| Project One-pager | Initiation | As needed | PdM / PM |
| Prioritized Backlog | Planning | Weekly (or continuous) | PdM |
| Risk Register | Planning | Weekly sync | PM |
| Project Board | Planning | Daily | Team |
| Release Notes | Release | Before deploy | PM / PdM |
| Retrospective Notes | Close | After each phase | PM |

---

## Document Structure

All process docs follow a consistent structure:
- **Purpose:** Why this guidance exists
- **Scope:** When and where it applies
- **Key Activities/Sections:** Step-by-step or detailed guidance
- **Checklist:** Concrete steps to ensure nothing is missed
- **Templates:** Reusable formats for common artifacts

---

## Questions or Feedback?

If you have questions about these processes or suggestions for improvement, please:
1. Open a [Process Doc Update](https://github.com/martin728/skills-scale-institutional-knowledge-using-copilot-spaces/issues/new?template=add-update-content-to-process-docs.yml) issue
2. Start a discussion with your PM or Product Lead
3. Bring feedback to the next retrospective

---

**Last Updated:** 2026-04-08  
**Maintained By:** OctoAcme Project Management Community