---
schema: agent-context-doc/v1
status: draft
doc_type: testing
generated_by: repo_context_preflight
generated_on: 2026-05-12
source_of_truth:
  - "README.md"
  - "package.json"
  - "pnpm-lock.yaml"
  - ".env.example"
---

# Testing Context

## Evidence Found

- `README.md`
- `package.json`
- `pnpm-lock.yaml`
- `.env.example`

## Test Locations

- `package.json`

## Validation Commands

- Unit tests: Evidence gap.
- Integration tests: Evidence gap.
- Lint: Evidence gap.
- Typecheck/build: Evidence gap.

## Rules

- Test behavior, not implementation details.
- Add regression tests for fixed bugs when practical.
- Do not weaken or delete failing tests unless the accepted spec changed.
