---
schema: agent-instruction/v1
status: draft
doc_type: database_instruction
generated_by: repo_context_preflight
generated_on: 2026-05-12
source_of_truth:
  - "README.md"
  - "package.json"
  - "pnpm-lock.yaml"
  - ".env.example"
---

# Database Instructions

## Evidence Found

- Evidence gap: database surface not proven

## Database Model

Evidence gap: database engine, schema ownership, and migration tool are not proven.

## Rules

- Use migrations for schema changes when the repo has a migration system.
- Use parameterized queries or safe ORM methods.
- Do not infer production database from local development artifacts alone.
