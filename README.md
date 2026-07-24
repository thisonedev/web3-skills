# Web3 Skills

Agent skills for working with web3 tooling, content, and workflows.

Skills follow the [Agent Skills](https://agentskills.io/) format.

## Install from GitHub

```bash
# Install a specific skill
npx skills add thisonedev/web3-skills --skill "ai-slop-punisher"

# Install everything in the repo
npx skills add thisonedev/web3-skills --all

# List all skills in this repo before installing
npx skills add thisonedev/web3-skills --list
```

### Manual Install

Copy (or symlink) `skills/web3-skills/` into your agent's skills directory:

- Claude Code: `.claude/skills/` or `~/.claude/skills/`
- OpenAI Codex: `.agents/skills/` or `~/.agents/skills/`
- Cursor: `.cursor/skills/` or `~/.cursor/skills/`

## Available Skills

### ai-slop-punisher

Scores technical writing (docs, blog posts, guides, tutorials, code samples,
READMEs) against common AI-writing patterns, quotes every hit, and applies
minimum edits that preserve the writer's voice.

```bash
npx skills add thisonedev/web3-skills --skill "ai-slop-punisher"
```

## License

MIT.