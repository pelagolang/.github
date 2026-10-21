<!--
Default template for repositories without their own. Keep it short: a reviewer should know in 30 seconds what changed and why.
Branch: <author>/<type>/<short-name>. Title: Conventional Commits, `type(scope): summary`. It becomes the squash commit.
-->

## Summary

**Before:** <what happened, or was missing, before this change>

**After:** <what happens now>

## Type

<!-- Keep one. It should match the branch type and the type in the PR title. -->

- [ ] `feat`
- [ ] `fix` / `bug`
- [ ] `perf`
- [ ] `refactor`
- [ ] `docs`
- [ ] `test`
- [ ] `chore`
- [ ] `ci` / `build`
- [ ] Breaking change: `!` in the title or a `BREAKING CHANGE:` footer

## Why

<The problem, issue or earlier PR behind this.>

## Checks

<!-- Tick every box. If one does not apply, tick it and write N/A. -->

- [ ] The title and every commit subject follow Conventional Commits
- [ ] The branch is named `<author>/<type>/<short-name>`
- [ ] Tests or checks for the change pass locally and in CI (or N/A)
- [ ] Docs updated (or N/A)

## Risks and follow-ups

<What could break, what you did not do on purpose. Write "none" if none.>
