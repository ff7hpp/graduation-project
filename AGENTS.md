# Repository-wide Codex instructions

- This repository contains two independent projects: `عبد الرحمن/` and `آلاء/`. Never mix their requirements, code, architecture, tests, diagrams, or reports.
- Before work, identify the active project. Read this file and that project's `AGENTS.md`; if no project is identified, ask before modifying project files.
- When working on one project, save all project-specific output inside its folder and do not modify the other project.
- Shared skills, GitHub configuration, and repository-wide instructions remain at the root. Do not duplicate skills inside project folders.
- Locate requirements in `docs/requirements/`, architecture in `docs/architecture/`, decisions in `docs/decisions/`, and plans in `docs/planning/`.
- Mark unknown information `TBD`; never invent facts, citations, test results, or project decisions.
- Keep documents traceable through requirement IDs, issues, ADRs, tests, and evidence.
- Apply evidence-first diagramming: inspect requirements, source, schemas, APIs, and ADRs before diagramming; label content as VERIFIED IMPLEMENTATION, APPROVED DESIGN, PROPOSED DESIGN, or UNKNOWN.
- Select notation by purpose: Structurizr DSL for reusable C4 models, Mermaid for simple GitHub documentation, PlantUML for complex UML, and Draw.io/Excalidraw only when editable presentation output is needed.
- Preserve editable diagram sources under `docs/architecture/diagrams/`, prefer SVG exports, and never present proposed architecture as implemented.
- Validate syntax, render when tools are available, inspect labels/layout, and document unverified relationships and unavailable checks.
- Run relevant checks and report skipped checks honestly. Never commit secrets or real environment files.
- Use issue-driven branches such as `abdulrahman/feature-name`, `alaa/feature-name`, or `shared/configuration-change`; use reviewed pull requests and never push directly to `main` or merge automatically.
- Use UTF-8 and quote Unicode paths in shell commands. Use descriptive diagram names such as `ARCH-001-system-context.mmd` and preserve editable sources.
