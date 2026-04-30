# 小红书内容自动化套件 · Xiaohongshu Content Automation Suite

AI-powered content automation for Xiaohongshu (RED) — from trend mining to data analytics.  
小红书 AI 内容自动化——从选题挖掘到数据分析，全流程覆盖。

## 套件组成 · Toolkit

| Skill | 功能 Function | 时机 When |
|--------|------|----------|
| `xiaohongshu-trend-mining` | 爆款选题挖掘 · Viral topic mining | 每周选题规划 · Weekly planning |
| `xiaohongshu-copywriting` | 文案生成 · Copy generation | 选题确定后 · After topic locked |
| `xiaohongshu-cover-prompt` | 封面提示词 · Cover image prompts | 文案完成后 · After copy done |
| `xiaohongshu-data-analysis` | 数据分析 · Performance analytics | 发布后复盘 · Post-publish review |

## 完整工作流 · Full Workflow

```
周一 Mon：选题规划 · Topic Planning
├── Run trend-mining
├── Lock weekly topics
└── Plan publishing schedule

周二-周四 Tue-Thu：内容生产 · Content Creation
├── Run copywriting
├── Run cover-prompt
└── Produce images/videos

周五 Fri：发布 · Publishing
└── Pick optimal posting time

周六/日 Sat-Sun：数据分析 · Analytics
├── Run data-analysis
├── Extract patterns
└── Optimize next week
```

## 基准数据 · Benchmarks

- CTR：22.6%
- 完播率 · Completion Rate：36%

**目标 · Goal**：所有笔记达到此基准线 · All posts hit these benchmarks

## 使用方法 · Usage

Each skill works independently · 每个指令包独立使用：

```
User: Help me find viral topics on Xiaohongshu
      → Load trend-mining

User: Write a Xiaohongshu post about xxx
      → Load copywriting

User: Generate cover image prompts
      → Load cover-prompt

User: Analyze my last 10 posts' data
      → Load data-analysis
```

## 文件结构 · File Structure

```
指令包/ (skills/)
├── xiaohongshu-trend-mining/
│   └── SKILL.md
├── xiaohongshu-copywriting/
│   └── SKILL.md
├── xiaohongshu-cover-prompt/
│   └── SKILL.md
├── xiaohongshu-data-analysis/
│   └── SKILL.md
└── README.md
```

## Why This Exists

Xiaohongshu is China's fastest-growing content platform, but creating high-CTR content consistently is hard. This suite encodes battle-tested patterns from a 22.6% CTR account into reusable AI workflows.

小红书是中国增长最快的内容平台，但持续产出高点击率的内容很难。这套指令包把一个 CTR 22.6% 的账号实战经验，编码成了可复用的 AI 工作流。

---

<details>
<summary>☕ Buy me a coffee</summary>
<br>
<img src="https://github.com/maomao52088/xiaohongshu-automation-skills/releases/download/assets/donate.jpg" width="120" alt="Alipay">
</details>

Made by 大龙猫 (Big Totoro) · 2026.04.15