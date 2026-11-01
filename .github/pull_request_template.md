<!-- Summary, no heading: 2–4 sentences giving the problem, the change, its effect
on customers, staff or operations, and the risk or rollback. Put "Closes #N" and
linked PRs (with merge order) above it. Title: an imperative sentence stating the
outcome. Guide: https://github.com/jirozone/engineering/blob/main/writing.md
Delete these hints once each section is written. -->

## What changed

<!-- Bullets with a bold lead-in. Name files, models, endpoints, migrations and
env vars. Explain what a later "cleanup" could get wrong. Don't restate the diff. -->

## Verified

<!-- What you ran and what you checked, with numbers. End with "**Not verified:**"
and what is left, if anything is. -->

## After merge

<!-- Anything someone must do by hand once this merges: apply a migration,
set an env var, run `uv sync` or `pnpm install`, reinstall pre-commit, change a
dashboard setting. If there is anything, add the `action-required` label, which
posts the PR to Slack. Otherwise write "Nothing". Nothing goes below this section:
the PR body becomes the squash commit message. -->
