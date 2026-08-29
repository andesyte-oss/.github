# Contributing

Thanks for your interest in contributing to an Andesyte project.

This file applies organization-wide. Individual repositories may add their own `CONTRIBUTING.md` with project-specific guidance, which takes precedence.

## Before you start

- For non-trivial changes, open an issue first to discuss the approach.
- Check existing issues and pull requests to avoid duplicate work.
- For security issues, follow [SECURITY.md](./SECURITY.md), not the public issue tracker.

## Development workflow

1. Fork the repository and create a topic branch from `main`.
2. Make your changes with clear commit messages. Conventional Commits are preferred (`feat:`, `fix:`, `docs:`, `chore:`).
3. Add or update tests for any behavior change.
4. Run the project's lint, type-check, and test commands locally before pushing.
5. Open a pull request against `main`. Fill in the PR template.

## Pull request expectations

- Keep PRs focused. One logical change per PR.
- Include a clear description of what changed and why.
- Link the issue the PR closes (`Closes #123`).
- Expect a review from a member of the `engineering` team. Critical paths may also require a `security` review (handled by Sebastion AI on every PR).
- CI must pass before merge.

## Code style

Follow the conventions in the repository you are contributing to. When in doubt, match the surrounding code.

## Licensing

Unless otherwise noted, contributions are accepted under the license declared in the repository's `LICENSE` file. By submitting a pull request, you confirm you have the right to contribute the code under that license.
