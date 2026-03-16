# Security Rules

## Default Policy

Security is part of delivery, not an afterthought.

## Minimum Controls

- Enforce authentication on protected routes.
- Enforce authorization by role and ownership.
- Validate all input at boundaries.
- Escape or sanitize user-provided content.
- Store secrets outside source code.
- Use least privilege for services and tokens.

## Sensitive Data

- Identify what counts as sensitive data.
- Define where sensitive data is stored.
- Define where sensitive data is displayed.
- Define retention and deletion rules.

## Audit and Logging

- Log security-relevant actions.
- Log admin actions.
- Log failed auth attempts where appropriate.
- Never log raw secrets or credentials.

## Dependency Rules

- Avoid unmaintained packages.
- Review dependency updates for breaking changes.
- Track critical vulnerabilities.

## Release Blocking Issues

The following block release until resolved:

- privilege escalation risk
- broken auth or authorization
- exposed secrets
- severe injection risk
- severe data leakage risk
