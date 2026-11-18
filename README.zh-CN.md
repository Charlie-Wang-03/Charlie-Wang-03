# Yichuan Wang

[English](https://github.com/Charlie-Wang-03/Charlie-Wang-03/blob/main/README.md) · **简体中文**

我在复旦大学攻读应用数学硕士，关注神经算子如何逼近偏微分方程的解。我做开源项目时，喜欢追溯一项数学结论的原始证据，也喜欢写工具，弄清编程智能体在运行时究竟做了什么。

## AI 与数学

- **[AI4Math Chronicle](https://github.com/Charlie-Wang-03/ai4math-chronicle)** — 我维护的中英双语时间线，记录 AI 参与数学研究的里程碑。每条记录都给出一手来源和核验进展。例如，有限单群分类条目列出了 Axiom 报告在 Lean 中证明的具体命题。[浏览时间线](https://charlie-wang-03.github.io/ai4math-chronicle/zh-CN/) · [阅读这条记录](https://charlie-wang-03.github.io/ai4math-chronicle/zh-CN/events/axiom-finite-simple-groups-lean/)
- **Creative-Intelligence · 上游贡献** — 我为数学探索工作流补上了恢复检查。中断后继续运行时，程序能识别重复的研究对象，也能发现标为“已验证”却缺失归档的结果。[已合并 PR #7](https://github.com/DeepMathLLM/Creative-Intelligence/pull/7)
- **[AI4Math Radar](https://github.com/Charlie-Wang-03/ai4math-radar)** — 我基于 AIHOT 维护的数学 AI 动态。围绕同一事件的多篇报道归在一起，方便读者沿着来源追踪近期工作。[浏览研究动态](https://charlie-wang-03.github.io/ai4math-radar/)

## 我开发的工具

- **[Sightline](https://github.com/Charlie-Wang-03/dsh-sightline)** — 在同一目录启动不同的编程智能体，它们会读到哪些指令？Sightline 从会话事件中还原 DeepSeek Harness 实际加载的指令，并按各自的发现规则推算 Codex 和 Claude Code 会加载什么。[运行时观测测试](https://github.com/Charlie-Wang-03/dsh-sightline/blob/main/tests/dsh-observed.integration.test.ts)
- **[Zotero Mirror](https://github.com/Charlie-Wang-03/zotero-mirror)** — 把 Zotero 文献条目、笔记和批注同步到私有 GitHub 仓库的模板，让科研工具可以读取带版本记录的副本。[验证记录](https://github.com/Charlie-Wang-03/zotero-mirror/blob/main/docs/VALIDATION.md)
- **[SLURM Dashboard](https://github.com/Charlie-Wang-03/slurm-dashboard)** — 为初次使用 SLURM 的同学开发的自托管集群面板。查看作业队列或 GPU 使用情况时，可以复制页面上的命令，在终端复现查询。

## 其他开源贡献

| 项目 | 我的贡献 |
| --- | --- |
| OpenHands SDK | 统一两种 API 响应格式中的 token 用量统计。[已合并 #5029](https://github.com/OpenHands/software-agent-sdk/pull/5029) |
| Harbor | 修正评测任务的超时归因，使验证环境启动失败时能报告对应的启动超时。[已合并 #3491](https://github.com/harbor-framework/harbor/pull/3491) |
| AIHOT | 将事件归组结果与完成回执放入同一数据库事务，一起提交或回滚。[已合并 #161](https://github.com/KKKKhazix/AIHOT/pull/161) |
| Moonshine | 提出工具执行日志方案，避免会话中断后意外重复执行工具。[在审 PR #4](https://github.com/DeepMathLLM/Moonshine/pull/4) |

## 联系我

欢迎联系我交流 Agent 工程实习机会，或一起开发科研软件。

[yichuancharliewang@gmail.com](mailto:yichuancharliewang@gmail.com) · [ORCID](https://orcid.org/0009-0009-3807-6901) · [OpenReview](https://openreview.net/profile?id=~Yichuan_Wang7)
