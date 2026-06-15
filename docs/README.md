# OctoAcme Project Management Docs

This README provides a comprehensive summary of OctoAcme's project management processes and links to the full process documents in this repository's `docs/` folder.

## Quick Overview

OctoAcme follows a structured, lifecycle-based project management approach designed around **customer value**, **iterative delivery**, and **clear ownership**. The framework spans five key phases: **Initiation** (validating business need and stakeholder alignment), **Planning** (creating actionable backlogs and timelines), **Execution** (day-to-day delivery with quality gates), **Release** (standardized deployment with risk mitigation), and **Retrospective** (capturing learnings and continuous improvement).

### Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles and Communication

OctoAcme defines three primary personas working in cross-functional teams:

- **Developers**: Design, build, and test features while maintaining documentation and quality standards
- **Product Managers**: Define what should be built through problem statements, success metrics, and roadmap prioritization
- **Project Managers**: Coordinate delivery, manage risks and dependencies, and ensure transparent stakeholder communication

**Communication Cadence**:
- Daily standups (15 minutes)
- Weekly delivery syncs between PM and Product Lead
- Twice-weekly team standups
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## Quality Assurance and Execution

Execution is managed through a project board with defined columns (Backlog, Ready, In Progress, In Review, QA, Done) and a disciplined PR workflow requiring:

- Small PRs (≤400 lines when possible)
- Issue links in descriptions
- At least one approval before merging

**Quality Standards**:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests before release
- Security scanning in CI
- Manual QA for feature acceptance

## Risk Management and Continuous Improvement

OctoAcme maintains a living Risk Register capturing:
- Description, Impact, Likelihood, Owner, Mitigation plan, and Status
- Reviewed and updated weekly during syncs

Each sprint, release, or milestone concludes with a retrospective (45–75 minutes) focusing on:
- What went well
- What could improve
- 2–3 prioritized action items with clear owners and due dates

---

## Links to Process Docs

- [OctoAcme Project Management Overview](./octoacme-project-management-overview.md) — Introduction to how OctoAcme runs projects
- [Project Initiation Guide](./octoacme-project-initiation.md) — Initial steps to validate and authorize work
- [Project Planning](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Managing day-to-day execution and progress
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases to production
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities

## Suggested Usage

- Use this README as the first entry point when onboarding new PMs and engineers
- Link to this document from your project charter or team wiki
- Keep links updated when documents are added, moved, or renamed
- Reference specific guides based on your current project phase (Initiation → Planning → Execution → Release → Retrospective)
