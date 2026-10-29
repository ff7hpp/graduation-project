---
name: architecture-and-diagrams
description: Document and review an approved graduation-project architecture using concise arc42-informed sections and Mermaid sources.
---

# Architecture and diagrams

## Inputs

Use `docs/requirements/`, source code, schemas, APIs, and ADRs. Create an evidence inventory before any diagram and cite the supporting file or document for each important element and relationship.

## Workflow

1. Classify every fact as VERIFIED IMPLEMENTATION, APPROVED DESIGN, PROPOSED DESIGN, or UNKNOWN.
2. Select notation by purpose: Structurizr DSL for reusable C4, Mermaid for simple GitHub docs, PlantUML for complex UML, and Draw.io/Excalidraw for editable presentation diagrams.
3. Define scope, title, abstraction level, legend, relationship direction, and traceability.
4. Preserve editable source in `docs/architecture/diagrams/`; prefer SVG exports and never provide only a raster image when source can be preserved.
5. Validate syntax, render when tools are available, inspect the rendered output, and correct clipping, overlap, unreadable labels, crossings, or unsupported relationships.

## Review criteria

The design is traceable, internally consistent, visually readable, appropriately abstracted, and explicit about unknowns. Do not invent services, endpoints, databases, authentication flows, classes, technologies, or integrations.
