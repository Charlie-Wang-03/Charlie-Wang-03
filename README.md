# Yichuan Wang

**English** · [简体中文](https://github.com/Charlie-Wang-03/Charlie-Wang-03/blob/main/README.zh-CN.md)

I’m an applied mathematics master’s student at Fudan University. I’m interested in how neural operators approximate solutions to partial differential equations. In my open-source work, I trace mathematical claims back to their sources and build tools to inspect what coding agents do.

## AI for mathematics

- **[AI4Math Chronicle](https://github.com/Charlie-Wang-03/ai4math-chronicle)** — I maintain a bilingual timeline of milestones in mathematical AI. Each entry links to primary sources and records what has been checked. The entry on finite simple groups shows the precise theorem Axiom reports formalizing in Lean. [Browse the timeline](https://charlie-wang-03.github.io/ai4math-chronicle/en/) · [Read the entry](https://charlie-wang-03.github.io/ai4math-chronicle/en/events/axiom-finite-simple-groups-lean/)
- **Creative-Intelligence · upstream contribution** — I added checks to a mathematical discovery workflow so that, on resuming a run, it catches duplicate objects and flags results marked as verified when their archives are missing. [Merged PR #7](https://github.com/DeepMathLLM/Creative-Intelligence/pull/7)
- **[AI4Math Radar](https://github.com/Charlie-Wang-03/ai4math-radar)** — I maintain an AIHOT-derived feed of recent work in mathematical AI. Reports about the same event are grouped so readers can follow the sources behind a story. [Read the feed](https://charlie-wang-03.github.io/ai4math-radar/)

## Tools I build

- **[Sightline](https://github.com/Charlie-Wang-03/dsh-sightline)** — Compare the instructions different coding agents see in the same directory. Sightline reads DeepSeek Harness session events and predicts what Codex and Claude Code would load from their discovery rules. [Runtime evidence test](https://github.com/Charlie-Wang-03/dsh-sightline/blob/main/tests/dsh-observed.integration.test.ts)
- **[Zotero Mirror](https://github.com/Charlie-Wang-03/zotero-mirror)** — A template that mirrors Zotero references, notes and annotations into a private GitHub repository, giving research tools a versioned copy to read. [Validation notes](https://github.com/Charlie-Wang-03/zotero-mirror/blob/main/docs/VALIDATION.md)
- **[SLURM Dashboard](https://github.com/Charlie-Wang-03/slurm-dashboard)** — A self-hosted cluster dashboard for first-time SLURM users. Each view shows the command behind the data, so a student can reproduce a queue or GPU query in a terminal.

## Other upstream contributions

| Project | Contribution |
| --- | --- |
| OpenHands SDK | Unified token usage reporting across two API response formats. [Merged #5029](https://github.com/OpenHands/software-agent-sdk/pull/5029) |
| Harbor | Fixed how evaluation runs report a timeout when the verifier environment fails to start. [Merged #3491](https://github.com/harbor-framework/harbor/pull/3491) |
| AIHOT | Made event grouping and its completion receipt commit in one database transaction. [Merged #161](https://github.com/KKKKhazix/AIHOT/pull/161) |
| Moonshine | Proposed a tool execution journal to prevent accidental replay after an interrupted turn. [Open PR #4](https://github.com/DeepMathLLM/Moonshine/pull/4) |

## Contact

I welcome conversations about agent engineering internships and collaborations on scientific software.

[yichuancharliewang@gmail.com](mailto:yichuancharliewang@gmail.com) · [ORCID](https://orcid.org/0009-0009-3807-6901) · [OpenReview](https://openreview.net/profile?id=~Yichuan_Wang7)
