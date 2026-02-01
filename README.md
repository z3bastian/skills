# Skills

A collection of custom skills for Claude. Each skill is a self-contained package that extends Claude's capabilities with specialized knowledge and workflows.

## Available Skills

### [no-ai-writing](./no-ai-writing/)

Enforces a natural, human writing style by eliminating identifiable AI writing patterns. Based on documented research into LLM writing tells — overused vocabulary clusters, formulaic sentence structures, puffery, superficial participial analyses, and mechanical formatting habits.

Use this skill whenever Claude produces written content of any kind: articles, reports, emails, blog posts, documentation, creative writing, or any other prose.

**What it catches:**
- Overused AI vocabulary ("delve," "tapestry," "pivotal," "foster," "underscore," etc.)
- Symbolism and legacy inflation ("stands as a testament to," "marking a pivotal moment")
- Superficial "-ing" analyses ("highlighting its significance," "underscoring its importance")
- Formulaic structures (challenge-then-optimism, rule of three, negative parallelisms)
- Promotional/advertisement-like tone
- Formatting tells (excessive bold, title case headings, emoji decoration, em dash overuse)

## Installation

### Claude Code
```bash
npx skills add https://github.com/z3bastian/skills --skill no-ai-writing
```

### Claude.ai

Download the `no-ai-writing` folder from this repo and upload the `SKILL.md` file through Settings > Profile > Skills.

## License

MIT
