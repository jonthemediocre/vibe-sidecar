---
schema: agent-instruction/v1
status: draft
doc_type: api_instruction
generated_by: repo_context_preflight
generated_on: 2026-05-12
source_of_truth:
  - "README.md"
  - "package.json"
  - "pnpm-lock.yaml"
  - ".env.example"
---

# API Instructions

## Evidence Found

- Evidence gap: API surface not proven

## Contract

Evidence gap: API contract source not proven. Check OpenAPI files, route definitions, tests, and existing handlers before editing.

## Rules

- Preserve backward compatibility unless an accepted spec says otherwise.
- Validate inputs at the boundary.
- Do not expose internal stack traces to clients.
