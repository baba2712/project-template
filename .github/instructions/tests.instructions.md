---
appliesTo: "tests/**"
---

# Test Instructions

## Test design
- Prefer deterministic tests.
- Avoid unnecessary network or filesystem coupling.
- Keep tests readable and behavior-focused.
- Use fixtures/helpers to reduce duplication.

## Assertions
- Assert on behavior and outcomes, not implementation details unless necessary.
- Keep one primary reason for failure per test when practical.

## Maintenance
- When production behavior changes, update tests in the same change.
- Remove obsolete tests instead of weakening them.
