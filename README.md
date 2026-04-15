# 小红书内容自动化套件

## 套件组成

| 指令包 | 功能 | 使用时机 |
|--------|------|----------|
| `xiaohongshu-trend-mining` | 爆款选题挖掘 | 每周选题规划 |
| `xiaohongshu-copywriting` | 文案生成 | 选题确定后 |
| `xiaohongshu-cover-prompt` | 封面提示词 | 文案完成后 |
| `xiaohongshu-data-analysis` | 数据分析 | 发布后复盘 |

---

## 完整工作流

```
周一：选题规划
├── 运行 trend-mining
├── 确定本周选题
└── 制定发布计划

周二-周四：内容生产
├── 运行 copywriting
├── 运行 cover-prompt
└── 完成图文/视频

周五：发布
└── 选择最佳时间发布

周六/日：数据分析
├── 运行 data-analysis
├── 总结规律
└── 优化下周内容
```

---

## 基准数据（路标笔记）

- CTR：22.6%
- 完播率：36%

**目标**：所有笔记达到此基准线

---

## 使用方法

每个指令包独立使用：

```
用户：帮我挖掘小红书爆款选题
→ 加载 trend-mining

用户：写一篇小红书文案，选题是xxx
→ 加载 copywriting

用户：生成封面提示词
→ 加载 cover-prompt

用户：分析最近10条笔记数据
→ 加载 data-analysis
```

---

## 文件位置

```
/mnt/d/备份/大龙猫/指令包/
├── xiaohongshu-trend-mining/
│   └── SKILL.md
├── xiaohongshu-copywriting/
│   └── SKILL.md
├── xiaohongshu-cover-prompt/
│   └── SKILL.md
├── xiaohongshu-data-analysis/
│   └── SKILL.md
└── README.md（本文件）
```

---

🦞 大龙猫制作 · 2026.04.15
