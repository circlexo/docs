# Contributing to CircleXO Docs

Thanks for wanting to help. This guide covers how to get a local setup running, the conventions
the codebase follows, and how a change gets merged.

## Ways to contribute

- Report a bug or request a feature through the [issue forms](https://github.com/circlexo/docs/issues/new/choose).
- Pick up an issue labelled [`good first issue`](https://github.com/circlexo/docs/labels/good%20first%20issue)
  or [`help wanted`](https://github.com/circlexo/docs/labels/help%20wanted). Comment on it first so nobody
  duplicates the work.
- Improve the docs. Typos and unclear sentences are worth a PR.

Security problems are **not** issues. Follow [SECURITY.md](SECURITY.md) instead.

## Local setup

The docs are plain Markdown; any editor works.

```bash
git clone https://github.com/circlexo/docs.git && cd docs
```

To work on the docs together with the code, clone [circlexo/apps](https://github.com/circlexo/apps) with `--recurse-submodules`; these docs are its `docs/` submodule.

## Before you open a pull request

CI checks every relative link and anchor. Run the same check locally with [lychee](https://github.com/lycheeverse/lychee):

```bash
lychee --offline --include-fragments './**/*.md'
```

## Conventions

- **Small, focused PRs.** One concern per PR; refactors separate from behaviour changes.
- **Branch names:** `feat/…`, `fix/…`, `docs/…`, `chore/…` off `master`.
- **Commit messages:** [Conventional Commits](https://www.conventionalcommits.org/) style
  (`feat: …`, `fix: …`, `docs: …`), imperative mood, explain *why* in the body.
- **Tests:** a bug fix comes with a test that fails without it; a feature comes with tests for its
  main path and its permission checks.
- **No secrets** in code, tests, fixtures or screenshots. Configuration goes in `.env`
  (documented in `.env.example`).
- **AI-assisted contributions are welcome.** Agents should read [AGENTS.md](AGENTS.md). You are
  responsible for every line you submit: review it, run it, and test it as if you wrote it.

## Developer Certificate of Origin (DCO)

Every commit must be signed off, certifying the [Developer Certificate of Origin](https://developercertificate.org/):
you wrote the change, or otherwise have the right to submit it under the project's license.

```bash
git commit -s -m "fix: describe the change"
```

This adds a `Signed-off-by: Your Name <you@example.com>` trailer that matches your Git identity.
Forgot? `git commit --amend -s` for the last commit, or `git rebase --signoff master` for a branch.

## License

CircleXO Docs is licensed under the [GNU AGPL-3.0](LICENSE). By contributing you agree your contribution
is licensed under the same terms.

## Community

- **Questions and ideas:** [GitHub Discussions](https://github.com/circlexo/docs/discussions)
- **Bugs and feature requests:** [Issues](https://github.com/circlexo/docs/issues/new/choose)

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
