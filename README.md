# data-ops-resume

数据运营岗位简历撰写与优化 Skill —— 适用于 Kimi、Claude 等 Agent 技能目录（[SKILL.md](SKILL.md) + [references/exemplars.md](references/exemplars.md)）。

从四份真实数据运营候选人简历中提炼：把「什么经历算数、怎么写才有竞争力」沉淀成可复用的撰写公式与标杆句式。

## 能做什么

- **写简历**：根据你的原始经历素材 + 目标 JD，产出一份数据运营方向的单页简历
- **改简历**：把现有经历按「动作 + 工具 + 量化结果」公式重写，补齐数字和工具名
- **评简历**：按模块覆盖度、量化率、工具具体度、JD 匹配度打分，给出强项 / 短板 / 是否约面结论

## 核心方法

数据运营的四大工作模块（招聘方在简历里找的证据）：

1. **数据治理与质量** —— 清洗、标准化、口径统一
2. **指标体系与监控** —— 核心指标、BI 看板（Tableau / Power BI）、异常排查
3. **业务诊断与分析** —— 漏斗分析、根因分析、用户分层
4. **策略落地与复盘** —— A/B 测试、活动效果量化、SOP 优化

Bullet 撰写公式：**动词开头 + 方法/工具具体 + 量化结果**（绝对值 + 相对值双写）。

## 安装

把整个仓库克隆（或复制 `SKILL.md` 与 `references/`）到你的 Agent 技能目录：

```bash
# Kimi / Claude 用户级技能目录（任选其一）
git clone https://github.com/zheyu-wq/data-ops-resume.git ~/.kimi/skills/data-ops-resume
# 或
git clone https://github.com/zheyu-wq/data-ops-resume.git ~/.claude/skills/data-ops-resume
```

## 使用示例

安装后直接对 Agent 说：

- 「帮我写一份数据运营实习简历，这是我的经历：……」
- 「把这份简历改成数据运营方向，JD 是：……」
- 「评估这份数据运营简历，给是否约面的结论」

## 文件结构

```
data-ops-resume/
├── SKILL.md                  # 岗位画像、简历结构、bullet 公式、关键词库、自检清单
└── references/
    └── exemplars.md          # 13 条标杆 bullet 句式骨架 + 4 种常见短板模式
```
