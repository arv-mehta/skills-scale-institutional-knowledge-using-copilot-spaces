# OctoAcme Project Management Docs

This README is the landing page for OctoAcme's project management process documentation. It provides a short overview of how projects move from idea to production, who owns key responsibilities, the communication cadence the team uses to stay aligned, and the quality assurance practices that protect releases. Each linked document in this folder contains the detailed guidance and templates referenced below.

OctoAcme follows a stage-based lifecycle: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement. Initiation validates ideas with a Project One-pager that captures the problem, goal, and success metrics. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and an initial risk register. Execution uses a visible project board (Backlog → Ready → In Progress → In Review → QA → Done), small incremental PRs, CI checks, and a regular delivery rhythm to surface blockers and keep work flowing.

Roles and responsibilities are explicit to avoid single-person dependencies: Product Managers define outcomes and prioritize, Project Managers coordinate schedules and risks, Developers implement and test, QA validates acceptance criteria and runs manual/integration checks when needed, and Stakeholders provide inputs and approvals. Named ownership and a clear escalation path (team → PM → Product Lead → Sponsor) ensure decisions and issues are routed and resolved efficiently.

Quality is integrated throughout the workflow — developers write unit and integration tests, CI enforces automated tests and linting, security scans run in pipeline, and smoke/end-to-end checks protect critical flows before release. PR guidance (small diffs, linked issue, acceptance criteria) and a Definition of Done reduce review friction. Releases follow a checklist (pre-release checks, release notes, rollback plan) and include post-deploy verification and a blameless retrospective to capture improvements.

How to use this folder
- Use the links below to open the full process documents for templates, checklists, and examples.
- Update this README when new process docs are added or filenames change.
- For process changes, use the ".github/ISSUE_TEMPLATE/Add Content to Project Management Process Docs" template to propose edits.

Process documents (click to open)
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Release & Deployment](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)
