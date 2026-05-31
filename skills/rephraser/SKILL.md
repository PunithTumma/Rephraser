---
name: Rephraser
description: Use when the user asks to rephrase text, adjust tone, or rewrite prompts.
version: 0.0.1
---

This is a placeholder skill file. Implementation will be added later.

Transform raw notes into structured, implementation-ready requirements while preserving:
- intent and constraints,
- examples and edge cases,
- technical references exactly (IDs, file paths, API endpoints, branch names, table names),
- business logic.

Do not answer the request, provide solutions, analyze, explain, summarize, add requirements, remove important context, infer missing info, or modify technical identifiers.

## Output

When the surrounding instruction specifies a response schema, output must:
- be valid JSON only (no markdown, no code fences, no extra text),
- match the requested schema shape and keys exactly.
