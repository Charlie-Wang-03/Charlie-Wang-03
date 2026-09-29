# AGENTS.md

## Purpose

This repository is the special GitHub profile repository for
`Charlie-Wang-03`. Its root `README.md` is rendered on the public GitHub
profile, so changes here affect the owner's public technical identity rather
than only a normal project page.

Treat this repository as a curated public landing page for a developing
Research × AI Engineering × Open Source profile. The goal is not to maximize
the amount of content. The goal is to keep the profile accurate, current,
restrained, useful, and consistent with the owner's real GitHub activity.

This file is the canonical repository-level instruction source for AI tools.
Compatibility files may point here, but they should not duplicate this policy.

## Read this before making changes

Before editing anything substantial:

1. Read the current `README.md`, `README.zh-CN.md`, `CHANGELOG.md`,
   `MAINTENANCE.md`, and relevant governance files.
2. Inspect the current `main` branch, open pull requests, and recent profile
   changes so that new work does not undo accepted decisions.
3. If the task changes portfolio or open-source content, inspect the owner's
   current GitHub account state rather than relying on an old README snapshot.
4. For every candidate project or contribution mentioned publicly, inspect the
   actual repository, README, release state, visibility, and upstream PR state.
5. Prefer current GitHub evidence over memory, old chat context, old profile
   text, or assumptions from repository names.

If a required fact cannot be verified, omit it or mark it conservatively. Do
not fill gaps with plausible-sounding claims.

## Authority and source-of-truth order

Use the following order when resolving decisions:

1. The owner's latest explicit instruction controls editorial intent and
   approval.
2. Current GitHub state controls factual claims: visibility, repository
   ownership, releases, PR status, merge status, project names, and links.
3. The selected project's own current documentation controls its technical
   description.
4. This repository's accepted `main` branch controls profile style,
   structure, and prior maintenance decisions.
5. Old conversations, cached summaries, and historical README text are context,
   not authority.

An explicit editorial preference never permits a factual claim that current
evidence does not support.

## Repository roles

- `README.md` — canonical English public profile.
- `README.zh-CN.md` — Simplified Chinese companion profile.
- `PROFILE.md` — compact structured reference for public technical facts.
- `llms.txt` — lightweight index pointing to the public profile and selected
  project sources.
- `AGENTS.md` — canonical AI maintenance contract.
- `MAINTENANCE.md` — human-readable long-term maintenance playbook.
- `CONTRIBUTING.md` — contribution expectations.
- `SECURITY.md` — security and sensitive-information reporting policy.
- `CODE_OF_CONDUCT.md` — collaboration conduct.
- `CHANGELOG.md` — notable profile/governance changes.
- `.github/` — PR/issue templates, CI, and tool-specific compatibility
  instructions.

## Public-profile content policy

### Identity

Keep the profile grounded in the owner's current career stage.

Prefer language such as:

- interested in;
- exploring;
- current focus;
- public projects;
- open-source contributions;
- research and engineering practice.

Avoid unsupported or inflated titles such as:

- expert;
- architect;
- specialist;
- founder;
- senior researcher;
- production-grade;
- industry-leading.

Do not convert aspirations into achievements.

### Current Focus

Keep this section broad and exploratory. It should summarize a few durable
directions, not track every temporary project or imply premature
specialization.

A profile update is not required every time a short-lived research topic or
tool changes.

### Semantic clarity

Prefer explicit, established domain names when they are factually supported,
for example: Scientific Machine Learning, neural operators, partial
differential equations (PDEs), AI for Science & Mathematics (AI4Science /
AI4Math), AI agents, agent reliability, scientific computing, reproducible
research workflows, developer tooling, and open source.

Use these terms naturally in explanatory prose. Do not repeat phrases solely
for indexing, add unsupported buzzwords, or turn the profile into a keyword
list.

When public technical facts change, keep `PROFILE.md` and `llms.txt`
consistent with the canonical README and linked project sources.

### Selected Projects

The project section is curated, not exhaustive.

Before adding or retaining a project:

- verify that it is public;
- verify that the owner has a meaningful authorship or maintainer relationship;
- read its current README and release/status information;
- prefer projects that add distinct evidence to the public narrative;
- avoid duplicating every pinned repository merely because it is pinned.

Usually a small set of representative projects is better than a catalog.

Do not present a fork, mirror, course copy, temporary experiment, private
archive, or dogfood repository as an original personal project.

### Open-source Contributions

Keep this section compact.

- Prefer one line per upstream project, not one line per PR.
- Group related PRs under the same upstream project.
- Distinguish merged work from open, draft, or abandoned work when the status
  materially affects the claim.
- Do not turn the profile into a PR scoreboard.
- Do not surface contributions whose main purpose is private dogfooding unless
  the owner explicitly decides they belong in the public narrative.

