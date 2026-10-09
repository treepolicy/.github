# Contributing to treepolicy

Thanks for your interest in contributing! This guide applies to every repository in the
treepolicy organization. Repositories with their own `CONTRIBUTING.md` add project-specific
details such as the toolchain, build commands and project layout — read that one first.

## Before you start

- **Bugs and small fixes** — open a pull request directly, or an issue if you're unsure.
- **New features and larger changes** — open an issue first so we can agree on the approach
  before you invest time in it.
- **Security issues** — do not open a public issue; see [SECURITY.md](SECURITY.md).

## Workflow

1. **Fork** the repository and create a feature branch from `main`.
2. **Implement** your change together with tests.
3. **Verify** that tests, lint and build pass locally.
4. **Commit** in small, atomic steps following [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/),
   e.g. `feat(cli): add --quiet flag` or `fix(rule): handle empty directories`.
5. **Open a pull request** against `main` with a clear description of what changed and why.
   Keep pull requests small and focused on one thing.

## Reporting bugs

Open an issue using the bug report template and include:

- what you expected and what happened instead
- steps or a minimal config to reproduce it (redact sensitive paths)
- the version you're using (`treepolicy --version`) and your operating system

## Code of conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating you agree to uphold it.

## License

By contributing, you agree that your contributions are licensed under the license of the
repository you contribute to.
