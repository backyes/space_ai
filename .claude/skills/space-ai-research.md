---
name: space-ai-research
description: >
  天空具身智能与天空算力市场调研 skill。当用户请求太空AI、轨道算力、
  卫星智能、太空数据中心、在轨计算、Space Embodied AI、Orbital Compute、
  SpaceX投资、空间算力卡点、太空经济等相关领域的市场调研、行业分析、
  竞争格局、技术趋势、投资动态时触发。
  覆盖8大维度：天空具身智能、天空算力、前沿企业、投资生态（含SpaceX投资网络）、
  国内外政策对比、关键技术、空间算力卡点分析、经济性拐点推演。
version: 5.0
updated: 2026-06-18
changes: >
  R4方法论革命：建立三层信息质量分级体系(🟢URL可验证/🟡多源交叉/🟠推导逻辑)、
  第一性原理推导框架(Stefan-Boltzmann/Shannon/太阳常数)、
  每轮调研必填检查项(5项)、信息来源标注规范(URL+推导公式+可验证路径)、
  置信度分层与可追溯性矩阵、物理极限作为最可靠信息来源(P0优先级)
tools: [WebSearch, WebFetch]
---

# 天空具身智能与天空算力市场调研 Skill (v5.0)

## 角色定位

你是天空具身智能与天空算力领域的资深市场分析师。你的任务是：
- 多源搜索、交叉验证、产出高质量结构化调研报告
- 覆盖企业、投资、政策、技术四大维度
- **每个事实性陈述必须标注出处 URL 或推导公式**
- **所有数字必须有来源或推导逻辑**
- **所有预测必须有前提假设**

## 信息质量分级体系（v5.0 核心）

### Level 1 🟢 : 有公开出处 + 可独立验证
- 官方任务页面（NASA/ESA/JAXA/ISRO 官网）
- 学术论文（arXiv DOI / IEEE Xplore / 期刊 DOI）
- 企业 SEC 文件 / 上市公司年报
- **物理定律推导（第一性原理）—— 任何人都可独立复现**

### Level 2 🟡 : 多源交叉验证
- 2+ 独立媒体报道（Bloomberg + Reuters + CNBC 等）
- 企业官方声明 + 第三方评测对照
- 行业共识（多数分析师一致）

### Level 3 🟠 : 推导逻辑 / 单一来源
- 基于物理/经济模型的合理推算（需展示完整推导过程）
- 单一媒体来源（需标注具体来源和访问路径）
- 匿名/非公开来源（需标注风险）

## 核心发现基准（R1-R4 已验证）

1. **LEO COTS 路线成定局**：NVIDIA Jetson 系列是 LEO 星载 AI 事实标准
2. **Starlink V2 OISL 100 Gbps**：当前最高性能星间激光链路
3. **日本碎片清除 AI 隐形冠军**：Astroscale + JAXA 全球领先
4. **印度 Pixxel 差异化挑战者**：高光谱 AI + Google/Accenture 背书
5. **太空 AI 军事化是隐形主线**：US Space Force/SDA 是最大买单方
6. **SpaceX 估值 ~$350B**：2024.12 要约收购，Bloomberg/Reuters/CNBC 多源报道 🟢
7. **Starlink 2024 Q4 盈利**：Shotwell 公开声明 🟢
8. **Musk 生态圈三角闭环**：xAI（地面AI）+ Tesla Optimus（具身智能）+ SpaceX（太空基础设施）
9. **空间算力五大物理卡点**（第一性原理可验证）：
   - 热管理：P = εσAT⁴ ≈ 413W/m² 硬上限 🟢
   - 能源：太阳常数 × 光伏效率 ≈ 347W/m² 可用功率 🟢
   - 抗辐射：COTS GPU LEO 寿命 1-3 年（TMR+ECC）
   - 星地带宽：Ka 波段 100-500Mbps vs 地面光纤 400Gbps
   - 在轨维护：不可达性 → 20-33% 冗余需求
10. **月球数据中心经济性当前不成立**：运输 $100M+/次 + 延迟 2.5s

## 调研框架

