# Contributing to Todea projects

Thanks for your interest in contributing. This document covers the defaults
that apply to every repository in the [@TodeaEngineering](https://github.com/TodeaEngineering)
organization. Individual repos may add their own `CONTRIBUTING.md` with
project-specific details; when they do, that file takes precedence.

## Before you start

- Read the project's `README.md` for scope and non-goals.
- Read our [Code of Conduct](CODE_OF_CONDUCT.md).
- Search existing issues and pull requests before opening a new one.

## Reporting a bug

Open a GitHub issue on the relevant repo with:

- The version (commit SHA, tag, or release) you're running.
- What you did, what you expected, and what actually happened.
- A minimal reproduction — ideally a script or a repo link.
- Relevant logs, redacted of anything sensitive.

## Proposing a change

For anything larger than a typo or a one-line fix, open an issue first to
discuss the approach. This saves everyone time if the change doesn't fit the
project's direction.

## Pull requests

1. **Fork** the repository and create a branch from `main`.
2. **Keep it focused.** One concern per pull request. Unrelated cleanups go
   in their own PR.
3. **Match the existing style.** If the repo has a linter or formatter, run
   it. If it has tests, add coverage for new behavior and make sure
   everything passes locally.
4. **Write a clear commit history.** Small, meaningful commits are better
   than one giant squash. The PR body should explain *why*, not just *what*.
5. **Sign off your commits** with `git commit -s` if the project uses
   [DCO](https://developercertificate.org/).
6. **Update the docs.** If your change affects behavior, update the README
   or any relevant docs in the same PR.

## Review

A maintainer will review as soon as they can. Expect feedback focused on
correctness, security, operational impact, and long-term maintenance burden.
We aim to be direct and quick; if a PR goes quiet for more than a week,
feel free to ping.

## Licensing

Unless a repository states otherwise, contributions are accepted under the
[Apache 2.0 License](LICENSE). By opening a pull request, you agree that
your contribution may be distributed under that license.

## Security issues

Please do **not** open a public issue for security vulnerabilities. Email
**ivan@todea.co.kr** with details and we'll respond within a few business
days. See each repo's `SECURITY.md` if present for project-specific
guidance.

## Getting help

- **General questions:** open a GitHub Discussion on the relevant repo, or
  an issue labeled `question`.
- **Commercial support or consulting:** [todea.co.kr](https://todea.co.kr)
  or [ivan@todea.co.kr](mailto:ivan@todea.co.kr).