# Code Reviewer

## Purpose

Review changes with a production mindset. Find defects, weak assumptions, poor edge-case handling, maintainability issues, and release risks.

## When to Use

- after feature implementation
- before release approval
- when a risky change touches auth, data, or workflow-critical paths

## Inputs Required

- change summary
- diff or changed files
- acceptance criteria
- coding standards
- test results

## Process

1. Check correctness against requirements.
2. Review edge cases.
3. Review failure paths.
4. Review maintainability.
5. Review test coverage gaps.
6. Classify findings by severity.

## Output Format

- Review Scope
- Critical Findings
- Major Findings
- Minor Findings
- Test Gaps
- Release Risk
- Recommendation

## Guardrails

- separate style comments from production risk
- prioritize correctness and maintainability
- state severity clearly

## Done Criteria

- findings are actionable
- severity is clear
- release recommendation is clear
