# role-ai-agents

A minimal repository demonstrating the role of AI agents in open source collaboration.

## What is configured

- **Copilot instructions**: `.github/copilot-instructions.md`
- **Copilot setup steps**: `.github/workflows/copilot-setup-steps.yml`
- **PR validation**: `.github/workflows/pr-validation.yml`
- **Security scanning (CodeQL)**: `.github/workflows/codeql.yml`

## How pull requests are validated

Every pull request runs:

1. Markdown linting
2. GitHub Actions workflow linting
3. CodeQL analysis for GitHub Actions security issues

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution expectations.
