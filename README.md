<div align="center">

<img src="./assets/superagent-hero.svg" width="100%" alt="wuzhongyanqiu · Super-Agent Architecture">

</div>

<br/>

## Super-Agent · 个人科研与 AI-Native 工程基座

> **Design Principle** — 把多模型 Harness、隔离沙箱、可复用 Skill、自动化工作流与实时运行态观测收口到一套**可迁移、零敏感泄漏、可一键复刻**的 Super-Agent 控制面。

---

### 01 · 核心架构拼图

| 模块 | 仓库 | 定位与能力 |
| :--- | :--- | :--- |
| **Control Plane** | [`advanced-research-control`](https://github.com/wuzhongyanqiu/advanced-research-control) | 研究运维总控台：Git 同步调度、项目全景、调用统计（7d/30d/模型细分）、资源检索 API 与便携环境引导脚本 |
| **Multi-Agent Sandbox** | [`DS-Bot`](https://github.com/wuzhongyanqiu/DS-Bot) | 基于 DeepSeek Harness 的多 Bot 协作与密码隔离实验空间，支持隔离 Bot 间群聊、受控工具授权与人设自治 |
| **Creator & Media Kit** | [`open-creator-toolbox`](https://github.com/wuzhongyanqiu/open-creator-toolbox) · [`ai-video-kit`](https://github.com/wuzhongyanqiu/ai-video-kit) | 音视频抽帧/字幕提取、素材生图（Image 2.5）、3D 草模清理与宣发视频自动化管线 |
| **Intelligence & Radar** | [`llm-landscape`](https://github.com/wuzhongyanqiu/llm-landscape) · [`dsh-ecosystem-dashboard`](https://github.com/wuzhongyanqiu/dsh-ecosystem-dashboard) | 模型能力雷达、Harness 生态观测与前沿研究追踪 |

---

### 02 · 一键复刻环境（Fresh Machine Bootstrap）

在任意新机器上，只需拉取总控仓库即可同步公开基建、共享 Skill 与工作习惯（**自动隔离并跳过公司内部敏感仓库与密钥文件**）：

```bash
git clone https://github.com/wuzhongyanqiu/advanced-research-control.git sync-controller
cd sync-controller
npm run bootstrap
```

`npm run bootstrap` 会自动完成：
1. 拉取并快进同步公开/个人常用仓库（`DS-Bot`、`open-creator-toolbox`、`llm-landscape`、`dsh-ecosystem-dashboard`、`ai-video-kit`）；
2. 将共享 Skills 软链到 `~/.codex/skills` 与 `~/.claude/skills`；
3. 从 `.env.example` 生成脱敏 `.env` 模板（绝不覆盖已有密钥）；
4. 编译并启动本地控制面板（`http://127.0.0.1:4310`）。

---

### 03 · Aesthetic Intelligence · 审美与泛化

我依然在持续验证一个研究直觉：**多样任务经验决定智能的下限，而审美判断（结构、比例、简洁与情境适切性）决定了系统能否跨任务主动取舍。**

<div align="center">
  <sub>Built for autonomous leverage · Keep secrets local, keep workflows portable.</sub>
</div>
