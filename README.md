# Manus Project OS


Structured operating system for building large software projects with Manus.

Manus Project OS provides governance, workflow structure, and repeatable delivery templates so AI assisted engineering stays organized as projects grow.

This framework works well for:

- B2B SaaS platforms
- internal operations systems
- AI enabled applications
- compliance and workflow platforms

---

# What this repository provides

Manus Project OS gives teams a reusable structure for disciplined AI assisted software development.

The framework includes:

- project operating rules
- reusable Manus skills
- structured planning templates
- QA validation workflows
- release discipline
- decision and risk tracking

The objective is simple.

Large projects should behave like engineered systems, not prompt experiments.

---

# Development workflow

Every meaningful change should move through the same pipeline.

```
Feature Request
      ↓
Change Plan
      ↓
Task Brief
      ↓
Implementation
      ↓
QA Report
      ↓
Release Packet
```

Each step produces documentation stored in the repository.

---

# Design principles

## One source of truth

Product, architecture, testing, and release rules live in version control.

## Evidence driven progress

Work advances when validation exists, not when code compiles.

## Planning before implementation

Major changes require a documented change plan before development begins.

## Repeatable delivery

Every feature follows the same lifecycle from idea to release.

## Layered context

Permanent context, project context, and task context remain separated.

---

# Recommended repository structure

```text
manus-project-os/
├── README.md
├── PROJECT_START_HERE.md
├── MANUS_CONTEXT.md
├── MANUS_SESSION_START.md
├── docs/
│   ├── charter/
│   │   └── PROJECT_CHARTER.md
│   ├── product/
│   │   └── PRODUCT_REQUIREMENTS.md
│   ├── architecture/
│   │   └── TECHNICAL_ARCHITECTURE.md
│   ├── standards/
│   │   ├── CODING_STANDARDS.md
│   │   ├── SECURITY_RULES.md
│   │   └── DEFINITION_OF_DONE.md
│   ├── testing/
│   │   ├── TEST_POLICY.md
│   │   └── QA_CHECKLIST.md
│   ├── release/
│   │   ├── RELEASE_PROCESS.md
│   │   └── RELEASE_NOTES_TEMPLATE.md
│   ├── retros/
│   │   └── RETRO_TEMPLATE.md
│   ├── decisions/
│   │   └── DECISION_LOG.md
│   └── risks/
│       └── RISK_REGISTER.md
├── skills/
│   ├── 00-skill-template/
│   │   └── SKILL.md
│   ├── 01-product-planner/
│   │   └── SKILL.md
│   ├── 02-technical-planner/
│   │   └── SKILL.md
│   ├── 03-scope-reviewer/
│   │   └── SKILL.md
│   ├── 04-feature-builder/
│   │   └── SKILL.md
│   ├── 05-code-reviewer/
│   │   └── SKILL.md
│   ├── 06-test-designer/
│   │   └── SKILL.md
│   ├── 07-qa-runner/
│   │   └── SKILL.md
│   ├── 08-security-reviewer/
│   │   └── SKILL.md
│   ├── 09-release-manager/
│   │   └── SKILL.md
│   └── 10-retro-writer/
│       └── SKILL.md
├── templates/
│   ├── FEATURE_REQUEST_TEMPLATE.md
│   ├── TASK_BRIEF_TEMPLATE.md
│   ├── CHANGE_PLAN_TEMPLATE.md
│   ├── QA_REPORT_TEMPLATE.md
│   ├── RELEASE_PACKET_TEMPLATE.md
│   └── PROJECT_BOOTSTRAP_CHECKLIST.md
└── .github/
    └── workflows/
        └── repo-health.yml
```

---

# How to use this framework

## 1. Copy or fork the repository

Create a new repository for your product and copy this structure.

## 2. Complete the core documentation

Before development begins complete the core documents:

- docs/charter/PROJECT\_CHARTER.md
- docs/product/PRODUCT\_REQUIREMENTS.md
- docs/architecture/TECHNICAL\_ARCHITECTURE.md
- docs/standards/CODING\_STANDARDS.md
- docs/testing/TEST\_POLICY.md
- docs/release/RELEASE\_PROCESS.md

These files define how the project operates.

## 3. Configure Manus skills

Each directory inside `skills/` defines a reusable development role. Adapt these to your stack and workflows.

## 4. Execute feature work

Follow the development workflow using the templates in `/templates`.

Feature request → change plan → task brief → implementation → QA report → release packet.

---

# Core operating rules

## Context layers

Three context layers guide development.

Permanent context

- business model
- product purpose
- architectural rules
- coding standards
- naming rules

Project context

- roadmap
- milestones
- data model
- infrastructure
- environment configuration

Task context

- specific feature or bug
- acceptance criteria
- constraints
- impacted components

---

# Stage gates

Development moves through validation gates.

## Gate 1 Scope

- requirements defined
- dependencies identified
- risks recorded

## Gate 2 Build

- code implemented
- tests written
- local validation passes

## Gate 3 QA

- acceptance criteria verified
- regression checks completed
- authentication and permissions validated

## Gate 4 Release

- release notes written
- rollback path defined
- deployment steps documented

## Gate 5 Post release

- retrospective recorded
- issues logged
- follow up work identified

---

# Customizing for a project

Each project should adjust:

- architecture documentation
- technology stack rules
- deployment workflow
- test commands
- environment configuration
- security policies

---

# Suggested improvements as projects mature

As the system grows consider adding:

- GitHub issue templates
- pull request templates
- architecture decision records
- migration playbooks
- environment runbooks
- seeded test data scripts
- browser testing automation
- CI evidence collection

---

# Quick start

1. Complete the documents in `docs/`.
2. Configure skills in `skills/`.
3. Use templates in `templates/` to plan and execute work.
4. Commit the repository.
5. Treat the repository as the operating system for the project.

---

# License

MIT License with attribution.

Copyright (c) 2026 Phillip Williams, Bafmin LLC

Permission is granted, free of charge, to any person obtaining a copy of this software and associated documentation files to deal in the Software without restriction. This includes the rights to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the Software.

Conditions

1. The copyright notice and this permission notice must be included in all copies or substantial portions of the Software.

2. Public redistributions or derivative frameworks must include attribution in documentation or repository description using the following credit:

Manus Project OS created by Phillip Williams.

The software is provided "as is", without warranty of any kind, express or implied, including but not limited to merchantability, fitness for a particular purpose, and noninfringement.