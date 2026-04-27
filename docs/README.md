# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, lifecycle-based approach to project management that spans five phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that defines the problem statement, SMART objectives, success metrics, and stakeholder alignment before any development work begins. A formal decision gate ensures that teams only proceed into planning once success criteria are clear, stakeholders agree on priority, and team availability is confirmed. This disciplined initiation process reduces wasted effort and ensures every project has a clear business rationale before resources are committed.

OctoAcme defines clear **roles and responsibilities** across four core personas: Project Managers (who coordinate schedules, risks, and communications), Product Managers (who own the product vision and backlog prioritization), Developers (who implement and test features), and QA/Stakeholders (who validate quality and provide approvals). Each project has a named PM and Product Lead to ensure clear ownership. Communication cadences are structured and predictable — daily standups, weekly PM/PdM syncs, monthly stakeholder updates, and sprint demos — ensuring consistent alignment across all levels of the organization without over-meeting.

Execution is managed through a GitHub Projects board with well-defined columns (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined Pull Request workflow that emphasizes small PRs (≤400 lines), linked issues, automated CI checks, and at least one peer approval before merging. **Quality assurance** is embedded throughout the process with unit tests, integration tests, end-to-end smoke tests, security scanning in CI, and manual QA for feature acceptance. Risks are tracked in a living Risk Register with owners and mitigation plans, and a three-level escalation path (team → PM/Product Lead → Sponsor) ensures blockers are surfaced and resolved quickly.

After each sprint, release, or significant milestone, OctoAcme runs **structured retrospectives** to capture what went well, what can be improved, and concrete action items with clear owners and due dates. Improvement actions are fed back into the project backlog to ensure follow-through, and their impact is measured over time to build a genuine culture of continuous improvement. Release management is equally disciplined, with standardized deployment checklists, pre-release requirements (passing CI, security scans, drafted release notes, and rollback plans), and a tiered release taxonomy (Patch, Minor, Major) to calibrate the level of rigor required for each type of change.

## Document Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management methodology and lifecycle |
| [Project Initiation](octoacme-project-initiation.md) | One-pager process, decision gates, and criteria for kicking off a new project |
| [Project Planning](octoacme-project-planning.md) | Sprint planning, backlog grooming, estimation, and roadmap management |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | GitHub Projects board workflow, PR discipline, CI checks, and QA practices |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk Register, escalation paths, and communication cadences |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release taxonomy, deployment checklists, and rollback procedures |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective formats, action item tracking, and improvement measurement |
| [Roles and Personas](octoacme-roles-and-personas.md) | Core team roles, responsibilities, and stakeholder definitions |
