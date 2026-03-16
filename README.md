# Manus Project OS

Structured operating system for building large software projects with Manus.

Manus Project OS provides governance, workflow structure, and repeatable
delivery templates so AI-assisted engineering stays organized as projects grow.

This framework is designed for:

• B2B SaaS platforms
• internal operations systems
• AI-enabled applications
• compliance and workflow platforms

## What this repo does

Manus Project OS gives you a reusable structure for:

- project-level operating rules
- role-based Manus skills
- fixed delivery templates
- QA and release gates
- decision and risk tracking
- repeatable output formats for larger builds

Use it for any substantial app or platform project:

- B2B SaaS
- internal ops software
- workflow systems
- AI-enabled applications
- compliance platforms
- multi-phase product builds

## Design principles

1. One source of truth
   - Product, architecture, testing, and release rules live in version control.

2. Fixed outputs
   - Every major Manus workflow produces the same categories of output.

3. Stage gates
   - Work does not move forward because code exists. Work moves forward because evidence exists.

4. Reusable skills
   - Skills are modular and project-agnostic.

5. Project context in layers
   - Permanent operating context, project context, and task context stay separate.

## Recommended repo structure

```text
manus-project-os/
├── README.md
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

## How to use this

### 1. Fork or copy this repo

Place it in its own repo, or copy the structure into the root of a product repo.

### 2. Fill out the core docs first

Before asking Manus to build features, complete:

- `docs/charter/PROJECT_CHARTER.md`
- `docs/product/PRODUCT_REQUIREMENTS.md`
- `docs/architecture/TECHNICAL_ARCHITECTURE.md`
- `docs/standards/CODING_STANDARDS.md`
- `docs/testing/TEST_POLICY.md`
- `docs/release/RELEASE_PROCESS.md`

### 3. Load skills into Manus

Each folder under `skills/` contains a reusable operating skill. Adapt the language and workflows to your preferred stack.

### 4. Run work in this order

For most feature work:

1. Product Planner
2. Technical Planner
3. Scope Reviewer
4. Feature Builder
5. Code Reviewer
6. Test Designer
7. QA Runner
8. Security Reviewer
9. Release Manager
10. Retro Writer

### 5. Require evidence

Every feature should leave behind:

- implementation plan
- changed files summary
- tests added
- test results
- risk notes
- rollback notes
- release note draft

## Core operating rules

### Context model

Use three layers of context:

- Permanent context
  - business model
  - product purpose
  - architectural rules
  - coding standards
  - naming rules

- Project context
  - roadmap
  - milestones
  - data model
  - infra details
  - environment notes

- Task context
  - specific feature or bug
  - acceptance criteria
  - constraints
  - impacted files
  - target environment

### Stage gates

#### Gate 1, Scope
- Requirements are clear.
- Dependencies are identified.
- Risks are logged.

#### Gate 2, Build
- Code is complete.
- Lint passes.
- Local tests pass.

#### Gate 3, QA
- Acceptance criteria verified.
- Regression smoke completed.
- Auth and permissions checked.

#### Gate 4, Release
- Release notes drafted.
- Rollback path defined.
- Migration steps documented.

#### Gate 5, Post-ship
- Retro completed.
- Defects logged.
- Follow-up tasks created.

## What to customize per project

You should customize:

- architecture decisions
- tech stack rules
- branch naming rules
- deployment method
- test commands
- definition of done
- release checklist
- environment URLs
- staging credentials process
- domain-specific security controls

## Suggested add-ons

As your project matures, add:

- GitHub issue templates
- pull request templates
- architecture decision records
- migration playbooks
- environment runbooks
- seeded test data scripts
- browser test scripts
- CI evidence collection

## Fast start

1. Complete the templates in `docs/`.
2. Rename or extend the skills in `skills/`.
3. Add project-specific examples to each skill.
4. Commit the repo.
5. Point Manus at this repository and treat it as your project operating system.

## License

MIT is a good default for internal reuse. Adjust to fit your goals.
