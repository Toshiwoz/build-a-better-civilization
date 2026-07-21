# EDU-ARCH-001 — System Overview

**Type:** Architecture  
**Status:** Draft  
**Scope:** Education — System  
**Owner:** Community  
**Last updated:** 2026-07-21

## Purpose

This document describes the overall structure of the education knowledge base: how its layers relate, where different types of content live, and how to navigate the system as it grows.

## Information layers

The education domain uses a three-layer hierarchy:

```
Layer 1 — Orientation
  docs/education/README.md         (start here)
  docs/education/INDEX.md          (full map)

Layer 2 — Concepts (stable, concise definitions)
  docs/education/concepts/         (EDU-001, EDU-002, EDU-003 …)
  docs/education/architecture/     (EDU-ARCH-001, EDU-ARCH-002 …)

Layer 3 — Detail / implementation
  docs/education/proposals/        (full proposals with evidence and discussion)
  docs/education/programs/         (curriculum and program design)
  docs/education/teaching/         (pedagogy, methodology, teacher requirements)
  docs/education/tools/            (approved tools, tooling principles)
  docs/education/operations/       (implementation, rollout, metrics)
  docs/education/references/       (glossary, bibliography, external links)
```

## Key relationships

- Concept docs (`EDU-NNN`) define principles; proposals validate and elaborate them.
- Architecture docs (`EDU-ARCH-NNN`) describe structure; they do not define educational content.
- Program docs use concepts and architecture as stable references.
- All concept docs link to related proposals and vice versa.

## Lifecycle

A document progresses through: `Draft → In discussion → Accepted (provisional) → Replaced / Deprecated`.

No document is deleted. Replaced documents are marked and linked to their successor.

## Maintenance

- This document should be updated whenever a new layer or major folder is added.
- Changes to this document require a PR with at least one review.

---

*Initial draft — structure will evolve as the domain grows.*
