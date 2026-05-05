# Project Template

A reusable GitHub project template for AI-assisted software development.

This repository provides:
- Repo-wide Copilot instructions
- Path-specific instructions for Python and tests
- A reusable Agent Skill for testing workflows
- Starter documentation and contribution guidance
- A sample CI workflow
- Guidance for all AI coding agents via `AGENTS.md`

## Structure

```text
your-template-repo/
├── .github/
│   ├── copilot-instructions.md
│   ├── instructions/
│   │   ├── python.instructions.md
│   │   └── tests.instructions.md
│   ├── skills/
│   │   └── testing/
│   │       └── SKILL.md
│   ├── workflows/
│   │   └── ci.yml
│   ├── CONTRIBUTING.md
│   └── ISSUE_TEMPLATE/
├── AGENTS.md
├── .gitignore
├── .editorconfig
├── README.md
├── docs/
│   ├── architecture.md
│   └── adr/
├── src/
└── tests/
```

## Included conventions

### `.github/copilot-instructions.md`
Repository-wide guidance for GitHub Copilot across the codebase.

### `.github/instructions/*.instructions.md`
Scoped instructions for specific file patterns or directories.

### `.github/skills/`
Reusable Agent Skills that can document repeatable workflows for Copilot agents.

### `AGENTS.md`
Cross-agent guidance for Copilot, Claude, Gemini, and other coding agents.

## Using this as a template

After reviewing the files:
1. Go to **Settings** for this repository.
2. Enable **Template repository**.
3. Use **Use this template** to create new projects.

## Suggested next steps

- Customize language/tooling conventions.
- Add issue templates and pull request templates.
- Add repo labels, branch protection, and CODEOWNERS if needed.
