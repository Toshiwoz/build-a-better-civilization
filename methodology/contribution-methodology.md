# Contribution Methodology

## Purpose

Convert ideas and conversations into clear, linkable, criticizable, and updatable units of knowledge.

For the quick contribution workflow, see [CONTRIBUTING.md](../CONTRIBUTING.md). This document covers the full lifecycle and quality standard in more detail.

## Repository structure and navigation

The knowledge base uses a three-layer hierarchy:

1. **Orientation layer** — `README.md`, `INDEX.md`, `CONTRIBUTING.md`, `GOVERNANCE.md`
2. **Concept layer** — `docs/education/concepts/` (concise canonical definitions, e.g. `EDU-001`)
3. **Detail / implementation layer** — `docs/education/proposals/`, `programs/`, `teaching/`, `tools/`, `operations/`, `references/`

Each major folder contains a `README.md` describing its scope and first documents to read.

## Issues vs Pull Requests

| Situation | Use |
|-----------|-----|
| A problem, question, or idea not yet attached to a specific document | **Issue** |
| A concrete change to an existing document | **Pull Request** |
| A new document proposal | **Pull Request** (link any related Issues) |
| Structural discussion (moving folders, renaming) | **Issue** first, then **PR** |

Always link related Issues and PRs in descriptions using `Closes #N` or `Related to #N`.

## Proposal lifecycle

A proposal may be in one of these states:

- **Draft:** structured idea pending review.
- **In discussion:** receiving critiques, alternatives, or additional evidence.
- **Accepted (provisional):** guides current work, but remains open to revision.
- **Replaced:** another proposal improves or supersedes it; the historical link is preserved.
- **Deprecated:** no longer relevant; marked with a note explaining why.
- **Rejected:** not adopted, with documented reasons.

## Naming conventions

| Document type | Pattern | Example |
|---------------|---------|---------|
| Concept doc | `EDU-NNN-title-kebab-case.md` | `EDU-001-purpose-of-education.md` |
| Architecture doc | `EDU-ARCH-NNN-title-kebab-case.md` | `EDU-ARCH-001-system-overview.md` |
| Proposal | `EDU-NNN-title-kebab-case.md` | `EDU-005-history-as-human-experience.md` |
| Guide | `guide-title-kebab-case.md` | `guide-assessment-rubrics.md` |
| Reference | `ref-title-kebab-case.md` | `ref-bibliography.md` |

Identifiers (`EDU-001`, `EDU-002`, …) are never reused.

## Quality rules

1. Separate description, evidence, inferences, and opinions.
2. Declare the assumptions that support a proposal.
3. Record risks, critiques, and open questions.
4. Link dependencies between proposals using their identifier.
5. Update status when the evaluation changes, without erasing relevant history.
6. Do not present an inference as a verified fact.

## Review expectations for concept docs

Concept docs (`EDU-NNN`) must have at least 1 written review before moving to "Accepted (provisional)". See [GOVERNANCE.md](../GOVERNANCE.md) for the full approval matrix.

## Folder placement guide

| Content type | Destination |
|-------------|-------------|
| New concept (brief, stable) | `docs/education/concepts/` |
| New architecture or structural doc | `docs/education/architecture/` |
| Full proposal (evidence + discussion) | `docs/education/proposals/` |
| Curriculum or program design | `docs/education/programs/` |
| Pedagogy, teacher requirements | `docs/education/teaching/` |
| Tools and tooling | `docs/education/tools/` |
| Implementation and metrics | `docs/education/operations/` |
| Glossary, bibliography, links | `docs/education/references/` |
| Cross-domain evidence | `evidence/` |
| Project-wide decisions | `decisions/` |
