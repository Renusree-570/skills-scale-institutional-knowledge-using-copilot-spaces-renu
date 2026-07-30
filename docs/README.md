# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. This README provides a single place to discover process artifacts, understand core workflows, and find owners and next actions.

## Overview

OctoAcme runs projects with an iterative, outcome-driven process that begins with a lightweight initiation (Project One-pager, stakeholder list, and success metrics) and progresses through planning, execution, release, and retrospective stages. During planning, approved initiatives are broken into shippable backlog items with clear acceptance criteria and estimates. Teams manage work on a visible project board (Backlog → Ready → In Progress → In Review → QA → Done) to make progress and dependencies transparent.

Key workflows emphasize small, reviewable increments and consistent quality gates. Pull requests should be scoped to be easy to review, include linked issues and acceptance criteria, and pass automated CI checks (tests, linting, and security scans) before requesting approval. Releases are classified (patch, minor, major) and follow a checklist-based process that includes pre-release verification, smoke tests in staging, rollback planning, and post-deploy checks.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize; Project Managers coordinate delivery, risks, and communications; Developers implement features, tests, and documentation; QA validates acceptance criteria and test plans; Stakeholders provide input and approvals. Each key artifact (one-pager, roadmap, Definition of Done, release notes, risk register) has a named owner to ensure accountability and traceability.

Communication is structured and frequent: daily standups for tactical progress and blockers, weekly delivery syncs for progress and risk review, PM–PdM weekly alignment, regular demos at the end of sprints or milestones, and monthly stakeholder updates. There are documented escalation paths (team → PM → Product Lead → Sponsor) and templates for status and incident communications to ensure consistent and timely messaging.

Quality assurance is embedded across the lifecycle: developers write unit and integration tests, CI enforces automated tests and security scanning, and end-to-end smoke tests are run before releases. Manual QA complements automation where needed, and retrospectives convert learnings into tracked action items. These practices shorten feedback loops, reduce risk, and help make releases predictable and observable.

## Documents in this folder

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Suggested next steps

- Link `docs/README.md` from the repository root README or an index page.
- Optionally add one-line descriptions or a table of contents for each document to improve discoverability.
