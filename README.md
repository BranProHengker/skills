# Antigravity Skills

Agent skills and behavioral guidelines for coding assistants such as Antigravity, Claude Code, Cursor, and Codex.

Maintained by Bran ([heybran.my.id](https://heybran.my.id) / [@BranProHengker](https://github.com/BranProHengker)).

## Available skills

| Skill | Purpose | Install |
| :--- | :--- | :--- |
| `no-slop-anymore` | Audit checklist to strip stock AI design patterns, pseudo-code labels, and marketing filler from frontends. | `npx skills add BranProHengker/skills --skill no-slop-anymore -g` |
| `antigravity-guidelines` | Operational rules enforcing zero silent assumptions, minimal code changes, pre-flight verification, and project context priority. | `npx skills add BranProHengker/skills --skill antigravity-guidelines -g` |

## Installation

### Install all skills
Add every skill in this repository globally:

```bash
npx skills add BranProHengker/skills --all -g
```

### Install a single skill
```bash
npx skills add BranProHengker/skills --skill no-slop-anymore -g
npx skills add BranProHengker/skills --skill antigravity-guidelines -g
```

## Structure

```text
skills/
├── skills/
│   ├── no-slop-anymore/
│   │   └── SKILL.md
│   └── antigravity-guidelines/
│       └── SKILL.md
├── LICENSE
└── README.md
```

## License

[MIT](./LICENSE)
