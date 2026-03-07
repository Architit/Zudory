# AGENT INSTRUCTIONS

Canonical policy mirror for multi-agent compatibility.
Last sync: 2026-03-03T11:03:39Z

## Core Rules
- Make safe, minimal, reversible changes.
- Prefer diagnostics -> patch -> verification -> report.
- Do not delete/archive data without explicit operator intent.
- If blocked, report reason and next action clearly.
- Keep repository-local conventions and existing contracts.

## Multi-Agent Compatibility
- This file is mirrored into `GEMINI.md` to avoid single-agent lock-in.
- If both files exist, they must stay semantically aligned.
