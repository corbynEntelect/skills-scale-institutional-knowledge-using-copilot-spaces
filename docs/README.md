# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documents. The files below index the team's lifecycle, roles, workflows, and checklists used across initiation, planning, execution, release, and continuous improvement.

## Overview

OctoAcme organizes work around a lightweight, repeatable project lifecycle. Projects begin with a one‑pager that clarifies the problem, measurable success metrics, stakeholders, and a high‑level timeline. A decision gate ensures success metrics, stakeholder alignment, and team availability before work moves into planning; once approved, planning produces a prioritized backlog with acceptance criteria and a Definition of Done (DoD).

Execution is driven via a visible project board (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined pull‑request workflow: keep PRs small, include linked issues and acceptance criteria, run CI (tests, linting, security scans) before requesting review, and require approvals per team policy. Releases follow a checklisted process (staging smoke tests, production deploys via automated pipelines when possible, rollback plans) and include release notes and post‑deploy verification.

Roles and responsibilities are defined so each function knows ownership: Product Managers define outcomes and success metrics, Project Managers coordinate schedules, risks and communications, Developers implement and test, and QA validates acceptance criteria. Communication cadence includes daily standups for blockers, weekly delivery syncs, sprint demos/reviews, PM+PdM alignment meetings, and monthly stakeholder updates. Quality is enforced through unit/integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, and manual QA when needed. Retrospectives capture action items and feed improvements back into the backlog so the team iteratively improves.

## Documents in this folder
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Suggested next steps
- Add this README to docs/ as docs/README.md
- Link this README from the repository root README (optional)
- Keep the index updated when new process docs are added or changed
