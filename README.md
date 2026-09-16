# Skills

A collection of agent skills for coding workflows.

## What's Inside

Each skill is a self-contained module that extends a coding agent's capabilities. They're organized under the `skills/` directory and can be plugged into tools like **Pi**, **Opencode**, **Cline**, **CMP**, and others.

Some skills are built for core functionality (palette references, terminal UIs, CLI multiplexing, skill creation), while others focus on design, code generation, and visual output.

## Structure

```
skills/
├── catppuccin-palette/   — Color palette references
├── opentui/              — Terminal UI framework
├── skill-creator/        — Skill authoring & evaluation tool
├── skill-herdr/          — Terminal multiplexer control
└── skills/               — Community & third-party skills
```

## Adding a Skill

Copy or symlink a skill directory into `skills/`, then reference its `SKILL.md` in your agent's configuration. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

MIT — see [LICENSE](LICENSE) for details.