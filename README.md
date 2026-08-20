# Master CV JD Tailor Skill

> A JD-aware resume tailoring skill built around a verified Master CV, factual rewriting, stable resume structure, and one-page validation.  
> 以经过确认的 Master CV 为事实库，根据目标 JD 进行经历筛选、篇幅分配、事实约束下的改写与一页简历验证。

## Why this skill?

很多 AI 简历工具会优先追求关键词匹配，但容易出现这些问题：

- 为了贴 JD 过度改写，甚至补出原本不存在的经历
- 打乱原有简历结构，把不同类型经历混在一起
- 把一个真实项目拆成多个重复 bullet
- 过度使用英文术语，让中文简历显得生硬
- 强行给每条经历加入量化结果
- 只验证“PDF 是 1 页”，却忽略页面是否过空、过挤或难读
- 每换一个 JD 就换一套模板，导致个人简历风格不稳定

这个 Skill 采用另一种方式：

**Master CV 是唯一事实源，JD 只决定“选什么、怎么强调、怎么表达”，而不是创造新的经历。**

---

## Core Principles

### 1. Master CV = Single Source of Truth

所有定制简历都应从经过确认的 Master CV 中选择和改写。

允许：
- 调整排序
- 调整篇幅
- 换业务表达角度
- 合并或压缩低相关内容
- 使用更贴近 JD 的能力语言

不允许：
- 虚构工具使用经验
- 虚构业务结果
- 把团队结果全部归因给个人
- 把“不确定”写成“确定”
- 为了匹配 JD 反向创造理想候选人经历

---

### 2. Analyze Before Rewrite

看到 JD 后，不应立刻生成简历。

先拆解：

1. 3–5 个核心职责
2. 硬性要求
3. 加分项
4. 岗位真正看重的能力
5. 候选人的直接匹配点
6. 明显缺口

如果某个事实会显著影响 bullet 强度，但 Master CV 中没有明确记录，应先向用户确认。

---

### 3. Preserve Resume Structure

默认保留 Master CV 的原始 section 层级，例如：

- 教育背景
- 实习经历
- 项目与运营经历
- 其他经历
- 技能与兴趣

JD 定制主要通过：

- 选择哪些经历
- 每段保留几条
- 哪些经历写得更详细
- bullet 的业务表达
- Skills 的重排
- 个人简介的侧重点

来体现岗位匹配度。

不要为了让某段经历“排第一”，随意把全部内容合并成“相关经历”。

---

### 4. One Real Workstream = One Complete Bullet

一个真实项目 / workstream，默认对应：

**一个业务小标题 + 一条完整 bullet**

推荐结构：

**业务能力 / 项目类型：业务场景 + 行动 + 方法 / 数据 + 产出 / 已知结果**

不要把一个完整项目机械拆成：

- 市场调研
- 竞品分析
- 财务测算
- 投资建议

如果这些本来就是同一个收购咨询项目，应合并为一个完整项目故事。

---

### 5. Business-first Labels

小标题优先描述业务问题或工作模块，例如：

- 渠道增长
- 产品策略
- 市场洞察
- 收购咨询
- 内容策略
- 商业化运营

而不是：

- SQL 分析
- Python 分析
- A/B Testing
- Power BI
- 数据清洗

工具和方法放在 bullet 正文中。

---

### 6. Chinese-first Wording

中文简历优先使用自然、行业常用的中文表达。

不必要的英文术语应避免，例如：

- Voice of Customer → 客诉与用户反馈
- Customer Segmentation → 用户分层
- Lifecycle Funnel → 生命周期漏斗
- Comparable Analysis → 可比项目分析

但行业标准工具、指标和专有名词可以保留，例如：

- SQL
- Python
- Power BI
- LEED
- ESG
- NOI
- Cap Rate
- IRR

判断标准不是“英文是否显得专业”，而是“目标行业是否通常这样表达”。

---

### 7. Real Metrics Only

真实、有业务意义的数字优先保留，但不要求每条 bullet 都必须量化。

适合保留：

- 20+ 个项目
- 数万粉 → 百万粉
- 10 万至 100 万+ 点赞
- 3 分钟归因窗口

避免：

- 无依据的“效率提升 30%”
- 无法验证的转化提升
- 与业务价值无关的巨大数据量
- 把相关性写成因果关系

---

### 8. JD-aware Content Allocation

JD 定制的重点不是关键词替换，而是篇幅分配。

可以按相关性进行处理：

- 高相关：保留完整 bullet，适当增加细节
- 中相关：压缩为 1 条
- 低相关：保留极简版本或删除

但默认不跨 section 随意搬动经历。

---

### 9. Skills Must Also Be Tailored

Skills 不应机械复制 Master CV。

例如：

互联网 / 市场岗位可强调：
- 渠道分析
- 内容运营
- 用户增长
- 市场研究
- Excel / SQL / Python
- 英文能力

地产 / 投资岗位可强调：
- 可比项目分析
- 租金测算
- NOI / Cap Rate / IRR
- 市场研究
- PowerPoint / Excel

只保留与目标 JD 有意义的技能。

---

### 10. Stable Visual Template

默认沿用用户已有简历的视觉体系，不因 JD 自动换模板或颜色。

