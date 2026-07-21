# Governance

## Purpose

This document defines lightweight decision and approval rules for the Build a Better Civilization project. The goal is clarity and accountability without bureaucracy.

## Principles

- Decisions are made transparently and documented.
- Any contributor can propose a change; approval depends on scope and impact.
- No document is deleted — replaced documents are marked and linked to their successor.

## Decision types and approval rules

| Type | Requires | Process |
|------|----------|---------|
| New draft proposal | None | Open a PR, follow naming convention |
| Status change to "In discussion" | Author judgment | Update status in PR |
| Status change to "Accepted (provisional)" | At least 1 review + no unresolved objections | PR review |
| Changes to `EDU-001` or other foundational concepts | Discussion + 2 reviews | PR with linked Issue |
| Changes to `GOVERNANCE.md`, `CONTRIBUTING.md`, or `methodology/contribution-methodology.md` | 2 reviews | PR with linked Issue |
| Structural changes (moving folders, renaming) | Discussion | PR with linked Issue describing rationale |

## Review expectations

- A review is a written comment on a PR that addresses content, not just style.
- Reviews should reference relevant proposals or evidence where applicable.
- A PR with no objections after 7 days may be merged by the author if it has at least 1 explicit approval.

## Who can approve

Currently, any active contributor can approve PRs. As the project grows, domain maintainers may be designated.

## Conflict resolution

If a PR receives conflicting reviews, the author opens a linked Issue for discussion. The PR is not merged until the Issue is resolved or consensus is documented.

## Amendments

Changes to this document follow the same rules as changes to `CONTRIBUTING.md` (see table above).
