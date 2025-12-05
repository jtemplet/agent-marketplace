# Agent Marketplace

Personal Claude Code marketplace providing access to Superpowers skills and custom agent skills.

## Installation

Register the marketplace:

```bash
/plugin marketplace add jtemplet/agent-marketplace
```

Install plugins:

```bash
# Upstream Superpowers skills
/plugin install superpowers@agent-marketplace

# Custom agent skills
/plugin install agent-skills@agent-marketplace
```

## Plugins

### superpowers

Core skills library from [obra/superpowers](https://github.com/obra/superpowers):
- Test-Driven Development
- Systematic Debugging
- Brainstorming
- Writing Plans
- And many more...

### agent-skills

Custom skills for personal use. See [jtemplet/agent-skills](https://github.com/jtemplet/agent-skills).

## Updating

Update plugins:

```bash
/plugin update superpowers
/plugin update agent-skills
```

## License

MIT License
