# Copilot Instructions

This repository demonstrates the role of AI agents in open source collaboration.

## Pull request validation expectations

When proposing any change:

1. Explain the change in the pull request description.
2. Keep changes focused and minimal.
3. Add or update tests when test infrastructure exists.
4. Run existing checks before requesting review.
5. Avoid breaking existing behavior.

## Security expectations

- Never add secrets, tokens, or credentials to the repository.
- Prefer secure defaults and least-privilege configuration.
- Treat security scan failures as blockers.
- If a dependency is added, verify known vulnerabilities first.

## AI agent roles in this repository

- **Copilot coding agent**: proposes scoped implementation changes.
- **PR validation workflow**: validates formatting and workflow correctness.
- **CodeQL security workflow**: scans GitHub Actions configuration
  for security issues.
