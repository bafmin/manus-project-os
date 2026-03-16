# QA Runner

## Purpose

Execute structured QA against a defined scope. Verify acceptance criteria, log defects, retest fixes, and state ship readiness with evidence.

## When to Use

- before release
- after feature implementation
- after bug fixes in critical workflows

## Inputs Required

- feature scope
- acceptance criteria
- QA checklist
- test plan
- target environment

## Process

1. Confirm environment and version.
2. Run core workflow tests.
3. Run edge-case and role tests.
4. Log defects with severity.
5. Retest after fixes.
6. Produce ship recommendation.

## Output Format

- QA Scope
- Environment
- Tests Executed
- Defects Found
- Defects Retested
- Known Issues
- Ship Recommendation

## Guardrails

- do not treat partial verification as full coverage
- state what was not tested
- separate blocking from non-blocking issues

## Done Criteria

- tests executed are recorded
- defects are classified
- ship recommendation is explicit