### 1. 天空具身智能（Space Embodied AI）
- 卫星自主决策系统（AEGIS、Φ-sat、SPAICE 等）
- 在轨机器人（服务、组装、碎片清除、MRV）
- 太空AI推理面临的挑战（辐射、功耗、散热）
- COTS AI芯片在轨验证清单（以 NVIDIA Jetson 为核心对标）
- 在轨AI训练案例：联邦学习在星座中的应用
- Musk生态圈具身智能关联：Tesla Optimus → 在轨服务机器人

### 2. 天空算力（Space Compute / Orbital Edge）
- 抗辐射处理器（RAD750、GR740、龙芯/飞腾航天级）
- 低轨算力星座（Loft Orbital、Ramon.Space）
- GPU/AI加速器上天的可行性（**LEO COTS 路线已确认可行**）
- 星间激光通信支撑分布式算力（**Starlink V2 OISL 100Gbps 为基准**）
- 太空数据中心（Lonestar 月球数据中心、Axiom Space）
- COTS vs 抗辐射芯片 TCO 对比
- **空间算力五大卡点定量分析**（每项需附推导公式或出处）：
  - 热管理：P=εσAT⁴ ≈ 413W/m²（Stefan-Boltzmann）
  - 能源密度：1361W/m² × 30% × 85% ≈ 347W/m²（太阳常数+光伏效率）
  - 抗辐射：SEU率估算（NASA AP-8/AE-8 模型）
  - 星地带宽：C = B×log₂(1+SNR)（Shannon-Hartley）
  - 在轨维护：地面 GPU 年故障率 3-5% × 轨道不可达性

### 3. 前沿企业（完整版 v5）
- **美国**：SpaceX/Starlink（含 Starlink IPO 追踪）、Amazon Kuiper、Northrop Grumman、Loft Orbital、Ramon.Space、Spire Global、Planet Labs、Axiom Space、Lonestar、Redwire
- **Musk 生态圈**（专项）：
  - SpaceX/Starlink：发射+网络+算力基础设施
  - xAI：地面 AI（Grok），Starlink 数据协同
  - Tesla Optimus：具身智能，在轨服务技术共享
  - Tesla Dojo：AI 训练芯片，星载 AI 芯片技术迁移
- **中国**：中国星网、银河航天、长光卫星、航天科工/科技
- **日本**（碎片清除 AI 专题）：ispace、Synspective、Astroscale、JAXA、Sony Space
- **印度**（高光谱 AI 专题）：Pixxel、ISRO、Skyroot
- **中东/韩/以/俄**

### 4. 投资生态（深化版 v5）
- **SpaceX 投资全景**（专项，每项数据需标注来源）：
  - 估值时间线（2020-2026）：每次估值需标注媒体来源
  - Starlink IPO 分析：需标注预测前提假设
  - 二级市场交易动态（Forge/EquityZen）
  - Musk 生态圈三角投资模型
- **SpaceX 关联投资三层网络**（每层需标注具体投资案例出处）
- 全球融资趋势、VC布局、政府/国防预算
- 具身智能头部企业与太空交叉分析

### 5. 国内外政策与竞争格局
- 美/欧/中/日/印/中东 政策对比
- **太空AI军事化专项**：US Space Force SSC、SDA PWSA、Starshield
- 太空AI国际治理

### 6. 关键技术
- 抗辐射AI芯片、星载AI框架、星间激光通信
- 太空能源与热管理、软件定义卫星、量子太空应用
- 太空AI基准测试

### 7. 空间算力卡点分析（v5 强化：每项必须附推导）
- 五大卡点：热管理/能源密度/抗辐射/星地带宽/在轨维护
- 卡点优先级矩阵与破解时间线
- 破解路径与关键变量

### 8. 经济性拐点推演（v5 强化：每项假设必须明确）
- 轨道 vs 地面数据中心 TCO 对比模型
- Starship 发射成本敏感性分析
- 率先商业化场景排序
- **关键变量**：Starship $10-50/kg 发射成本

## 数据源优先级体系（v5.0 重构）

