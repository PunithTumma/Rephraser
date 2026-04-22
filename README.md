# Rephraser (Claude Code Plugin)

This repository is a scaffold for a Claude Code plugin that will rephrase the current prompt via a slash command (planned: `/rephrase`).

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

- Create and manage a virtualenv with `uv` (to be used once we add implementation).
- No rephrase logic is implemented yet; this is just the initial scaffold.
