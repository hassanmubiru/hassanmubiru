# Contributing

Thanks for your interest in contributing. This guide applies to this profile repository and to every project maintained by **Hassan Mubiru — Creator of StreetJS**, including StreetJS, Vibra, Afrchat, and SCMINER. It explains how to report issues, how to propose changes, and the review steps your contribution goes through.

## Code of Conduct

By participating, you agree to uphold the [Code of Conduct](./CODE_OF_CONDUCT.md). Please read it before contributing.

## How to report issues

1. **Search first.** Check existing [Issues](../../issues) and the repository **Discussions** to avoid duplicates.
2. **Pick the right channel.** Usage questions belong in **Q&A Discussions**; confirmed bugs and scoped requests belong in **Issues**.
3. **Use a template.** Open an issue with the matching template (Bug Report, Feature Request, or Documentation Issue) and fill in every required field.
4. **Make bugs reproducible.** Include a minimal reproduction, the version you are running, your environment (OS, Node.js version), expected vs. actual behavior, and relevant logs.

## How to propose changes

1. **Discuss non-trivial work first.** Open or comment on an issue so the approach is agreed before code is written.
2. **Fork and branch.** Branch from `main` with a descriptive name, e.g. `fix/router-edge-case` or `feat/typed-config`.
3. **Set up locally.** Install dependencies and confirm the test suite runs before you start.
4. **Develop to the conventions.** Keep changes focused on a single concern, follow the existing style, pass lint and type checks, and add or update tests for your change.
5. **Use Conventional Commits.** Prefix commits with `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, or `chore:` so the changelog and version bumps can be derived from history.
6. **Open a pull request.** Use the [pull request template](./.github/pull_request_template.md), link the related issue (`Closes #123`), describe the change and motivation, and note any breaking change.

## Local development

```bash
# Install dependencies
npm install

# Run the test suite (single, non-watch pass)
npm test

# Type-check the project
npm run typecheck
```

## Review steps

1. **Automated checks** run on every pull request: lint, type-check, tests, and a build. A pull request cannot merge until CI is green.
2. **Maintainer review** checks correctness, API and design fit, test coverage, and documentation. Requested changes block merge.
3. **Iteration** — address review comments and push updates; re-review continues until approval.
4. **Approval and merge** — at least one maintainer approval plus green CI are required. Pull requests are merged with **squash-and-merge** to keep `main` a clean, Conventional-Commit history.
5. **Post-merge** — the linked issue closes automatically and the change is queued for the next release and recorded in the [changelog](./CHANGELOG.md).

## Commit and PR checklist

- [ ] Tests added or updated and passing
- [ ] Lint and type-check pass locally
- [ ] Documentation updated where relevant
- [ ] Commit messages follow Conventional Commits
- [ ] The pull request links its related issue

Thank you for helping make these projects better.
