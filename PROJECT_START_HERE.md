# PROJECT_START_HERE

## Purpose

This repository contains the Manus Project OS. It defines the workflow, rules, and reusable skills used to plan, build, test, review, and release larger software systems using Manus.

Every Manus session should read this file first before performing any task.

---

## Repository Structure

### /docs/core
Core governance and operating rules.

- docs/core/PROJECT_CHARTER.md
- docs/core/DEFINITION_OF_DONE.md
- docs/core/ENGINEERING_STANDARDS.md
- docs/core/TEST_POLICY.md
- docs/core/RELEASE_PROCESS.md

### /skills
Reusable Manus workflow skills.

### /templates
Templates for feature development, QA, releases, and retrospectives.

---

## Required Reading Order

Before starting work, read these documents in order:

1. docs/core/PROJECT_CHARTER.md
2. docs/core/DEFINITION_OF_DONE.md
3. docs/core/ENGINEERING_STANDARDS.md
4. docs/core/TEST_POLICY.md
5. docs/core/RELEASE_PROCESS.md

These documents define the rules and constraints for all work.

---

## Skill Usage Rules

Select a skill based on the type of task.

### Planning

**product-planner**  
Used for new feature discovery, requirements, and scope definition.

**technical-planner**  
Used for architecture design and implementation planning.

**scope-reviewer**  
Used to validate requirements and dependencies before development.

### Development

**feature-builder**  
Used to implement new features.

**refactor-builder**  
Used to improve internal code without changing functionality.

**migration-builder**  
Used for database schema or data migrations.

### Quality

**code-reviewer**  
Used to review code changes after implementation.

**test-designer**  
Used to design test coverage.

**qa-runner**  
Used to validate acceptance criteria and run regression checks.

**security-reviewer**  
Used when authentication, authorization, billing, or sensitive data is involved.

### Release

**release-manager**  
Used to prepare a release candidate.

**release-notes-writer**  
Used to generate release notes.

**retro-writer**  
Used after a release to document lessons learned.

---

## Required Output For Any Feature

Every feature or system change must produce the following information:

- goal
- assumptions
- acceptance criteria
- implementation plan
- affected files
- schema changes
- edge cases
- tests added
- test results
- risks
- rollback notes
- release notes draft

If these elements are missing, the work is incomplete.

---

## Standard Development Workflow

All meaningful tasks should follow this sequence:

1. Read project context
2. Confirm scope and assumptions
3. Produce implementation plan
4. Identify impacted files and risks
5. Implement changes
6. Add or update tests
7. Execute validation
8. Perform code review
9. Execute QA checklist
10. Prepare release notes
11. Summarize risks and remaining work

---

## Guardrails

- Do not mark work complete without test evidence
- Do not bypass QA validation
- Do not modify authentication, authorization, billing, or permissions logic without additional review
- Do not change core architecture without documenting the decision
- Do not ship incomplete work

---

## Definition of Done

A task is complete only when all conditions below are satisfied:

- Acceptance criteria met
- Code implemented
- Tests added and passing
- QA validation completed
- Risks documented
- Rollback path defined
- Release notes drafted

---

## New Project Setup

When creating a new project using this framework:

1. Copy the Manus Project OS repository
2. Update the project charter with the system purpose and scope
3. Add product requirements documentation
4. Add architecture diagrams and database models
5. Define environments for development, staging, and production
6. Configure test commands
7. Define deployment and release procedures

After these steps are complete, development work may begin.

---

## How This Framework Is Used

For each new software system:

1. Clone the Manus Project OS repository
2. Rename the repository for the project
3. Update the charter and architecture documents
4. Use the defined workflow and skills for all work

This ensures consistency across all large Manus projects.

