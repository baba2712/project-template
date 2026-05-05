# Copilot Instructions

This repository is a reusable project template intended for AI-assisted development.

## Repository goals
- Keep the repository easy to scaffold and adapt for new projects.
- Prefer clear structure, small focused modules, and concise documentation.
- Treat docs and automation as first-class project assets.

## Coding guidelines
- Keep changes minimal and scoped.
- Prefer readable code over clever code.
- Add or update tests for behavior changes.
- Update documentation when changing workflows, architecture, or setup.
- Avoid adding dependencies unless clearly justified.

## Project structure expectations
- Production code belongs in `src/`.
- Tests belong in `tests/`.
- Architecture and decision records belong in `docs/`.
- Reusable AI instructions belong under `.github/`.

## When generating code
- Follow existing naming and layout patterns.
- If adding a new component, include a short docstring or comment describing its purpose.
- If assumptions are required, document them in the relevant file or README.

## When modifying this template
- Keep examples generic and reusable.
- Do not hardcode organization-specific values unless intentionally customizing the template.
