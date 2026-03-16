# QA Report Template

This document records validation results for a change or release candidate.

---

## Scope

Describe what was tested.

Example

Feature: organization invitations  
Change Plan: change-plan-002

---

## Environment

environment  
build or commit  
tester  
test date

Example

staging  
commit abc123  
tester name

---

## Tests Executed

List test scenarios.

- scenario
- scenario
- scenario

Examples

- user authentication
- role based access
- data creation workflow

---

## Defects Found

| ID | Severity | Summary | Status |
|----|----|----|----|
| id | critical/high/medium/low | description | open/fixed/retested |

---

## Retest Results

If fixes were applied record results.

- issue resolved
- issue verified

---

## Known Issues

Non blocking issues.

- issue
- issue

---

## Workflow Validation

Confirm key workflows function correctly.

- authentication
- permissions
- primary product workflow
- background jobs

---

## Recommendation

Ship  
Hold

Provide reasoning if release should be blocked.

---

## Notes

Additional observations or testing context.