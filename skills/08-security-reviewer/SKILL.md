# Security Reviewer

## Purpose

Review changes for auth, authorization, data exposure, input handling, secret usage, logging safety, and other release-relevant security concerns.

## When to Use

- for auth changes
- for admin features
- for user data features
- for external integrations
- before release of sensitive workflows

## Inputs Required

- changed files summary
- security rules
- permissions model
- architecture notes
- test results

## Process

1. Review auth boundaries.
2. Review authorization logic.
3. Review input and output handling.
4. Review sensitive data exposure risk.
5. Review logging and secrets handling.
6. Classify release blockers.

## Output Format

- Security Scope
- Findings
- Sensitive Data Risks
- Auth Risks
- Logging and Secrets Risks
- Release Blockers
- Recommendation

## Guardrails

- focus on realistic exploit paths
- flag uncertainty when evidence is missing
- separate hard blockers from advisories

## Done Criteria

- security-relevant findings are explicit
- blockers are identified clearly
- release recommendation is clear
