# Space AI — 天空具身智能与天空算力市场调研项目

## 项目概述

本项目用于系统化调研天空具身智能（Space Embodied AI）、天空算力（Orbital Compute）
及太空AI产业生态。包含调研 prompt、Claude Code skill、多轮调研报告。

## 项目结构

```
space_ai/
├── CLAUDE.md                     # 本文件
├── README.md                     # 项目说明
├── .claude/skills/
│   └── space-ai-research.md      # 天空AI市场调研 Skill
├── prompts/
│   └── research-prompt.md        # 核心调研 Prompt 模板
├── reports/
│   ├── round-1-report.md         # 第一轮调研报告
│   └── round-2-report.md         # 第二轮调研报告
└── .gitignore
```

## Skills

本项目定义以下 Claude Code Skills：

### space-ai-research
- **路径**: `.claude/skills/space-ai-research.md`
- **触发条件**: 用户请求太空AI、轨道算力、卫星智能、太空数据中心等相关调研
- **功能**: 6 维度全景调研（天空具身智能、天空算力、前沿企业、投资生态、政策对比、关键技术）
- **工具**: WebSearch、WebFetch

## 使用方法

### 方式 1: 使用 Skill
```
请使用 space-ai-research skill 进行天空算力市场调研
```

### 方式 2: 直接使用 Prompt
将 `prompts/research-prompt.md` 内容作为 system prompt 使用。

### 方式 3: 单维度调研
```
请调研天空具身智能领域的前沿企业（使用 space-ai-research skill，仅维度3）
```

## 调研迭代流程

1. **R1**: 初始调研 → 产出 round-1-report.md → 识别信息缺口
2. **R2**: 更新 skill 搜索方向 → 补充调研 → 产出 round-2-report.md → 深度优化
3. **持续**: 根据行业动态定期更新

## Git 仓库

- Remote: https://github.com/backyes/space_ai.git
- Branch: main
