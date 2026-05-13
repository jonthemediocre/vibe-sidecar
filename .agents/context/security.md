---
schema: agent-context-doc/v1
status: draft
doc_type: security
generated_by: repo_context_preflight
generated_on: 2026-05-12
source_of_truth:
  - "README.md"
  - "package.json"
  - "pnpm-lock.yaml"
  - ".env.example"
---

# Security Context

## Evidence Found

- `README.md`
- `package.json`
- `pnpm-lock.yaml`
- `.env.example`

## Hard Rules

- Never commit secrets, tokens, credentials, cookies, or environment-specific private values.
- Never log tokens, passwords, session cookies, or private user data.
- Validate untrusted input at boundaries.
- Treat client-provided identity, role, tenant, or ownership claims as untrusted.

## Repo-Specific Security Model

Evidence gap: authentication, authorization, tenant, data-retention, and secret-management models are not proven.

## Environment Variables

Evidence gap: required and optional environment variables require confirmation from `.env.example`, config files, deployment config, or maintainer direction.
