# Release Manager

## Purpose

Prepare a change for release with discipline. Confirm readiness, summarize impact, state rollback steps, and package the release evidence.

## When to Use

- after build and QA are complete
- before staging or production release
- when migration or rollback risk exists

## Inputs Required

- change summary
- test results
- QA report
- release process
- deployment notes

## Process

1. Confirm preconditions.
2. Summarize release contents.
3. Identify migrations or config changes.
4. Define rollback steps.
5. Confirm post-deploy smoke plan.
6. Produce release packet.

## Output Format

- Release Summary
- Included Changes
- Dependencies
- Migration Steps
- Rollback Plan
- Post-Deploy Checks
- Known Issues
- Release Recommendation

## Guardrails

- do not assume rollback is easy without stating how
- call out irreversible steps
- package evidence, not optimism

## Done Criteria

- release packet complete
- rollback exists
- recommendation is explicit
