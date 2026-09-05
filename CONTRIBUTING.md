# Contributing to Kyntex

Thank you for taking an interest in Kyntex. The project is currently maintained
as an independent engineering effort, so contributions should be focused,
well-documented, and appropriate for the repository's public or private scope.

## Before opening a change

1. Read the repository README and any component-specific instructions.
2. Search existing issues before creating a duplicate.
3. Open an issue for substantial behavior, protocol, or architecture changes.
4. Never include credentials, personal health information, proprietary device
   details, private recordings, or security-sensitive configuration.

## Pull requests

- Keep each pull request limited to one clear purpose.
- Explain the problem, the chosen approach, and any tradeoffs.
- Include tests or reproducible verification where practical.
- Update documentation and versioned interfaces with the implementation.
- Preserve compatibility unless the change explicitly documents a migration.
- Confirm that generated files, local build products, and secrets are excluded.

## Engineering expectations

- Prefer readable, testable code over premature complexity.
- Keep sensor-derived metrics accurately described and avoid medical claims.
- Treat BLE packet layouts and persisted data formats as versioned contracts.
- Use labeled, subject-separated validation data before proposing learned
  activity models.

By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
Potential security issues should follow [SECURITY.md](SECURITY.md), not a public
issue.
