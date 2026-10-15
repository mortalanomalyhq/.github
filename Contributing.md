# Contributing to Mortal Anomaly

Welcome. Mortal Anomaly is a flat, volunteer-run collective, so there is no
gatekeeper to ask permission from. If something needs doing, you can do it.

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) and
[Governance](GOVERNANCE.md) before you start.

## Ways to contribute

You don't have to write code to be a real contributor:

- Fix bugs or build features
- Improve documentation and examples
- Report bugs with clear steps to reproduce
- Review other people's pull requests
- Test on your own hardware and share results (especially useful for
  `maximumdistill`, which runs on CPUs)
- Answer questions from other users
- Propose new projects (see "Proposing something new" below)

## Your first contribution

1. Find an issue labeled **`good first issue`** in any repository.
2. Comment on it to say you're working on it, so others don't duplicate effort.
3. Fork the repository and create a branch for your change.
4. Make your change. Keep it focused on one thing.
5. Sign off every commit (see "Sign-off" below).
6. Open a pull request that explains **what** you changed and **why**.

**Our promise:** every first pull request gets a review from a human within
**48 hours**. If it doesn't, ping the Welcome Steward in the pull request.

## Sign-off (Developer Certificate of Origin)

We use the [Developer Certificate of Origin](https://developercertificate.org/)
instead of a contributor license agreement. By signing off a commit, you
certify that you wrote the code or otherwise have the right to submit it under
the project's license.

Sign off by adding `-s` when you commit:

```bash
git commit -s -m "Fix tokenizer alignment bug"
```

This adds a line like `Signed-off-by: Your Name <you@example.com>` to your
commit. Pull requests with unsigned commits can't be merged. If you forgot,
fix all commits on your branch with:

```bash
git rebase --signoff main
git push --force-with-lease
```

## Pull request guidelines

- One logical change per pull request.
- Include tests for new behavior where possible.
- Update docs if you change how something works.
- Be ready for questions. Anyone can question anyone's work here, including
  yours and including the reviewer's. It's how we keep quality high, and it's
  never personal.
- Security-sensitive changes need approval from two members other than the
  author (see `GOVERNANCE.md`).

## Reviewing

Anyone can review a pull request, and reviews from non-members are welcome.
Merging requires approval from at least one member.

Good reviews explain their reasoning, separate "must fix" from "suggestion",
and say what's good, not only what's wrong.

## Proposing something new

Have an idea for a feature or a whole new project? Open a post in
**Discussions → Proposals**. Anyone can upvote it. A proposal becomes an active
project once three people pledge to build it. Details are in `GOVERNANCE.md`.

## Becoming a member

After three merged contributions (or equivalent sustained work like reviews,
docs, or support), any member can propose you for membership. Members get
voting rights and write access. There's no interview and no hierarchy beyond
that.

## Reporting security issues

Do **not** open public issues for security vulnerabilities. Follow the
instructions in the affected project's `SECURITY.md`.

## Questions?

Open a discussion or ask in our public chat. There are no stupid questions,
and asking in public helps the next person with the same question.
