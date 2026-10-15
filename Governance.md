# Mortal Anomaly Governance

Mortal Anomaly is a flat, volunteer-run open source collective. This document
describes how we make decisions without bosses. It applies to every project
under the Mortal Anomaly organization.

## Core principles

1. **No ranks.** Nobody outranks anybody. There are no leaders, managers, or
   owners of projects, only people doing work.
2. **Everyone is responsible for everything.** If you see a problem anywhere,
   it is yours to raise or fix.
3. **Anyone can question anyone.** Any decision, any piece of work, any person's
   reasoning, including the founder's, can be challenged.
4. **Public by default.** Decisions happen in public channels (GitHub issues,
   discussions, or our public chat) so that anyone can see and question them.
   The only exceptions are code of conduct reports and security vulnerabilities.
5. **Those who do the work shape the work.** Proposals carry weight when people
   commit to building them.

## Who is who

- **Contributor:** anyone who participates in any way: code, docs, issues,
  reviews, design, answering questions.
- **Member:** a contributor with voting rights and repository write access.
  Anyone becomes a member after **three merged contributions** (or equivalent
  sustained non-code work), proposed by any existing member and accepted by
  lazy consensus (see below).
- **Founder:** the person who started Mortal Anomaly. The founder is a member
  like any other and has **no special powers** once there are three or more
  members. Until then, the founder handles decisions alone and in public, and
  every such decision can be revisited by the membership later.

## How decisions are made

### 1. Lazy consensus (the default)

1. Anyone writes a proposal in public: an issue, discussion, or pull request.
2. If **no member objects within 72 hours**, the proposal passes.
3. Small, easily reversible changes (typo fixes, docs, minor bug fixes) need no
   waiting period. Normal pull request review is enough.

### 2. Questioning and objecting

Any contributor may question any decision or piece of work. To keep this
constructive:

- Questions and objections are written **in public**, with a **reason**.
- An objection should, where possible, suggest an alternative.
- Questioning someone's work is never a personal attack, and must not be
  treated as one. Being questioned is normal here; it is how we work.
- An objection from a member pauses a lazy-consensus proposal until it is
  resolved through discussion or a vote.

### 3. Voting (when discussion stalls)

If an objection cannot be resolved through discussion within **7 days**, any
member may call a vote.

- Votes run for **7 days** in a public GitHub discussion.
- Every member has one vote. Options are **yes**, **no**, or **abstain**.
- **Simple majority** of votes cast decides ordinary matters.
- **Two-thirds majority** is required to: change this governance document,
  add or remove a project, change a license, or remove a member.
- A vote needs participation from at least **half of active members** to count.

## Rotating stewards

Some jobs need a clear person responsible at any given time. These are
**responsibilities, not authority**. A steward does the job; they do not get
extra say in decisions.

| Role | What they do |
|---|---|
| Welcome Steward | Greets newcomers, makes sure first pull requests get reviewed within 48 hours |
| Release Steward | Coordinates and publishes releases |
| Triage Steward | Labels and sorts new issues |
| Conduct Stewards (two) | Receive and handle code of conduct reports |

- Stewards serve **one month** (Conduct Stewards serve **three months**, for
  continuity), then rotate.
- Any member can volunteer. If several volunteer, they agree among themselves
  or the membership decides by lazy consensus.
- Nobody may hold the same role for two consecutive terms if someone else has
  volunteered.

## Starting new projects: the pledge system

Anyone, member or member of the public, can propose a new project or major
feature.

1. Open a proposal in GitHub Discussions under **Proposals**, describing what it
   is and why it matters.
2. Anyone can upvote. Votes show **demand**, not obligation.
3. A proposal becomes an active project only when **at least three people
   publicly pledge to build it**, including at least one member.
4. The membership confirms new projects by lazy consensus.

Popular proposals that lack builders are shown publicly as **looking for
builders**, so interested people can step up.

## Security-sensitive changes

Changes that affect security (authentication, cryptography, secrets handling,
release signing, CI permissions, dependency additions) require **approval from
two members other than the author** before merging, regardless of size.

Security vulnerabilities are reported privately (see each project's
`SECURITY.md`) and are not discussed publicly until fixed.

## Inactivity

A member with no activity for **six months** becomes inactive. Inactive members
lose write access and voting rights until they return, which they can do at any
time by announcing it publicly. This is not a punishment; it keeps voting
quorums and access permissions accurate.

## Leaving and removal

- Anyone may leave at any time.
- A member may be removed only for serious or repeated code of conduct
  violations, or for acting against the collective in bad faith, by a
  two-thirds vote. The person concerned may respond publicly before the vote.

## Changing this document

This document can be changed by anyone proposing an edit as a pull request,
followed by a two-thirds member vote. While there are fewer than three
members, the founder may update it in public, and those changes must be
re-confirmed by vote once there are three members.