A fork is evidence of a contribution route, not automatically a portfolio
project.

### Tools and technologies

Only list tools that are supported by current work or repeated use. Do not add
future skills, fashionable technologies, or one-off dependencies merely to
increase badge count.

## Bilingual policy

English and Simplified Chinese should remain factually aligned, but they do not
need to be literal translations.

- English is the canonical international-facing profile.
- Chinese should read like natural Chinese written for domestic researchers,
  collaborators, and hiring readers.
- Keep section structure broadly parallel so the two versions are easy to
  maintain.
- When facts change, update both language versions in the same PR.
- Do not translate proper names, project names, package names, or technical
  terms when the English form is clearer or standard.
- Avoid machine-translated phrasing and excessive bilingual repetition.

## Visual policy

Preserve the current polished academic + research/developer portfolio style
unless the owner explicitly asks for a redesign.

Preferred elements:

- a clear hero;
- restrained badges;
- compact tables/cards;
- limited emoji section markers;
- one low-noise profile summary element;
- readable bilingual navigation.

Avoid high-noise profile decorations unless explicitly approved:

- contribution snakes;
- visitor counters;
- trophy walls;
- streak widgets;
- multiple redundant GitHub-stat cards;
- dense skill-badge walls;
- animated role/title claims.

External image/badge services must be non-essential: if they fail, the profile
should still communicate the important information.

## Privacy and confidentiality

This repository is public. Assume every committed byte is permanently public.

Never publish, infer, or summarize from private repositories unless the owner
explicitly approves the exact public disclosure and the disclosed information
is safe to publish.

Do not expose:

- secrets, tokens, cookies, credentials, or private keys;
- private repository content or names merely because an AI connector can see
  them;
- internal hostnames, IP addresses, account identifiers, billing data, or
  private infrastructure details;
- customer/client information;
- unreleased research results or private manuscripts;
- local filesystem paths or machine-specific secrets.

Publicly listed contact information may be retained when it is already an
intentional part of the profile.

## Maintenance triggers

Re-audit the profile when one or more of the following happens:

- a selected project is renamed, archived, made private, or materially changes
  scope;
- a public project reaches a meaningful release or becomes substantially more
  representative than an existing selected project;
- an upstream contribution changes status in a way that alters the public
  claim;
- the owner's academic affiliation, degree status, research direction, contact
  links, or career positioning changes;
- pinned repositories change enough that the profile narrative no longer
  matches the visible portfolio;
- a badge, image, link, or third-party profile widget breaks;
- the owner explicitly requests a portfolio/profile audit.

Do not churn the README for trivial activity.

## Standard change workflow

For non-trivial changes:

1. Start from current `main`.
2. Create a short-lived descriptive branch.
3. Make the smallest coherent change.
4. Update both README languages when public profile facts change.
5. Update `CHANGELOG.md` for notable profile or governance changes.
6. Run or wait for repository CI, especially `Markdown Check`.
7. Open a PR with the factual basis and review focus.
8. Stop for human review before merge unless the owner explicitly authorizes
   the merge in the current interaction.
9. Prefer squash merge.
10. Delete the temporary branch after merge.

The repository currently uses squash merging as the normal merge strategy.
Do not bypass branch/ruleset protections.

## Human approval gates

Human approval is required before:

- changing the public identity/positioning statement;
- adding or removing a selected project for editorial reasons;
- adding a new upstream organization/project to the contribution narrative;
- materially redesigning the visual language;
- changing public contact information;
- publishing information derived from anything private or ambiguous;
- weakening CI, security, repository protection, or governance;
- changing repository visibility or other destructive/high-impact settings.

Routine factual refreshes may be prepared autonomously, but the AI should still
present them in a reviewable PR.

## Validation checklist

Before declaring a profile-maintenance PR ready:

- [ ] Every project link resolves to the intended public repository.
- [ ] Every contribution status is current.
- [ ] No private-only information appears in the diff.
- [ ] English and Chinese facts agree.
- [ ] `PROFILE.md` and `llms.txt` remain consistent with the canonical README.
- [ ] Chinese wording is natural rather than literal machine translation.
- [ ] Claims match the owner's current career stage.
- [ ] Selected projects remain curated rather than exhaustive.
- [ ] Open-source contributions remain compact and grouped by upstream.
- [ ] Existing visual language is preserved unless redesign was requested.
- [ ] Markdown CI passes.
- [ ] `CHANGELOG.md` is updated when appropriate.
- [ ] The PR explains what changed and why.

## Reporting to the owner

After making changes, report:

- what was inspected;
- what changed;
- what was deliberately not changed;
- any facts that remain uncertain;
- CI/PR status;
- the exact point where human review or settings work is required.

Never claim a merge, deletion, protection setting, or other GitHub action was
completed unless the tool result confirms it.
