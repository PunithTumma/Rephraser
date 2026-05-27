# Rephraser (Claude Code Plugin)

This repository is a Claude Code plugin that rephrases your last prompt via `/rephrase`.

## Usage

- Run `/rephrase` to rewrite your most recent prompt (clearer, same intent).
- Optional args: `/rephrase [tone] [length] [audience]` (example: `/rephrase direct shorter senior-engineer`).

## Layout

```
.
├── .claude-plugin/
│   └── plugin.json          # Plugin manifest (required)
├── commands/
│   └── rephrase.md          # Slash command placeholder
├── skills/
│   └── rephraser/
│       └── SKILL.md         # Skill placeholder
├── scripts/                 # Future helper scripts invoked by commands
├── hooks/
│   └── hooks.json           # Hook config (empty for now)
└── pyproject.toml           # uv / Python project metadata
```

## Development (uv)

- No Python code is required for `/rephrase` right now; it’s implemented as a command prompt template.
- `scripts/` and `pyproject.toml` are reserved for future automation (optional).
