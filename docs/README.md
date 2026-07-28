# OctoAcme Project Management Docs

Centralizing and democratizing project management knowledge
for the OctoAcme organization

## Purpose
This folder collects OctoAcme's project management process documents in one place so teammates can find, use, and improve them. The docs describe lifecycle stages, roles and responsibilities, communication cadences, quality gates, and templates you can reuse for new projects.

## Quick summary
OctoAcme runs projects iteratively with clear ownership and measurable outcomes. Projects progress through initiation, planning, execution, release, and retrospective stages. Each stage has lightweight artifacts (one-pager, backlog, release notes, risk register) and defined handoffs so teams can move quickly while keeping transparency with stakeholders.

Our approach emphasizes small, testable increments, automated quality checks in CI, and frequent communication. Project teams use a project board to manage work states and a pull request workflow that requires acceptance criteria, CI passes, and at least one reviewer before merge. Risk and dependency management is captured in a simple risk register reviewed during weekly syncs.

Roles and responsibilities are defined so each project has a named Project Manager (PM) and Product Lead (PdM). Developers, QA, and stakeholders each have clear expectations to reduce ambiguity and escalation friction. The docs in this folder include role descriptions and examples to help teams assign responsibilities and escalate blockers efficiently.

Finally, these docs are living artifacts: add improvements, examples, or templates via the issue template at `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`. Use Copilot Spaces (if available) to summarize, attach issues, and create PRs that update these docs so process changes remain discoverable and versioned.

## Docs in this folder
- [Project Management Overview](./octoacme-project-management-overview.md) — high-level principles, lifecycle, cadence, and key artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) — one-pager template, initiation checklist, decision gate
- [Project Planning](./octoacme-project-planning.md) — backlog template, planning activities, risk register guidance
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — team rhythm, PR workflow, quality gates, reporting
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — risk register, stakeholder comms, escalation paths
- [Release & Deployment](./octoacme-release-and-deployment.md) — release types, deployment checklist, rollback playbook
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — retrospective structure and action tracking
- [Roles & Personas](./octoacme-roles-and-personas.md) — role summaries and responsibilities

## How to contribute
1. Use the issue template: `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose additions or updates.
2. Describe the change, rationale, and acceptance criteria in the template form.
3. Attach the issue to Copilot Spaces if you use it, or create a PR that updates the appropriate file(s) in this folder.
4. Keep changes small and focused; reference related artifacts and add examples where helpful.

---

If you want, I can open a pull request adding this README to the docs/ folder and link it to an issue using the provided template. Would you like me to create the PR now?