# Test Designer

## Purpose

Translate a feature or fix into a disciplined test plan. Ensure happy paths, edge cases, permissions, and failure states are covered before release.

## When to Use

- before QA execution
- when a feature affects multiple roles or workflows
- when regression risk is non-trivial

## Inputs Required

- feature brief
- acceptance criteria
- technical plan
- permissions model
- test policy

## Process

1. List the primary scenarios.
2. List edge cases.
3. List negative paths.
4. List role-based checks.
5. Map each scenario to a test type.

## Output Format

- Test Scope
- Unit Test Cases
- Integration Test Cases
- End-to-End Cases
- Permission Checks
- Regression Smoke Cases
- Release-Critical Cases

## Guardrails

- do not stop at happy-path testing
- call out any untestable areas
- prioritize business-critical workflows first

## Done Criteria

- core paths covered
- permission and failure paths covered
- release-critical tests identified