推荐默认：

- A4 一页
- 黑白简洁
- section 标题清晰
- section 下保留横向分隔线
- 机构 / 项目名称明显
- bullet 层级稳定
- 中文阅读自然
- 不默认添加照片

除非用户主动要求，否则：

**改 JD = 改内容，不等于换模板。**

---

### 11. One Page ≠ Page Count Only

一页验证不能只检查：

`page_count == 1`

还应检查：

- 页面是否基本填满
- 留白是否均衡
- 是否出现底部大面积空白
- 是否为了塞满而过度缩小字号
- 是否出现孤行
- section 横线是否完整
- 机构名称、日期、地点是否对齐
- 联系方式是否准确
- 正文字号是否可读

推荐目标：

**有效内容约占页面 85%–95%，同时保持正常阅读密度。**

调整顺序：

1. 优先加入更有价值的真实内容
2. 调整 bullet 篇幅
3. 调整 section spacing
4. 最后才微调字号和页边距

---

## Workflow

```text
Target JD
   ↓
JD Responsibility Analysis
   ↓
Match / Gap Analysis
   ↓
Clarification (if needed)
   ↓
Master CV Mapping
   ↓
Experience Selection
   ↓
JD-aware Factual Rewriting
   ↓
DOCX Generation
   ↓
One-page + Visual Validation
   ↓
Final Resume
```

---

## Project Structure

```text
mastercv-jd-tailor-skill/
├── SKILL.md
├── README.md
├── LICENSE
├── references/
│   └── jd_mapping.md
└── scripts/
    ├── resume_template.py
    └── verify_resume.py
```

---

## Usage

### Step 1 — Prepare a verified Master CV

先整理一份尽可能完整的 Master CV。

Master CV 不需要一页，可以保存：

- 所有真实实习经历
- 所有项目
- 工作背景
- 数据和方法
- 可验证结果
- 技能
- 已确认的量化指标
- Stakeholder / 使用方
- 尚不确定的业务结果

Master CV 的目标是成为事实库，而不是直接投递。

### Step 2 — Provide a target JD

输入目标公司的岗位描述。

Skill 会先分析 JD，而不是立即改写简历。

### Step 3 — Clarify missing facts

如果出现类似情况，应先追问：

- 是否主导项目？
- 是否真正操作过某个平台？
- 结果是否上线？
- 分析是给内部团队还是外部客户？
- 最终结论是否已确认？

无法确认的事实不应写入简历。

### Step 4 — Map JD to Master CV

根据 JD 选择最相关的经历，并决定：

- 哪些完整保留
- 哪些压缩
- 哪些删除
- 哪些 bullet 需要换业务表达角度
- 哪些 Skills 应前置

### Step 5 — Generate the tailored resume

默认输出一页 `.docx`。

推荐文件名：

```text
姓名_公司_岗位.docx
```

例如：

```text
朱程锋_友塔游戏_市场管培生.docx
```

### Step 6 — Validate

验证：

- 是否一页
- 页面是否基本填满
- 字号是否正常
- 横线和 section 是否完整
- 是否存在异常留白
- 联系方式是否正确
- 是否出现未被 Master CV 支持的表述

---

## Example

假设目标 JD 重点要求：

- 市场策略
- 内容创意
- 数据分析
- 用户洞察
- 游戏经验

Master CV 中存在：

- 百万粉丝内容账号运营
- 渠道转化与产品分析
- 市场研究
- 游戏经历
- 商业地产投资分析

Skill 不会简单地把所有经历都保留。

更合理的策略是：

```text
高相关
→ 内容策略 / 商业化运营
→ 渠道效果分析 / 策略效果评估

中相关
→ 市场洞察

低相关
→ 商业地产投资测算压缩或删除
```

同时保留原始 section 结构，不把所有内容合并成“相关经历”。

---

## Before / After Philosophy

### Before

```text
参与账号运营，负责内容选题、发布排期和数据复盘。
```

### After

```text
内容策略：参与账号从唱歌内容向手势舞方向的定位转型，结合播放量、互动表现及粉丝反馈持续复盘不同内容形式，提出增加手势舞及外景拍摄等方向；转型后账号由数万粉增长至百万粉级，多条内容获得 10 万至 100 万+ 点赞。
```

改写的重点不是“换高级词”，而是恢复完整的业务链路：

**背景 → 判断 → 行动 → 方法 → 已知结果**

---

## What This Skill Does Not Do

这个 Skill 不应该：

- 自动虚构 JD 中出现但候选人没有的技能
- 为了 ATS 关键词强行重复 JD
- 自动把所有经历改成英文
- 自动替换简历视觉模板
- 默认添加照片
- 为每个 bullet 强行制造数字
- 用“技术上一页”替代真正的视觉检查

---

## Design Philosophy

The goal is not to create a completely different resume for every JD.

The goal is to maintain **one verified Master CV as the factual source**, then generate role-specific branches through:

**selection + emphasis + factual rewriting + visual validation**

可以把它理解为：

```text
Master CV = main branch

Target JD A → tailored resume A
Target JD B → tailored resume B
Target JD C → tailored resume C
```

Master CV 保留事实，JD 定制版只负责选择和表达。

---

## License

MIT License
