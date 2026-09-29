# 👋 Yichuan Wang

## 应用数学 × 科学机器学习 × AI 系统

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=Scientific+Machine+Learning;Agent+Reliability+%26+Infrastructure;Reproducible+Research+Workflows;Open-source+Engineering" alt="Current interests" />
</p>

复旦大学 · 应用数学硕士研究生

[English](README.md) · **简体中文**

---

## 👨‍💻 关于我

我目前在复旦大学应用数学系攻读硕士，主要关注科学机器学习（Scientific Machine Learning）、神经算子与 PDE，以及 AI for Science & Mathematics（AI4Science / AI4Math）等方向，也在探索面向科研与工程场景的实用 AI 系统。除科研外，我持续维护公开项目，并参与自己实际使用的开源软件上游贡献，目前的实践涉及 AI Agent 与可靠性、可复现科研工作流、科学计算和开发工具。

---

## 🧭 近期关注

| 方向 | 正在探索 |
| :--- | :--- |
| **科学机器学习** | 神经算子、PDE，以及面向物理系统的科学机器学习方法 |
| **Agent 工程** | AI Agent、Agent 可靠性、科研 Agent 与开发工具 |
| **开源实践** | 公开项目、上游贡献与可复现科研工作流 |

---

## 🛠️ 常用工具与技术

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

---

## 🚀 部分公开项目

<table>
<tr>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/ai4math-chronicle">AI4Math Chronicle</a></h3>
  <p><strong>一个以时间线为核心、基于证据的 AI for Mathematics 重大进展档案。</strong></p>
  <p>这是一个持续维护的中英双语项目，包含公开网站、明确的编辑与核验方法、机器可读数据，以及可引用的版本快照。</p>
  <p><code>AI4Math</code> · <code>开放数据</code> · <code>证据驱动</code> · <code>Astro</code></p>
</td>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/agentic-simulation-lab">Agentic Simulation Lab</a></h3>
  <p><strong>尝试把工程仿真整理成由 Agent 编排、可复现并带有明确物理验证的工作流。</strong></p>
  <p>这是一个围绕 Ansys 的公开实验型项目，重点不是替代求解器，而是把仿真过程、验证依据和结果证据组织得更清楚、更容易复现。仓库中包含真实求解器结果与结构化验证信息。</p>
  <p><code>科学计算</code> · <code>AI Agent</code> · <code>工程仿真</code> · <code>可复现性</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/dsh-sightline">Sightline</a></h3>
  <p><strong>比较 DeepSeek Harness、Codex 与 Claude Code 在同一工作区中看到的指令来源。</strong></p>
  <p>这是一个小型开发者工具，用于把不同 Coding Agent 的指令发现差异显式展示出来，并区分真实观测与规则推断。v0.1 已发布到 npm 和 GitHub Releases。</p>
  <p><code>开发工具</code> · <code>Coding Agent</code> · <code>DeepSeek Harness</code> · <code>TypeScript</code></p>
</td>
<td width="50%" valign="top">
  <h3><a href="https://github.com/Charlie-Wang-03/jev-testbench">jev-testbench</a></h3>
  <p><strong>一个用来测试「类型化概率决策原语」的可审计实验台。</strong></p>
  <p>项目通过只追加的证据记录和预注册实验测量 TypeSafe Jev，并冻结了 v0.1 证据版本。主要结果是一个负结果，仓库将它如实保留，而不是包装成预设成功。</p>
  <p><code>Agentic Engineering</code> · <code>评估</code> · <code>可复现性</code> · <code>Python</code></p>
</td>
</tr>
</table>

---

## 🤝 开源贡献

- **[DeepMathLLM / Creative-Intelligence](https://github.com/DeepMathLLM/Creative-Intelligence)** — 已合并工作主要涉及确定性回归/集成测试、可恢复工作流的输入溯源和生命周期完整性；进一步的核验与 controller 加固仍在评审中。
- **[DeepMathLLM / Moonshine](https://github.com/DeepMathLLM/Moonshine)** — [开放中的 PR](https://github.com/DeepMathLLM/Moonshine/pull/4)，围绕工具执行日志与中断恢复提升 runtime 的崩溃安全性。
- **[OpenHands / software-agent-sdk](https://github.com/OpenHands/software-agent-sdk)** — [已合并 PR #5029](https://github.com/OpenHands/software-agent-sdk/pull/5029)，通过 typed adapter 统一 LLM usage telemetry 的不同数据形态。
- **[mcp-migrate](https://github.com/dheerajjha/mcp-migrate)** — [已合并 PR #279](https://github.com/dheerajjha/mcp-migrate/pull/279)，修复 Python fixer 在注释迁移后可能留下空函数体的问题，并补充相应回归覆盖。

---

## 🔬 研究兴趣

- 科学机器学习
- 神经算子与偏微分方程（PDE）
- AI for Science & Mathematics（AI4Science / AI4Math）
- 面向物理系统的机器学习方法

---

## 🎓 学术主页

[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-3807-6901)
[![OpenReview](https://img.shields.io/badge/OpenReview-8C1B13?style=for-the-badge)](https://openreview.net/profile?id=~Yichuan_Wang7)

---

## 📫 联系方式

欢迎围绕科研、开源项目和 AI 工程实践交流。

[![Email](https://img.shields.io/badge/Email-YichuanCharlieWang%40outlook.com-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:YichuanCharlieWang@outlook.com)

---

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Charlie-Wang-03&theme=github_dark" alt="Charlie-Wang-03 GitHub profile summary" />
</p>
