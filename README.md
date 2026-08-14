<div align="center">

# Wuzhong Yanqiu

### Building reliable systems for capable AI agents

[![Agent Harness](https://img.shields.io/badge/Agent_Harness-18181B?style=flat-square)](https://github.com/wuzhongyanqiu)
[![Agent Training](https://img.shields.io/badge/Agent_Training-0F766E?style=flat-square)](https://github.com/wuzhongyanqiu)
[![Evaluation](https://img.shields.io/badge/Evaluation-B45309?style=flat-square)](https://github.com/wuzhongyanqiu)
[![Memory](https://img.shields.io/badge/Memory_%26_Tool_Use-1D4ED8?style=flat-square)](https://github.com/wuzhongyanqiu)

I focus on the engineering layer between foundation models and dependable agents:
the harnesses that run them, the feedback loops that improve them, and the
evaluations that show whether they actually work.

</div>

---

## Current focus

| Area | What I care about |
| --- | --- |
| **Agent Harness** | Runtime architecture, context management, tool orchestration, permissions, and failure recovery |
| **Agent Training** | Trajectory collection, data curation, feedback signals, post-training, and iterative self-improvement |
| **Evaluation** | Reproducible tasks, process-level traces, quality gates, regression detection, and observability |
| **Memory & Tools** | Long-term memory, retrieval, state management, and reliable interaction with external systems |

```text
task -> agent runtime -> tool calls -> trajectory -> evaluation -> training data -> improved agent
```

## Research agenda

- How harness design changes an agent's effective capability
- How to turn real interaction traces into high-quality training signals
- How process evaluation can catch failures that final-answer metrics miss
- How memory systems can remain useful, inspectable, and controllable over time

## System view

I think about agents as complete learning systems, not isolated model calls.

| Layer | Core questions |
| --- | --- |
| **Environment** | What can the agent observe, change, and verify? |
| **Harness** | How are context, tools, state, budgets, and permissions controlled? |
| **Policy** | How does the model plan, act, reflect, and recover? |
| **Data flywheel** | Which trajectories should become feedback or training data? |
| **Evaluation** | Did the result succeed, and was the process robust enough to trust? |

The goal is a closed loop where every real task can make the system more
measurable, more reliable, and eventually more capable.

## Working principles

```text
Reliable > impressive in a demo
Measured > assumed
Inspectable > opaque
Useful feedback loops > one-off prompts
```

<details>
<summary><strong>中文简介</strong></summary>

我关注大模型到可靠 Agent 之间的工程层：Agent Harness、上下文与工具编排、训练反馈闭环、过程评测、长期记忆和可观测性。希望把真实任务中的运行轨迹转化为可复现的评测和高质量训练信号，让 Agent 不只是在演示中聪明，而是在持续运行中稳定、可控、可改进。

</details>

---

<div align="center">

**Interested in agent infrastructure, training systems, and evaluation.**

</div>
