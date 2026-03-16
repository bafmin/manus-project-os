# MANUS_SESSION_START

## Purpose

This document defines the startup procedure Manus should follow when beginning a work session in this repository.

The goal is to ensure every session begins with the correct project context, operating rules, and workflow discipline.

Following this procedure prevents context drift and improves reliability when building complex systems.

---

## Session Startup Sequence

When beginning a new session, Manus should follow this order.

1. Read `PROJECT_START_HERE.md`
2. Read `MANUS_CONTEXT.md`
3. Read `PROJECT_CHARTER.md`
4. Review `ENGINEERING_STANDARDS.md`
5. Review `TEST_POLICY.md`
6. Review `RELEASE_PROCESS.md`

After reviewing these documents, identify the specific task or feature being worked on.

---

## Determine Task Type

Manus should determine the type of work before taking action.

Possible task types

- feature development
- bug fix
- refactor
- architecture change
- release preparation

Each task type should follow the corresponding template workflow.

---

## Workflow Selection

Select the correct delivery pipeline.

Feature work

1. FEATURE_REQUEST_TEMPLATE.md
2. CHANGE_PLAN_TEMPLATE.md
3. TASK_BRIEF_TEMPLATE.md
4. QA_REPORT_TEMPLATE.md
5. RELEASE_PACKET_TEMPLATE.md

Bug fix or small change

1. TASK_BRIEF_TEMPLATE.md
2. CHANGE_PLAN_TEMPLATE.md
3. QA_REPORT_TEMPLATE.md

Release preparation

1. QA_REPORT_TEMPLATE.md
2. RELEASE_PACKET_TEMPLATE.md

---

## Context Verification

Before implementing changes Manus should confirm:

- system architecture is understood
- impacted components are identified
- dependencies are known
- risks are documented

If context is missing Manus should request clarification before continuing.

---

## Planning Requirement

Major changes must have a documented change plan before code is written.

The change plan should describe

- objective
- affected components
- planned implementation
- test strategy
- risks
- rollback approach

---

## Implementation Discipline

When writing code Manus should:

- follow ENGINEERING_STANDARDS.md
- maintain clear naming and structure
- avoid unnecessary complexity
- add appropriate tests

---

## Validation Process

After implementation Manus should:

1. execute automated tests
2. validate acceptance criteria
3. perform regression checks
4. record results in QA_REPORT_TEMPLATE.md

---

## Release Preparation

Before recommending a release Manus should ensure

- all tests pass
- QA validation completed
- rollback plan documented
- release notes drafted

Release documentation should be recorded in

`RELEASE_PACKET_TEMPLATE.md`

---

## Session Output Requirements

At the end of a work session Manus should produce:

- summary of work performed
- files modified
- tests added or updated
- risks identified
- recommended next steps

---

## Continuous Context Awareness

During long sessions Manus should periodically verify

- work remains aligned with project architecture
- changes follow engineering standards
- new risks are recorded

---

## Guiding Principle

The objective is not simply to generate code.

The objective is to produce reliable, well documented, testable software that can be safely released.

