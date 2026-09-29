# Profile Repository Maintenance

This repository is not a normal software project. It is the GitHub special
profile repository for `Charlie-Wang-03`, and `README.md` is displayed on
the owner's public GitHub profile.

Its long-term job is to provide a concise, credible entry point into the
owner's work across applied mathematics, scientific machine learning, AI
engineering, and open source.

For AI-specific operating rules, read [AGENTS.md](AGENTS.md) first.

## Maintenance model

The profile should be treated as a **curated summary of current public
evidence**, not as a complete inventory of the GitHub account.

The GitHub account can contain:

- public original projects;
- public forks used for upstream contribution;
- private research or engineering repositories;
- temporary experiments and archives;
- collaboration or dogfood repositories.

Only a small, deliberately selected subset belongs on the public profile.

## Public profile surfaces

Maintain these surfaces as one coherent public record:

- `README.md` — canonical English profile and primary human-facing overview.
- `README.zh-CN.md` — natural Simplified Chinese companion.
- `PROFILE.md` — compact structured reference for stable public technical
  facts and selected work.
- `llms.txt` — concise source map for agents, prioritizing canonical or raw
  Markdown sources and brief descriptions.
- `profile.jsonld` — Schema.org `Person` metadata for public identity,
  affiliation, technical areas, and selected work.

The README remains authoritative for current public positioning. The structured
reference files should summarize or point to verified public facts rather than
introduce new claims.

## What should remain stable

The current profile design intentionally favors:

- a polished academic + developer portfolio style;
- restrained visual elements;
- a broad, exploratory `Current Focus`;
- a small set of representative public projects;
- a compact upstream-contributions section;
- English and natural Simplified Chinese versions;
- factual, non-promotional language.

Do not redesign these principles merely because a new GitHub profile trend
appears.

## Routine profile audit

When the profile appears stale, use this sequence.

### 1. Verify this repository first

Check:

- current `main`;
- open PRs;
- recent merged profile PRs;
- Markdown CI;
- current README links and widgets;
- whether the English and Chinese versions still agree;
- whether `PROFILE.md`, `llms.txt`, and `profile.jsonld` still match the
  canonical README and selected public work;
- whether the structured profile JSON-LD still parses successfully.

### 2. Inspect the public GitHub portfolio

Use current GitHub account data.

Review:

- public repositories owned by the account;
- currently pinned repositories when the interface/tool can retrieve them;
- meaningful releases;
- archived or renamed repositories;
- recent upstream PRs and their actual status.

If pinned repositories cannot be retrieved reliably, do not guess them.

### 3. Re-evaluate selected projects

Ask of each current project card:

- Is it still public?
- Is it still maintained or representative?
- Does its README support the profile description?
- Does it show something meaningfully different from the other selected
  projects?
- Would replacing it improve the profile's evidence without making the page
  noisier?

A new repository should not replace an existing project merely because it is
newer.

### 4. Re-evaluate open-source contributions

The section should answer:

> Which upstream communities/projects has the owner meaningfully contributed to?

It should not answer:

> How many pull requests has the owner opened?

Group multiple related PRs under one upstream project. Keep one line per
upstream project unless there is a strong reason to do otherwise.

### 5. Check identity drift

Review whether the profile still reflects:

- current academic status;
- current research interests;
- current engineering direction;
- current open-source activity;
- intended contact information.

Major identity changes require explicit owner approval.

## Change levels

| Level | Typical change | Expected workflow |
| --- | --- | --- |
| Low | typo, broken link, stale PR status, wording correction | branch + PR + CI |
| Medium | project-card refresh, contribution-summary refresh, tool badge change | branch + PR + CI + human review |
| High | new identity statement, major visual redesign, privacy-sensitive content, governance/security weakening | explicit owner approval before implementation or merge |

## Repository workflow

For normal maintenance:

1. create a short-lived branch from `main`;
2. make one coherent change set;
3. keep English/Chinese profile facts synchronized;
4. update `CHANGELOG.md` for notable changes;
5. open a PR;
6. wait for `Markdown Check`;
7. review the rendered README, not only the raw diff;
8. squash merge after approval;
9. delete the temporary branch.

The repository is intentionally kept close to a single-long-lived-branch model:
`main` is the durable branch; feature/maintenance branches should be
short-lived.

## Public/private boundary

The strongest maintenance rule is simple:

> Access is not permission to publish.

An AI connector may be able to see private repositories or account metadata.
That does not make those details valid profile content.

Private projects may influence internal reasoning about what *not* to claim,
but their names, content, results, infrastructure, or status must not be copied
into this public repository without explicit approval.

## README and pinned repositories

The profile README and GitHub pinned repositories serve different roles:

- **README** — explains the owner's technical narrative and provides curated
  context.
- **Pins** — provide direct artifact-level evidence.

They may overlap, but should not be exact duplicates by default.

When the set of pins changes, re-check whether the README still explains the
visible portfolio coherently.

## Bilingual maintenance

`README.md` is the canonical international-facing version.
`README.zh-CN.md` is a companion written for natural Chinese reading.

Maintain factual parity, not sentence-by-sentence translation.

When updating Chinese:

- rewrite naturally;
- keep standard English project/tool names;
- avoid translated corporate jargon;
- avoid inflated self-description;
- preserve the same public evidence and caveats as English.

## Security and protection

Repository-level governance files and CI exist to protect a public identity
asset.

Do not casually remove or weaken:

- branch/ruleset protections;
- PR-based workflow;
- Markdown CI;
- `SECURITY.md`;
- contribution/governance guidance.

For security-sensitive findings, follow [SECURITY.md](SECURITY.md).

## Suggested audit cadence

No fixed calendar schedule is required. Audit on meaningful change rather than
for activity's sake.

Useful triggers include:

- a major project release;
- a selected project becoming inactive/private;
- a meaningful upstream contribution being merged;
- a major shift in research/career direction;
- a change in public academic/contact information;
- a visible mismatch between profile README and pinned repositories.

A lightweight periodic audit every few months is reasonable if the account is
changing quickly.

## Handoff to another AI tool

A new AI maintainer should begin with:

1. [AGENTS.md](AGENTS.md)
2. this file;
3. both profile READMEs;
4. `CHANGELOG.md`;
5. current GitHub account/repository state.

Do not ask the owner to restate facts that can be verified from GitHub.
Do ask before making high-impact editorial, privacy, security, or identity
decisions.
