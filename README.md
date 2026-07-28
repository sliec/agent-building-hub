# AI Agent 搭建共学指南

> 本指南系统整理了从零开始构建 AI Agent 的优质开源资源、工具与学习路线。无论你是刚接触 Agent 概念的新手，还是希望深入工程实践的进阶开发者，都能在这里找到适合自己的学习路径。

---

## 目录

- [一、系统教程（从零开始）](#一系统教程从零开始)
- [二、开发指南与路线图](#二开发指南与路线图)
- [三、框架选型与生态](#三框架选型与生态)
- [四、框架实战](#四框架实战)
- [五、实用 Skills 工具](#五实用-skills-工具)
- [六、推荐学习路径（4 周计划）](#六推荐学习路径4-周计划)

---

## 一、系统教程（从零开始）

### 1. datawhalechina/hello-agents ⭐ 69k stars

**《从零开始构建智能体》**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/datawhalechina/hello-agents |
| 语言 | 中文 |
| 章节 | 16 章 |
| 配套资源 | 完整代码 + 共创项目 |

**核心内容：**

- 从零理解 Agent 的基本概念与工作原理
- 16 章系统覆盖 Agent 从理论到实践的全过程
- 配套代码仓库，边学边练
- 共创项目支持社区协作学习

**适合人群：** 🟢 初学者 / 🟡 中级开发者

> 这是入门 Agent 的首选教程，章节循序渐进，社区活跃度高，适合跟着 Datawhale 的开源学习计划一起推进。

---

### 2. bojieli/ai-agent-book ⭐ ~10k stars

**《深入理解 AI Agent：设计原理与工程实践》**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/bojieli/ai-agent-book |
| 在线阅读 | https://bojieli.github.io/ai-agent-book/ |
| 作者 | 李博杰（华为天才少年） |
| 章节 | 10 章 |
| 实验 | 92 个配套实验（70+ 可独立运行） |
| 语言 | 支持 8 种语言 |

**核心公式：** `Agent = LLM + Context + Tools`

**各章内容：**

1. **Agent 基础** — 什么是 Agent，核心概念与架构
2. **Context 工程** — 上下文管理与优化
3. **用户记忆与知识库** — 长期记忆、知识检索与管理
4. **工具（MCP）** — 工具调用、MCP 协议与集成
5. **Coding Agent** — 代码生成与执行
6. **Agent 评估** — 系统评估与测试方法
7. **模型后训练** — Fine-tuning 与对齐
8. **持续演化** — Agent 的自我改进机制
9. **多模态交互** — 视觉、语音等多模态能力
10. **多 Agent 协作** — Multi-Agent 系统设计

**适合人群：** 🟢 初学者 / 🟡 中级 / 🔴 高级开发者

> 这本书是目前最系统的 Agent 工程教材，作者有深厚的工程背景。92 个实验中有 70+ 可以独立运行，非常适合动手实践。强烈推荐配合 hello-agents 一起学习。

---

## 二、开发指南与路线图

### 3. adongwanai/AgentGuide ⭐ 7.4k stars

**AI Agent 开发指南**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/adongwanai/AgentGuide |
| 在线阅读 | https://adongwanai.github.io/AgentGuide |

**核心内容：**

- LangGraph 实战指南
- 高级 RAG 技术
- Agent 开发全流程

**适合人群：** 🟡 中级 / 🔴 高级开发者

> 偏实战导向，适合已经了解基本概念、想要动手用 LangGraph 搭建 Agent 的开发者。

---

### 4. datawhalechina/Agent-Learning-Hub ⭐ 5.9k stars

**AI Agent 学习路线与资料库**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/datawhalechina/Agent-Learning-Hub |

**核心内容：**

- 系统化的 Agent 学习路线图
- 分类整理的学习资料索引
- 社区学习路径推荐

**适合人群：** 🟢 初学者 / 🟡 中级开发者

> 如果你不确定从哪里开始，这个仓库提供了清晰的学习路线，帮你规划学习顺序。

---

## 三、框架选型与生态

### 5. kaushikb11/awesome-llm-agents ⭐ 1.5k stars

**Curated List of LLM Agent Frameworks**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/kaushikb11/awesome-llm-agents |

**核心内容：**

- 精选的 LLM Agent 框架列表
- 框架特性对比
- 社区评价与推荐

**适合人群：** 🟡 中级 / 🔴 高级开发者

---

### 6. Vincentwei1021/awesome-ai-agent-frameworks

**中文框架选型指南**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/Vincentwei1021/awesome-ai-agent-frameworks |

**核心内容：**

- 覆盖主流框架：Scion、AutoGen、CrewAI、LangGraph、MetaGPT、Dify、Coze
- 框架对比分析
- 选型决策树（帮助你快速选择最适合的框架）

**适合人群：** 🟡 中级开发者（正在做技术选型的团队）

> 如果你需要在项目中选择 Agent 框架，这个仓库的决策树能帮你快速定位。

---

### 7. WangRongsheng/awesome-LLM-resources ⭐ 8.8k stars

**全世界最好的 LLM 资料总结**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/WangRongsheng/awesome-LLM-resources |

**核心内容：**

- 全面的 LLM 资料索引
- Agent 板块覆盖非常全面
- 持续更新

**适合人群：** 🟢 初学者 / 🟡 中级 / 🔴 高级（所有人）

> 作为一个大型资料库，可以按需查阅，不必全部阅读。重点关注 Agent 相关板块。

---

## 四、框架实战

### 8. HKUDS/AutoAgent ⭐ 9.5k stars

**Fully-Automated Zero-Code LLM Agent Framework**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/HKUDS/AutoAgent |
| 来源 | 香港大学 |

**核心内容：**

- 全自动、零代码的 Agent 构建框架
- 学术级研究与工程级实现结合
- 开箱即用的 Agent 系统

**适合人群：** 🟡 中级 / 🔴 高级开发者

> 港大出品，适合想快速搭建完整 Agent 系统、或研究 Multi-Agent 架构的开发者。

---

## 五、实用 Skills 工具

### 9. yizhiyanhua-ai/fireworks-tech-graph

**12 种视觉风格画架构图的 Agent Skill**

| 属性 | 详情 |
|------|------|
| GitHub | https://github.com/yizhiyanhua-ai/fireworks-tech-graph |
| 输出格式 | SVG、PNG、GIF、交互式 HTML |

**支持的 12 种视觉风格：**

1. Flat Icon — 扁平图标风格
2. Dark Terminal — 暗色终端风格
3. Blueprint — 蓝图风格
4. Notion Clean — Notion 简洁风格
5. Glassmorphism — 玻璃拟态风格
6. Claude Official — Claude 官方风格
7. OpenAI Official — OpenAI 官方风格
8. Dark Luxury — 暗色奢华风格
9. C4 Review Canvas — C4 架构评审画布
10. Cloud Fabric — 云架构织物风格
11. Event Transit — 事件流风格
12. Ops Pulse — 运维脉冲风格

**支持的 14 种图表类型：** 系统架构图、流程图、时序图、部署图、网络拓扑图、数据流图等。

**适合人群：** 🟢 初学者 / 🟡 中级 / 🔴 高级（所有人）

> 非常实用的工具，画架构图时直接调用，支持多种输出格式和风格，特别适合做技术分享和文档配图。

---

## 六、推荐学习路径（4 周计划）

以下是一份推荐的 4 周学习计划，每周约投入 5-8 小时：

### 📅 第一周：打基础

**目标：** 建立 Agent 基本概念，理解核心架构

| 学习内容 | 资源 | 预计时间 |
|---------|------|---------|
| hello-agents 第 1-5 章 | [hello-agents](https://github.com/datawhalechina/hello-agents) | 3-4 小时 |
| ai-agent-book 第 1-2 章 | [ai-agent-book](https://github.com/bojieli/ai-agent-book) | 2-3 小时 |
| 浏览 Agent-Learning-Hub 路线图 | [Agent-Learning-Hub](https://github.com/datawhalechina/Agent-Learning-Hub) | 1 小时 |

**本周产出：** 用自己的话写一篇 Agent 概念笔记，画出 Agent 基本架构图（可用 fireworks-tech-graph）

---

### 📅 第二周：深入核心

**目标：** 掌握 Context 工程、记忆系统、工具调用

| 学习内容 | 资源 | 预计时间 |
|---------|------|---------|
| hello-agents 第 6-10 章 | [hello-agents](https://github.com/datawhalechina/hello-agents) | 3-4 小时 |
| ai-agent-book 第 3-5 章（重点：Context、Memory、Tools） | [ai-agent-book](https://github.com/bojieli/ai-agent-book) | 3-4 小时 |
| 运行 ai-agent-book 第 3-5 章配套实验 | 同上 | 2-3 小时 |

**本周产出：** 完成至少 3 个实验，整理 Context Engineering 和 MCP 工具调用的学习笔记

---

### 📅 第三周：动手实践

**目标：** 通过实验加深理解，学会用可视化工具表达架构

| 学习内容 | 资源 | 预计时间 |
|---------|------|---------|
| ai-agent-book 第 6-8 章实验（Agent 评估、模型后训练、持续演化） | [ai-agent-book](https://github.com/bojieli/ai-agent-book) | 4-5 小时 |
| 学习使用 fireworks-tech-graph 画架构图 | [fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) | 1-2 小时 |
| 浏览框架选型资料，了解主流框架差异 | [awesome-ai-agent-frameworks](https://github.com/Vincentwei1021/awesome-ai-agent-frameworks) | 1-2 小时 |

**本周产出：** 完成 2-3 个进阶实验，用 fireworks-tech-graph 画出你的 Agent 系统设计图

---

### 📅 第四周：进阶与项目

**目标：** 探索多模态与 Multi-Agent，搭建自己的 Agent 项目

| 学习内容 | 资源 | 预计时间 |
|---------|------|---------|
| ai-agent-book 第 9-10 章（多模态交互、多 Agent 协作） | [ai-agent-book](https://github.com/bojieli/ai-agent-book) | 2-3 小时 |
| 学习 AutoAgent 框架 | [AutoAgent](https://github.com/HKUDS/AutoAgent) | 2-3 小时 |
| **搭建自己的 Agent 项目** | 自选框架 + 参考资料 | 3-5 小时 |

**本周产出：** 完成一个完整的 Agent 项目 demo，在社区做分享

---

## 资源速查表

| # | 项目 | Stars | 难度 | 类型 |
|---|------|-------|------|------|
| 1 | [hello-agents](https://github.com/datawhalechina/hello-agents) | 69k | 🟢 入门 | 系统教程 |
| 2 | [ai-agent-book](https://github.com/bojieli/ai-agent-book) | ~10k | 🟢🟡🔴 全级 | 系统教程+实验 |
| 3 | [AgentGuide](https://github.com/adongwanai/AgentGuide) | 7.4k | 🟡🔴 中高级 | 开发指南 |
| 4 | [Agent-Learning-Hub](https://github.com/datawhalechina/Agent-Learning-Hub) | 5.9k | 🟢🟡 入门中级 | 学习路线 |
| 5 | [awesome-llm-agents](https://github.com/kaushikb11/awesome-llm-agents) | 1.5k | 🟡🔴 中高级 | 框架列表 |
| 6 | [awesome-ai-agent-frameworks](https://github.com/Vincentwei1021/awesome-ai-agent-frameworks) | — | 🟡 中级 | 框架选型 |
| 7 | [awesome-LLM-resources](https://github.com/WangRongsheng/awesome-LLM-resources) | 8.8k | 全级 | 资料库 |
| 8 | [AutoAgent](https://github.com/HKUDS/AutoAgent) | 9.5k | 🟡🔴 中高级 | 框架实战 |
| 9 | [fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) | — | 全级 | 可视化工具 |

---

## 共学建议

1. **结伴学习**：2-3 人一组，每周同步进度、讨论疑问
2. **输出驱动**：每周产出一篇笔记或一个 demo，比纯阅读有效得多
3. **善用实验**：ai-agent-book 的 92 个实验是核心资产，至少完成 10 个
4. **框架选型先调研**：在开始项目前，用 awesome-ai-agent-frameworks 的决策树确定框架
5. **社区分享**：第四周的项目建议在社区做一次 Demo Day，互相学习

---

*持续更新中，欢迎提交 PR 补充优质资源！*

---

## 七、FDE（前沿部署工程师）

FDE = **Forward Deployed Engineer**，2026 年硅谷 AI 圈最火的新职业方向。核心使命是把 AI 从实验室搬到真实业务场景落地——充当顾问、工程师和产品经理三合一的「跨界翻译者」。

灵感来源于 Palantir 的 Delta 角色，OpenAI、Anthropic、Scale AI 等公司都在大量招聘 FDE。

### 学习资源

| # | 项目 | Stars | 说明 |
|---|------|-------|------|
| 1 | [Awesome-FDE-Roadmap](https://github.com/pierpaolo28/Awesome-FDE-Roadmap) | 666 | 最全面的 FDE 路线图：AI Agents + 企业数据架构 + 战略咨询 |
| 2 | [FDEOps](https://github.com/suboss87/FDEOps) | 241 | FDE 第二大脑：6 大领域 35 项技能，配合 AI coding agent 使用 |
| 3 | [Awesome-FDE](https://github.com/libaice/Awesome-FDE) | 92 | FDE 资源/公司/技能精选列表 |
| 4 | [FDE Material](https://github.com/weissmanntobi-del/Forward_Deployed_Engineer_Material) | 44 | FDE 实战材料合集 |
| 5 | [前线部署工程指南](https://github.com/yeasy/forward_deployed_engineering_guide) | 34 | 中文最佳实践指南 |
| 6 | [OpenFDE](https://github.com/OpenFDEAI/OpenFDE) | 25 | FDE 开放知识社区，配套网站 open-fde.com |
| 7 | [FDE Book](https://github.com/dawei008/fde-book) | 15 | OpenBook Vol II：FDE 落地工程学 |
| 8 | [learn-ai](https://github.com/itshen/learn-ai) | 123 | AI 产品经理培训：大模型原理 → 上下文工程 → Agent 设计 → 成本优化，41 页交互式幻灯片 |

### FDE 核心能力模型



**推荐学习顺序**：Awesome-FDE-Roadmap（看全景）→ FDEOps（建技能框架）→ learn-ai（补 AI 工程化基础）→ FDE Book + 实战材料（深入落地）

---

## 相关项目

| 项目 | 说明 |
|---|---|
| [shared-files](https://github.com/sliec/shared-files) | 20 个 Agent Skills 同步中心，一行命令全平台拉齐 |
| [sliec.github.io](https://sliec.github.io/) | 个人技术博客与资源导航 |

---

<p align="center">
  <sub>Star 数为整理时的近似值，以 GitHub 实时数据为准</sub>
</p>
