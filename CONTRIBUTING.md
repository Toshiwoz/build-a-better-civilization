# Contributing

Thank you for helping build reviewable knowledge — not just a collection of opinions.

## Workflow overview

- **Issues** — for problems, questions, and proposals not yet tied to a specific document. Use them to start a discussion.
- **Pull Requests** — for concrete document changes. Link related Issues in the PR description.
- **Branches** — for experimental tracks; open a PR when ready for review.

When creating a PR, use "Closes #N" or "Related to #N" to link related Issues.

## Creating a proposal

1. Choose the domain and the next available identifier.
2. Copy [the template](methodology/proposal-template.md) to `docs/<domain>/proposals/`.
3. Name the file `ID-short-title-kebab-case.md`; content may be written in Spanish or English.
4. Explain the problem, assumptions, benefits, risks, evidence, and uncertainties.
5. Add the proposal to [docs/education/INDEX.md](docs/education/INDEX.md) and to the root [INDEX.md](INDEX.md).
6. Open a PR and link any related Issues.

## Naming conventions

| Document type | Pattern | Example |
|---------------|---------|---------|
| Concept doc | `EDU-NNN-title-kebab-case.md` | `EDU-001-purpose-of-education.md` |
| Architecture doc | `EDU-ARCH-NNN-title-kebab-case.md` | `EDU-ARCH-001-system-overview.md` |
| Proposal | `EDU-NNN-title-kebab-case.md` | `EDU-005-history-as-human-experience.md` |
| Guide | `guide-title-kebab-case.md` | `guide-assessment-rubrics.md` |
| Reference | `ref-title-kebab-case.md` | `ref-bibliography.md` |

## Document metadata

New canonical docs should include a metadata header:

```
**Type:** Concept / Architecture / Proposal / Guide / Reference
**Status:** Draft / In discussion / Accepted (provisional) / Replaced / Deprecated
**Scope:** Global / Education / Program / Module
**Owner:** person or team
**Last updated:** YYYY-MM-DD
```

## Evidence standard

- **Verified:** supported by a primary source or reliable review, cited well enough to locate.
- **Inferred:** reasonable conclusion from evidence or explicit premises, but not directly proved.
- **Speculative:** useful hypothesis or possibility that does not yet have sufficient support.

Critiques are part of the record. They are not removed for disagreeing: they are answered, incorporated, or documented as not changing the proposal.

## Review expectations for concept docs

Concept docs (`EDU-NNN`) require at least 1 review before changing status from Draft to Accepted. See [GOVERNANCE.md](GOVERNANCE.md) for full approval rules.

## Changes

Use clear commit messages. A contribution should be independently reviewable and must not present an inference as a verified fact.

## For more detail

See [methodology/contribution-methodology.md](methodology/contribution-methodology.md) for the full lifecycle, quality rules, and status definitions.
