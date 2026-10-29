# Codex project instructions

- This is a foundation for one graduation project. Do not implement application features or select an unapproved stack.
- Locate requirements in `docs/requirements/`, architecture in `docs/architecture/`, decisions in `docs/decisions/`, and plans in `docs/planning/`.
- Mark unknown information `TBD`; never invent facts, citations, test results, or project decisions.
- Keep documents traceable through requirement IDs, issues, ADRs, tests, and evidence.
- Apply evidence-first diagramming: inspect requirements, source, schemas, APIs, and ADRs before diagramming; label content as VERIFIED IMPLEMENTATION, APPROVED DESIGN, PROPOSED DESIGN, or UNKNOWN.
- Select notation by purpose: Structurizr DSL for reusable C4 models, Mermaid for simple GitHub documentation, PlantUML for complex UML, and Draw.io/Excalidraw only when editable presentation output is needed.
- Preserve editable diagram sources under `docs/architecture/diagrams/`, prefer SVG exports, and never present proposed architecture as implemented.
- Validate syntax, render when tools are available, inspect labels/layout, and document unverified relationships and unavailable checks.
- Run relevant checks and report skipped checks honestly. Never commit secrets or real environment files.
- Use issue-driven branches and reviewed pull requests. Do not push, merge, reset, delete user work, or perform destructive operations automatically.
