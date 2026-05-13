---
schema: agent-instruction/v1
status: draft
doc_type: deployment_instruction
generated_by: repo_context_preflight
generated_on: 2026-05-12
source_of_truth:
  - "README.md"
  - "package.json"
  - "pnpm-lock.yaml"
  - ".env.example"
---

# Deployment Instructions

## Evidence Found

- Evidence gap: deployment target not proven

## Deployment Target

Evidence gap: deployment target and release process are not proven.

## Rules

- Treat deployment config as higher-confidence evidence than generated prose.
- Do not add or change environment variables without documenting placeholders.
- Do not assume production infrastructure from local-only files.
