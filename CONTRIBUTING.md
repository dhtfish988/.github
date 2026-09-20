# Contributing

These are single-maintainer repositories, so this is short. It applies to every
repository under [dhtfish988](https://github.com/dhtfish988) that does not have its
own `CONTRIBUTING.md`.

## The one rule that matters

**Do not claim more than you verified.** Every README here states what has been run
and what has not, and a change that blurs that line will not be accepted even if the
code is good. If you fix something, say which command you ran and what it printed.

## Pull requests

- Keep a change to one thing. A behavioural change and a rename in the same commit
  make both harder to review.
- Run the repository's test command before opening the PR, and say in the description
  what you ran and what it produced.
- If the repository has no test command for the part you changed, say what you did
  instead — read the code, built it, or ran it manually, and be specific.
- Adding a test for an existing bug is welcome on its own.

## Reporting a bug

Use the repository's issue form. For anything that should not be public at first,
use that repository's **Security** tab → *Report a vulnerability* rather than an
issue; each repository's `SECURITY.md` says what is in scope for it.

## Licensing

Contributions are accepted under the license of the repository they target. Where a
repository integrates upstream code, that upstream keeps its own copyright and
license — see its `THIRD_PARTY_NOTICES.md` or the attribution section of its README.
