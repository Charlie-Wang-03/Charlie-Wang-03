# 👋 Yichuan Wang

## Applied Mathematics × Scientific ML × AI Systems

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=Scientific+Machine+Learning;Agent+Reliability+%26+Infrastructure;Reproducible+Research+Workflows;Open-source+Engineering" alt="Scientific Machine Learning, AI4Science, AI4Math, agent reliability, reproducible research workflows, and open-source engineering" />
</p>

M.S. student in Applied Mathematics · Fudan University

**English** · [简体中文](README.zh-CN.md)

---

## 👨‍💻 About

I am an Applied Mathematics M.S. student at Fudan University. My current interests include Scientific Machine Learning (Scientific ML), neural operators and PDEs, AI for Science & Mathematics (AI4Science / AI4Math), and practical AI systems.

Alongside research, I maintain public projects and contribute upstream to open-source software, with current work spanning AI agents and agent reliability, research-intelligence tooling, reproducible research workflows, scientific computing, and developer tooling.

---

## 🧭 Current Focus

| Area | Exploring |
| :--- | :--- |
| **Scientific ML** | Neural operators, PDEs, and scientific machine learning for physical systems |
| **Agent Engineering** | AI agents, agent reliability, research agents, and developer tooling |
| **Open Source** | Public projects, upstream contributions, and reproducible research workflows |

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

---

## 🚀 Selected Projects

<table>
<tr>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/ai4math-chronicle">AI4Math Chronicle</a></h3>
  <p><strong>A timeline-first, evidence-backed archive of major milestones in AI for Mathematics.</strong></p>
  <p>A continuously maintained bilingual project with a public site, explicit editorial and verification methodology, machine-readable data, and citable releases.</p>
  <p><code>AI4Math</code> · <code>Open Data</code> · <code>Evidence</code> · <code>Astro</code></p>
</td>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/ai4math-radar">AI4Math Radar</a></h3>
  <p><strong>A curated, evidence-aware research-intelligence project for AI for Mathematics.</strong></p>
  <p>Independently maintained and derived from the AIHOT open-source framework; combines an explicit selection policy, structured AI4Math data, deterministic validation, and a static public site. v0.1.0 is the first citable editorial baseline.</p>
  <p><code>AI4Math</code> · <code>Research Intelligence</code> · <code>Evidence</code> · <code>TypeScript</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/dsh-sightline">Sightline</a></h3>
  <p><strong>Compare the workspace instruction surfaces seen by DeepSeek Harness, Codex, and Claude Code.</strong></p>
  <p>A small developer tool that makes cross-agent instruction discovery differences visible, with explicit observed/predicted evidence semantics. The v0.1 release is available on npm and GitHub Releases.</p>
  <p><code>Developer Tools</code> · <code>Coding Agents</code> · <code>DeepSeek Harness</code> · <code>TypeScript</code></p>
</td>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/zotero-mirror">Zotero Mirror</a></h3>
  <p><strong>A versioned Zotero library for AI-assisted research.</strong></p>
  <p>A reusable template syncs references, notes and annotations into a private GitHub repository. Zotero remains the source of record.</p>
  <p><code>Zotero</code> · <code>Research Tools</code> · <code>GitHub Actions</code> · <code>Python</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/slurm-dashboard">SLURM Dashboard</a></h3>
  <p><strong>A teaching dashboard for new SLURM users.</strong></p>
  <p>Cluster and GPU views show the shell commands behind each result so users can reproduce a query in their own terminal.</p>
  <p><code>SLURM</code> · <code>GPU Monitoring</code> · <code>Scientific Computing</code> · <code>Python</code></p>
</td>
<td width="50%" valign="top">
  <h3><a href="https://github.com/DeepMathLLM/Creative-Intelligence/pull/7">Creative-Intelligence · Upstream contribution</a></h3>
  <p><strong>Recovery checks for mathematical discovery runs.</strong></p>
  <p>My merged contribution checks for duplicate research objects and flags verified results whose archives are missing when a run resumes.</p>
  <p><code>AI4Math</code> · <code>Research Agents</code> · <code>State Validation</code> · <code>Open Source</code></p>
</td>
</tr>
</table>

---

## 🤝 Open-source Contributions

- **OpenHands SDK · Model usage tracking** — Two LLM APIs report token counts under different field names. I replaced four separate lookups with one typed adapter, so metrics, traces and logs use the same count for each model call. [Merged #5029](https://github.com/OpenHands/software-agent-sdk/pull/5029)
- **Creative-Intelligence · Research agent recovery** — A resumed discovery run could accept a previously tried name or trust a result whose archive had changed. I added name and file-integrity checks. The runner now flags both cases before work continues. [Merged #7](https://github.com/DeepMathLLM/Creative-Intelligence/pull/7)
- **Harbor · Agent evaluation** — Evaluation reports could blame the verifier for a timeout before it had started. I fixed the error handling and added regression tests for both phases, so the report tells engineers whether to investigate environment startup or verification. [Merged #3491](https://github.com/harbor-framework/harbor/pull/3491)
- **AIHOT · Reliable LLM retries** — An interruption could save an event grouping while leaving the model call marked incomplete. I made both writes commit together. Fault-injection tests showed retries reused the saved response without a second model call. [Merged #161](https://github.com/KKKKhazix/AIHOT/pull/161)
- **Moonshine · Tool execution after a crash** — A tool can finish just before an agent crashes, leaving its outcome unknown on restart. I proposed recording each call before dispatch and blocking further calls when the outcome is uncertain, to avoid repeating an external action. [Open #4](https://github.com/DeepMathLLM/Moonshine/pull/4)

---

## 🔬 Research Interests

- Scientific Machine Learning
- Neural Operators & Partial Differential Equations (PDEs)
- AI for Science & Mathematics (AI4Science / AI4Math)
- Learning-based methods for physical systems

---

## 🎓 Academic Profiles

[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-3807-6901)
[![OpenReview](https://img.shields.io/badge/OpenReview-8C1B13?style=for-the-badge)](https://openreview.net/profile?id=~Yichuan_Wang7)

---

## 📫 Connect

Open to agent engineering internships and collaborations on scientific software.

[![Email](https://img.shields.io/badge/Email-yichuancharliewang%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yichuancharliewang@gmail.com)

---

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Charlie-Wang-03&theme=github_dark" alt="Yichuan Wang, Charlie-Wang-03 GitHub profile summary" />
</p>