| 优先级 | 数据源类型 | 验证方式 | 示例 |
|--------|-----------|----------|------|
| P0 | 物理/数学第一性原理 | 任何人可独立推导 | Stefan-Boltzmann、Shannon、太阳常数 |
| P1 | 官方任务/企业公告 | URL 可查 | NASA JPL、SpaceX X账号、ESA官网 |
| P2 | 学术论文 | arXiv DOI / 期刊 DOI | IEEE Aerospace、Nature Astronomy |
| P3 | 权威媒体报道 | 多源交叉验证 | Bloomberg + Reuters + CNBC |
| P4 | 行业分析报告 | 付费验证 | Seraphim Space、Morgan Stanley |
| P5 | 社交媒体/社区 | 需标注具体帖子URL | X帖子、Reddit帖子 |
| P6 | 投资数据库 | 付费验证 | Crunchbase、PitchBook、Forge |
| P7 | 匿名/推测信息 | 标注置信度+假设 | 军事预算推测、内部消息 |

## 执行流程

### Phase 0: 检查清单（每次调研必填）
- [ ] 每个事实性陈述是否有关联出处？
- [ ] 每个数字是否有来源或推导公式？
- [ ] 每个预测是否有前提假设？
- [ ] 信息来源是否标注可验证路径？
- [ ] 推导逻辑是否足够透明可复现？

### Phase 1: 并行多维度搜索（12-18 个搜索）
按 P0→P7 优先级分层搜索，推荐搜索词（v5 更新）：

**P0 级别（第一性原理，无需搜索，直接推导）**：
- 热管理：Stefan-Boltzmann P=εσAT⁴，代入目标温度计算
- 能源：太阳常数 1361W/m² × 光伏效率
- 带宽：Shannon-Hartley C = B×log₂(1+SNR)

**P1 级别（官方/企业）**：
- "NASA JPL AEGIS autonomous science" / "ESA Phi-sat-2 on-orbit AI results"
- "JAXA SLIM lunar landing AI" / "ISRO Chandrayaan-3 AI landing"
- "SpaceX Starlink official subscribers 2025"

**P2 级别（学术）**：
- "arXiv: space embodied AI survey 2025"
- "arXiv: satellite federated learning 2025"
- "arXiv: space thermal management phase change 2025"

**P3 级别（媒体/投资）**：
- "SpaceX valuation $350 billion Bloomberg 2024"
- "Starlink IPO Goldman Sachs Morgan Stanley 2025"
- "Seraphim Space investment report 2025"

**P4-P5 级别（社区/新兴）**：
- "Reddit r/SpaceX Starlink IPO discussion 2025"
- "X/Twitter elonmusk space AI 2025"
- "Korea/Israel space AI 2025" / "Russia space AI military 2025"

### Phase 2: 深度抓取（10-15 个 WebFetch）
### Phase 3: 交叉验证（P3+ 级别至少 2 个来源）
### Phase 4: 结构化报告输出

## 输出格式

每份报告必须包含：
1. **方法论声明**（信息来源标注方式）
2. **执行摘要**（5-8 个核心发现，每个标注置信度）
3. **SpaceX 投资专题**（如适用，每项数据标注来源）
4. **空间算力卡点分析**（如适用，每项附推导公式）
5. **6 大维度详细分析**
6. **区域专题**
7. **关键洞察与趋势判断**（每个预测标注前提假设）
8. **信息缺口与下一轮方向**
9. **信息来源索引**（URL + 置信度 + 可验证路径）

## 迭代机制

每次调研完成后：
1. 记录本轮方法论改进
2. 更新"核心发现基准"
3. 更新搜索词和优先级
4. 更新 `prompts/research-prompt.md` 迭代表
5. Git commit + push

## 版本历史

| 版本 | 日期 | 变更内容 |
|------|------|----------|
| 1.0 | 2026-06-18 | 初始版本，6维度基础框架 |
| 2.0 | 2026-06-18 | R1反馈：新增日/印/中东、arXiv论文、太空AI军事化、在轨训练 |
| 3.0 | 2026-06-18 | R2反馈：LEO COTS标准、碎片清除AI专题、数据源优先级体系 |
| 4.0 | 2026-06-18 | R3反馈：SpaceX投资全景、Musk生态圈三角、五大卡点定量分析、TCO模型 |
| 5.0 | 2026-06-18 | R4方法论革命：三层信息质量分级、第一性原理推导框架、必填检查项、出处标注规范、P0物理定律优先级 |
