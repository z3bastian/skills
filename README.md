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

## How to Use

### Claude Code (CLI)

Add the skill to your project by creating or editing a `CLAUDE.md` file in your project root:

**Option 1: Reference the GitHub raw URL**
```markdown
# Project Instructions

Include the no-ai-writing skill from:
https://raw.githubusercontent.com/z3bastian/skills/main/no-ai-writing/SKILL.md
```

**Option 2: Copy the content directly**
1. Copy the contents of [`no-ai-writing/SKILL.md`](./no-ai-writing/SKILL.md)
2. Paste into your project's `CLAUDE.md` file

### Claude.ai (Web Interface)

1. Go to [claude.ai](https://claude.ai)
2. Click your profile icon → **Settings** → **Profile**
3. Find the **Custom Instructions** section
4. Copy the contents of [`no-ai-writing/SKILL.md`](./no-ai-writing/SKILL.md) (skip the YAML header)
5. Paste into the custom instructions text area
6. Save

### Quick Copy

- **Ready-to-use template**: [`no-ai-writing/CLAUDE.md`](./no-ai-writing/CLAUDE.md) — copy this file directly to your project root
- **Full instructions with YAML metadata**: [`no-ai-writing/SKILL.md`](./no-ai-writing/SKILL.md)
- **Detailed reference patterns**: [`no-ai-writing/references/ai-writing-patterns.md`](./no-ai-writing/references/ai-writing-patterns.md)

## License

MIT
