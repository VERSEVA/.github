# Contributing

These defaults apply to every VERSEVA repository that does not override them.

## Before you open a PR

- **Open an issue first for anything that changes behavior.** Bug reports and small fixes can
  go straight to a PR; new options, new flags, and new surface area need agreement first, or
  you risk writing code we cannot merge.
- **One change per PR.** A fix bundled with a refactor is two reviews wearing one coat.
- **Tests are part of the change, not a follow-up.** A bug fix ships with a test that fails
  without it. Run the repo's `npm test` before pushing.

## What we look for

- Does it work at the edges, not just the happy path.
- Does it stay readable six months from now.
- Does it avoid adding a dependency. Our tools are deliberately dependency-light; a new
  dependency needs a reason that survives the question "what breaks if this package is
  abandoned".

## Style

Match the file you are editing. If a repo carries a linter, it is the arbiter; if the code and
the linter disagree, say so in the PR rather than silently reformatting.

## Licensing

Contributions are accepted under the repository's license. By opening a PR you confirm you
have the right to submit the work under it.
