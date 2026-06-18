# Space AI — 天空具身智能与天空算力市场调研

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 概述

本项目专注于**天空具身智能（Space Embodied AI）**与**天空算力（Orbital Compute）**两大前沿领域的市场调研，覆盖以下维度：

| 维度 | 描述 |
|------|------|
| 🛰️ 天空具身智能 | 卫星自主决策、在轨机器人、太空AI推理 |
| 💻 天空算力 | 星载芯片、低轨算力星座、太空数据中心 |
| 🏢 前沿企业 | 国内外主要玩家的技术路线与竞争格局 |
| 💰 投资生态 | 融资趋势、VC布局、政府基金、并购动态 |
| 🌍 国内外政策 | 中美欧日印太空AI政策与竞争态势 |
| 🔬 关键技术 | 抗辐射芯片、激光通信、能源系统、量子应用 |

## 项目结构

```
space_ai/
├── CLAUDE.md                     # Claude Code 项目配置
├── README.md                     # 本文件
├── .claude/skills/
│   └── space-ai-research.md      # 天空AI市场调研 Skill
├── prompts/
│   └── research-prompt.md        # 核心调研 Prompt（6维度详细拆解）
├── reports/
│   ├── round-1-report.md         # 第一轮调研报告
│   └── round-2-report.md         # 第二轮调研报告
└── .gitignore
```

## 快速开始

### 前置条件
- [Claude Code](https://claude.ai/code) CLI 已安装
- 本仓库已 clone 到本地

### 使用 Skill 进行调研

```bash
# 在项目目录下启动 Claude Code
cd space_ai
claude
```

然后在 Claude Code 会话中：

```
请使用 space-ai-research skill 进行天空算力市场调研
```

或针对单维度：

```
请调研天空具身智能的国内外政策对比（使用 space-ai-research skill，维度5）
```

## 调研维度详情

### 1. 天空具身智能（Space Embodied AI）
在太空环境中运行、具备感知-决策-执行闭环的 AI 系统。包括卫星自主导航、在轨机器人操作、空间站AI助手、深空探测器自主决策。

### 2. 天空算力（Orbital Compute）
部署于地球轨道或深空的计算资源。包括星载边缘计算、低轨算力星座、太空数据中心等概念。

### 3. 前沿企业图谱
- **国际**: SpaceX/Starlink、Amazon Kuiper、Northrop Grumman、Astroscale、LeoCloud、Loft Orbital、Ramon.Space、Axiom Space、Lonestar、Redwire
- **国内**: 中国星网、银河航天、长光卫星、航天科工/科技、国星宇航、航天宏图

### 4. 投资生态
Lux Capital、Space Capital、Seraphim Space 等头部 VC 布局，各国政府/国防预算投入，SPAC/IPO 动态。

### 5. 国内外政策
美国 Space Policy Directive、ESA AI in Space、中国航天强国战略、卫星互联网新基建等。

### 6. 关键技术
抗辐射 AI 芯片、星载 AI 框架、星间激光通信、太空能源与热管理、软件定义卫星、量子太空应用。

## 迭代记录

| 轮次 | 日期 | 更新内容 |
|------|------|----------|
| R1 | TBD | 初始调研 |
| R2 | TBD | 基于R1发现的补充与深化 |

## 贡献

本项目由 backyes 维护。欢迎提交 Issue 或 PR 补充调研方向和数据。

## License

MIT License
