# Coding Standards

## General Rules

- Prefer simple, explicit code over clever abstractions.
- Keep functions focused.
- Minimize shared mutable state.
- Name code by business meaning.
- Remove dead code quickly.

## File and Module Rules

- One clear purpose per file.
- Split large files before they become hard to review.
- Keep domain logic out of UI components where possible.

## Naming Rules

- Components:
- Services:
- Variables:
- Database tables:
- API routes:

## Error Handling

- Fail loudly in development.
- Return actionable errors.
- Never swallow exceptions without logging.

## Logging

- Log business-significant actions.
- Do not log secrets.
- Include request IDs where available.

## Testing Expectations

- New logic needs tests.
- Bug fixes need regression tests.
- Critical flows need integration coverage.

## Review Expectations

- Changes must be understandable without oral explanation.
- Each PR or change set must state why the change exists.
- Complex changes must include tradeoffs and risks.

## Documentation Expectations

- Update docs when behavior changes.
- Update architecture notes when system boundaries change.
- Update release notes for user-visible changes.
