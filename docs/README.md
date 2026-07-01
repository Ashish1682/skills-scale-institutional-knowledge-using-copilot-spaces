# OctoAcme Project Management

This folder contains OctoAcme's process and playbook documents for planning, executing, and improving cross-functional projects. The materials are intended to accelerate onboarding, provide a single source of truth for project rhythm and artifacts, and make it easier to follow consistent delivery and quality practices.

## Overview

OctoAcme follows an iterative, outcome-focused project management approach. Work starts with a lightweight initiation (project one-pager, stakeholder alignment, and success metrics) that gates planning. Planning turns approved initiatives into a prioritized backlog, estimates, and a release plan. Execution emphasizes small, testable increments, CI-first PRs, and a clear Definition of Done to ensure work is releasable.

Teams coordinate using a regular cadence—daily standups for progress and blockers, weekly delivery syncs for status and risks, and demos at the end of sprints or milestones. A project board (Backlog → Ready → In Progress → In Review → QA → Done) manages ticket flow. Risk and dependencies are tracked in a Risk Register and reviewed weekly, with a clear escalation path (team → PM → Product Lead → Sponsor).

Quality and release practices include unit and integration tests, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed. Releases require passing CI/security checks, a deployment checklist, rollback plans, and post-deploy verifications. Retrospectives capture action items that are added to the backlog and measured for impact.

## Summary of processes
- Initiation: Capture the problem, define measurable success metrics, identify stakeholders, and decide go/no-go using a short project one-pager.
- Planning: Turn approved initiatives into a prioritized backlog, estimate scope, document the Definition of Done (DoD), and create a release/milestone plan while capturing dependencies and risks.
- Execution & Tracking: Run regular team cadence (daily standups, weekly delivery syncs), use a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done), follow PR and CI-first practices, and track progress with velocity/burndown dashboards.
- Release & Deployment: Validate acceptance criteria, pass CI/security scans, follow a deployment checklist and smoke tests, and have rollback and incident playbooks ready.
- Risk & Communication: Maintain a risk register with owners and mitigation plans, provide stakeholder updates, and use a clear escalation path (team → PM → Product Lead → Sponsor).
- Retrospectives & Improvement: Hold regular retrospectives, create prioritized action items, and feed improvements back into the backlog for measurement.
- Roles & Personas: Clear role definitions (Product Manager, Project Manager, Developers, QA, Stakeholders) ensure ownership and efficient cross-team coordination.

## Process documents
- [Project Management Overview](./octoacme-project-management-overview.md) — Concise intro to approach, roles, and artifacts.
- [Project Initiation Guide](./octoacme-project-initiation.md) — One-pager, stakeholder alignment, decision gate.
- [Project Planning](./octoacme-project-planning.md) — Backlog, estimation, DoD, release plan.
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Team rhythm, workflows, QA, reporting.
- [Release & Deployment](./octoacme-release-and-deployment.md) — Pre-release, deployment checklist, rollback.
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Risk register and stakeholder comms.
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Retrospective structure and tracking.
- [Roles & Personas](./octoacme-roles-and-personas.md) — Role summaries and responsibilities.

## How to use this README
- Use this README as the single entry point to find and link into the process docs.
- Keep the one-pager and project README in the project repo updated as the single source of truth for stakeholders.
- If you want Copilot Spaces to use process-specific docs as context, add them into `.copilot/` per the repository guidance.

## Acceptance checklist
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
