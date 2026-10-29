---
name: diagram-review
description: Review architecture diagrams for evidence, notation, readability, traceability, and honest implementation status.
---

# Diagram review

## Inputs

Inspect the editable source under `docs/architecture/diagrams/`, the rendered artifact if present, and linked requirements, source files, schemas, APIs, and ADRs.

## Checks

- Confirm title, scope, abstraction level, legend, labels, direction, spacing, and readable text.
- Confirm each important element and relationship has evidence or is explicitly marked proposed or unknown.
- Check that notation matches purpose and editable source is retained.
- Validate syntax and render with available tools; inspect output for clipping and overlap.
- Report unavailable renderers or unverified relationships rather than claiming validation.

Never turn a proposed design into a claim about the implemented system.
