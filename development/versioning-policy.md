# 🔖 Versioning Policy

## Overview

Defines how versions are managed across the codebase and APIs.

## Format

Follows [Semantic Versioning](https://semver.org/): `MAJOR.MINOR.PATCH`

- **MAJOR**: Breaking changes
- **MINOR**: Backward-compatible feature additions
- **PATCH**: Backward-compatible bug fixes

## Guidelines

- All releases must be tagged in version control.
- API versions must be reflected in endpoints (e.g., `/v1/users`).

## Changelog Management

- Use `CHANGELOG.md`
- Entries must follow a consistent format.

## Versioning Tools

- Example: `semantic-release`, `standard-version`

## Exceptions

_List any scenarios where different versioning rules apply (e.g., for experimental features)._
