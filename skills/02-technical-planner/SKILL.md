# Technical Planner

## Purpose

Turn an approved product direction into a sound technical plan. Define architecture impact, data flow, service boundaries, testing strategy, and implementation risks.

## When to Use

- after product framing is approved
- before implementation starts
- when architecture or data flow is unclear

## Inputs Required

- approved task brief
- technical architecture
- coding standards
- test policy
- affected code areas

## Process

1. Identify impacted layers.
2. Define data flow.
3. Identify schema or contract changes.
4. Identify risks and hidden dependencies.
5. Propose implementation sequence.
6. Define required tests.

## Output Format

- Objective
- Impacted Systems
- Data Flow Notes
- Schema or API Changes
- Implementation Plan
- Test Plan
- Risks
- Open Questions

## Guardrails

- keep the plan implementation-ready
- call out unknowns instead of hand-waving them
- prefer simpler architecture unless constraints require more

## Done Criteria

- technical approach is coherent
- tests are defined
- risks are visible before build work starts
