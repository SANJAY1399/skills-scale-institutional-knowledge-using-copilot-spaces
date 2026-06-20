# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents and templates. The README provides a short overview of our approach and direct links to each detailed document so new teammates can quickly find the single source of truth for how projects are run.

## Overview
OctoAcme follows a lightweight, iterative approach that centers on delivering customer value through small, testable increments. Projects move through five high-level stages: Initiation (problem statement, stakeholders, and success metrics), Planning (prioritized backlog, estimates, Definition of Done, and release plan), Execution & Tracking (project board, daily standups, PR/CI conventions, and QA), Release & Deployment (automated pipelines, smoke tests, rollback plans, and release notes), and Close & Retrospective (capture learnings, action items, and continuous improvement). Key artifacts include the Project One-pager, backlog items with acceptance criteria, a risk register, release notes, and retrospective action items.

## Roles & Communication
Roles are clearly defined so ownership and responsibilities are explicit: Product Managers own vision and prioritization; Project Managers coordinate schedules, risks, and stakeholder communication; Developers implement and test; QA validates acceptance criteria. Communication cadence includes daily standups for the delivery team, weekly PM↔PdM syncs, weekly delivery updates, and monthly stakeholder updates. Blocker escalation follows a three-level path (team triage → PM escalation → sponsor escalation for business-impacting issues).

## Quality & Release Practices
Work favors small PRs with CI gates, automated unit/integration/security tests, and manual QA when needed. The PR workflow requires an issue link and acceptance criteria, automated test/lint runs before review, and at least one approval before merging. Releases are classified (patch/minor/major) and require passing CI/security scans, drafted release notes, and a rollback plan. Post-deploy verifications and stakeholder announcements close the release cycle.

## Docs (this repository)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use these docs
- Keep the Project One-pager and key templates updated in the project repo to reduce onboarding time.
- Add process-specific examples to `.copilot/` if you want Copilot Spaces to use them as context.
- Use the backlog item template, DoD, and release checklist to standardize new initiatives.

## Acceptance Criteria (for this README)
- [x] Content aligns with existing process docs
- [x] Improves discoverability and onboarding
- [ ] (Optional) Reviewed by stakeholders if required
