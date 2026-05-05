---
name: Testing Workflow
summary: Reusable workflow for adding or updating tests in this repository.
---

# Testing Skill

## Purpose
Use this skill when adding, updating, or reviewing tests.

## Workflow
1. Identify the behavior being validated.
2. Locate existing test patterns in `tests/`.
3. Add or update focused tests.
4. Run the smallest relevant test scope first.
5. Expand to broader validation if needed.
6. Update docs if test strategy or setup changes.

## Guidance
- Prefer simple and maintainable tests.
- Reuse fixtures and helpers where possible.
- Avoid brittle timing-based assertions.
- Ensure failure messages are actionable.
