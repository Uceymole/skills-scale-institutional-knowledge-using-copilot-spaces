## Program process documents

- Stored in `docs/`

### Purpose of this Copilot Space

- Centralize scattered project management knowledge in Copilot Spaces
- Convert tacit team insights into searchable, versioned artifacts
- Give all team members equal access to processes, decisions, and rationale
- Connect a repository as a structured knowledge source
- Extract, refine, and standardize workflows collaboratively
- Feed validated improvements back into living documentation
- Accelerate onboarding and reduce single-person dependency risk
- Enable consistent, repeatable project execution

## Issue templates for program process documents

- Stored in `.github/ISSUE_TEMPLATE/`

---

Project summary

OctoAcme runs projects with an iterative, outcome-focused approach centered on clear ownership and small, testable deliveries. Projects follow a lightweight lifecycle: Initiation (one‑pager, stakeholder alignment, success metrics), Planning (kickoff, prioritized backlog, estimates, Definition of Done), Execution (work on the project board, PRs, CI, reviews), Release (pre-release checks, deployment checklist), and Close/Retrospective (capture learnings and action items). The program emphasizes customer-first decisions, data-informed trade-offs, and psychological safety so teams can learn and iterate quickly.

Operational workflows are documented and prescriptive. Work is tracked on a project board with columns such as Backlog → Ready → In Progress → In Review → QA → Done; PRs are kept small where possible, must include an issue link and acceptance criteria, and run through automated tests and linting before review. Planning uses a standard backlog item template and a release/milestone map; risk and dependency management are captured in a simple risk register. Release procedures include pre-release checks (passing CI/security scans, release notes, rollback plans) and a deployment checklist with post-deploy verification steps.

Roles and responsibilities are defined to reduce ambiguity: Product Managers own vision, prioritization, and success metrics; Project Managers coordinate schedules, risks, and communications; Developers implement and test features; QA validates acceptance criteria; Stakeholders provide input and approvals. The roles document includes responsibilities, typical communication patterns, and expected outcomes so each role knows handoffs, escalation points, and what artifacts they must maintain (e.g., one‑pager, acceptance criteria, risk register).

Communication cadence and quality practices ensure transparency and reliability. Cadences include daily standups (focus on progress/blockers), weekly delivery syncs, demos at the end of sprints/milestones, and monthly stakeholder updates; templates exist for weekly status and incident communications. Quality assurance is layered: unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA where appropriate. Checklists (execution, deployment, release notes) plus an escalation path (team → PM → Product Lead → Sponsor) support consistent, low-risk delivery and fast, structured incident response.

Docs in this folder
- [octoacme-project-management-overview.md](docs/octoacme-project-management-overview.md)
- [octoacme-project-initiation.md](docs/octoacme-project-initiation.md)
- [octoacme-project-planning.md](docs/octoacme-project-planning.md)
- [octoacme-execution-and-tracking.md](docs/octoacme-execution-and-tracking.md)
- [octoacme-release-and-deployment.md](docs/octoacme-release-and-deployment.md)
- [octoacme-retrospective-and-continuous-improvement.md](docs/octoacme-retrospective-and-continuous-improvement.md)
- [octoacme-risks-and-communication.md](docs/octoacme-risks-and-communication.md)
- [octoacme-roles-and-personas.md](docs/octoacme-roles-and-personas.md)
