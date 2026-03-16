# MANUS_CONTEXT

## Purpose

This document provides persistent operational context for Manus when working inside this repository.

It acts as the system memory that prevents context loss across sessions and ensures that Manus understands the project environment before performing tasks.

Every Manus session should read this file after `PROJECT_START_HERE.md`.

---

## Project Identity

Project Name:

Primary System Purpose:

Core Business Outcome:

Primary Users:

---

## Technology Stack

Frontend:

Backend:

Database:

Infrastructure:

Key Libraries / Frameworks:

---

## Repository Structure

Describe the important folders and their purpose.

Example

/src
Application source code

/docs
Project documentation

/templates
Operational templates used for planning and delivery

/skills
Reusable Manus workflow skills

/tests
Automated test suites

---

## Core System Concepts

Define key domain concepts used throughout the system.

Example

Organization
Represents a company or group using the platform.

User
Represents a person with access to the system.

Project
Represents a managed unit of work within the platform.

---

## Key Workflows

Document the most important workflows in the system.

Example

User onboarding

1. administrator creates invitation
2. user receives invitation
3. user accepts invitation
4. account is created and linked to organization

---

## Architecture Overview

Provide a high level explanation of how the system operates.

Example

- API service handles requests
- services layer contains business logic
- database stores persistent data
- background jobs process asynchronous tasks

Detailed diagrams should be stored in:

/docs/architecture

---

## Environments

Define runtime environments used by the project.

Development
Purpose: local development and debugging

Staging
Purpose: pre‑release validation

Production
Purpose: live system

---

## External Integrations

List external services the system depends on.

Examples

- authentication provider
- email service
- payment provider
- analytics system

---

## Security Model

Describe the system security structure.

Examples

- role based access
- permission checks
- audit logging
- token validation

---

## Operational Constraints

Define important rules or limitations.

Examples

- API rate limits
- data retention rules
- compliance requirements

---

## Known Risks

List major known system risks.

Examples

- third party service dependency
- complex migrations
- scaling limitations

---

## Active Development Focus

Describe the current development priority.

Examples

- building core platform features
- improving system reliability
- expanding integrations

---

## Decision References

Important architectural decisions are stored in:

/docs/decisions

Each decision record should include:

- context
- decision
- alternatives considered
- impact

---

## How Manus Should Use This Document

When beginning work Manus should:

1. read `PROJECT_START_HERE.md`
2. read this document
3. review the relevant feature request or task brief
4. follow the defined workflow and engineering standards

This ensures work aligns with the project architecture and business goals.

