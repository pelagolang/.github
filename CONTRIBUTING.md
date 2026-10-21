# Contributing to Pelago

Thanks for helping. This is the short guide shared by every repository in the organization; the `pelago` repository has the details in [`docs/contributing/`](https://github.com/pelagolang/pelago/tree/main/docs/contributing) and in its [README](https://github.com/pelagolang/pelago#contributing).

## Before you start

- For anything bigger than a small fix, open an issue first so we can agree on the approach. Language changes follow the decisions in [ROADMAP.md](https://github.com/pelagolang/pelago/blob/main/ROADMAP.md) and the design docs under `docs/design/`.
- The compiler has no external dependencies on purpose (compile speed is a goal). Ask before adding one.

## Branches

`<author>/<type>/<short-name>`, for example `dennis/feat/for-range`. The type is one of `feat`, `fix` (or `bug`), `perf`, `refactor`, `docs`, `test`, `chore`, `ci`, `build`.

## Commits and pull request titles

Both use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/): `type(scope): imperative summary`, lowercase, no trailing period, under 72 characters. A breaking change gets `!` after the type or scope, or a `BREAKING CHANGE:` footer. Pull requests are squash-merged, so the title becomes the commit on `main`. CI lints both.

```
perf(native): if-convert unpredictable branches
fix(syntaxes): colour the new comment forms
docs: explain how to publish
```

## Pull requests

Fill in the pull request template. Tick every checkbox; if an item does not apply, tick it and write N/A. For the compiler, run these before pushing:

```
cargo fmt --all --check
cargo clippy --all-targets -- -D warnings
cargo test
```

## Licensing of contributions

The projects are licensed MIT OR Apache-2.0, at the user's option. Unless you say otherwise, any contribution you submit is licensed under those same terms, with no additional conditions (this is Section 5 of the Apache License 2.0). We do not require a CLA or a DCO sign-off.

## Conduct

Be kind and be direct. See the [Code of Conduct](CODE_OF_CONDUCT.md).
