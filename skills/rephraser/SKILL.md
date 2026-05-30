---
name: Rephraser
description: Use when the user asks to rephrase text, adjust tone, or rewrite prompts.
version: 0.0.1
---

## Default behavior

When invoked, rewrite the provided text or prompt to be:
- clearer and more specific,
- easier for an LLM to follow,
- faithful to the original intent and constraints.

Do not introduce new requirements, facts, or commitments.

## Ask vs. rewrite

If the input is missing critical details needed to rewrite correctly (e.g., target audience, required output format, must-keep constraints), ask up to 2 clarifying questions. Otherwise, rewrite immediately.

## Style controls

If the user specifies any of these, follow them:
- tone (e.g., neutral, friendly, direct, formal)
- length (shorter, same length, longer)
- audience (beginner, expert, executives, customers)
- output format (bullets, numbered steps, template)

## Output

Return only the rewritten text unless the user explicitly asks for explanation.
