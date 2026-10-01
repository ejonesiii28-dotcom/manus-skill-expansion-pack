---
name: testing-debugging
description: Systematic bug reproduction, test design, failure isolation, and regression prevention across codebases. Use for failing tests, flaky behavior, production defects, and quality improvements.
---

# Testing and Debugging

Use this skill to turn symptoms into verified fixes.

## Workflow
1. Capture the smallest reproducible case, expected behavior, actual behavior, environment, and logs.
2. Reproduce before editing; preserve a failing test or minimal fixture when possible.
3. Narrow the fault with hypothesis-driven inspection, targeted instrumentation, and boundary checks.
4. Fix the root cause with the smallest coherent change; avoid unrelated refactors.
5. Add or strengthen a regression test, then run focused and full relevant suites.
6. Check for adjacent failure modes and document residual uncertainty.

## Test design
Cover normal, boundary, invalid, empty, concurrent, retry, permission, and compatibility cases as appropriate. Prefer deterministic fixtures and isolated tests.

## Output
Report **Reproduction**, **Root cause**, **Fix**, **Tests run**, and **Remaining risk**. Never claim a test passed unless it actually ran.
