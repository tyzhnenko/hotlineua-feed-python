# Hotline.UA Product Feed Python Wrapper

## Terms of usage

By using this project or its source code, for any purpose and in any shape or form, you grant your implicit agreement to all the following statements:

    You condemn Russia and its military aggression against Ukraine
    You recognize that Russia is an occupant that unlawfully invaded a sovereign state
    You support Ukraine's territorial integrity, including its claims over temporarily occupied territories of Crimea and Donbas
    You reject false narratives perpetuated by Russian state propaganda


## Contributing

### Development Workflow
- Create a feature branch from `master`.
- Follow Conventional Commits for messages (e.g., `feat: add ledger summary endpoint`).
    - `feat:` for new features
    - `fix:` for bug fixes
    - `chore:` for maintenance tasks
    - `docs:` for documentation changes
    - `refactor:` for code changes that neither fix a bug nor add a feature
    - `perf:` for performance improvements
    - `test:` for adding or updating tests
    - `build:` for build system changes
    - `ci:` for CI/CD changes
    - `style:` for formatting changes
    - `revert:` for reverting changes
    - `deps:` for dependency updates
    - `security:` for security fixes
    - `contributors:` for acknowledging contributors
    - use an `!` after the type (e.g., `feat!:`) or add a `BREAKING CHANGE:` footer for changes that break backward compatibility
- Keep PRs focused and small; include tests for new behavior.
- Ensure CI basics pass locally: lint, format, type-check, and tests. Run these commands before pushing:
```bash
just format
just lint
just test
```
- Use pre-commit hooks for consistent code quality. Install them with:
```bash
uv run prek install
```

### Pull Request Checklist
- [ ] Tests added/updated for changes
- [ ] `ruff check` and `ruff format` pass
- [ ] `mypy` passes
- [ ] Brief description of changes and rationale

### Reporting Issues
- Include steps to reproduce, expected vs actual behavior, and environment details.
- Propose a minimal fix or a direction when possible.

Thank you for helping improve Hotline.UA Product Feed Python Wrapper!
