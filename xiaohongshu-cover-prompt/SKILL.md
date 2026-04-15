---
name: xiaohongshu-cover-prompt
description: 生成小红书封面图的AI绘图提示词，确保视觉冲击力
triggers:
  - pattern: "封面图"
  - pattern: "小红书封面"
  - pattern: "生成封面"
---

# 小红书封面提示词库

## 封面类型选择

### 类型A：人物+文字

**适用**：个人成长、生活方式、干货分享

**提示词模板**：
```
[主体描述]，[动作/表情]，[场景]，[光线]，[风格]
+ 大面积留白用于文字
+ 文字占画面30-40%
```

**示例**：
```
Asian woman in casual wear, sitting at desk with laptop, 
confident smile looking at camera, warm natural lighting,
minimalist home office background, 
leaving top 40% space for text overlay,
Instagram style, high quality, 4:5 aspect ratio
```

---

### 类型B：对比图

**适用**：教程、前后对比、测评

**提示词模板**：
```
Split screen composition, 
[left side description] vs [right side description],
clear visual contrast,
[风格关键词]
```

**示例**：
```
Split screen comparison,
left: messy desk with piles of paper, dark lighting,
right: clean organized workspace, bright natural light,
before and after transformation,
minimalist aesthetic, 4:5 aspect ratio
```

---

### 类型C：纯文字排版

**适用**：清单、干货、工具推荐

**提示词模板**：
```
Minimalist background, [颜色/渐变],
text-focused design,
[装饰元素],
clean typography aesthetic
```

**示例**：
```
Soft gradient background, cream to light pink,
minimalist design with subtle geometric shapes,
plenty of negative space for text,
aesthetic Pinterest style, 4:5 aspect ratio
```

---

### 类型D：场景+道具

**适用**：生活方式、好物推荐、Vlog

**提示词模板**：
```
[道具/物品], [摆放方式], [背景], [氛围],
lifestyle photography style,
[颜色调性]
```

**示例**：
```
Journal and coffee cup on wooden desk,
aesthetic flat lay composition,
morning sunlight through window,
cozy productive vibe,
warm earth tones, lifestyle photography, 4:5 aspect ratio
```

---

## 封面设计原则

| 元素 | 规范 |
|------|------|
| 文字占比 | 30-40% |
| 字体大小 | 标题占画面1/3 |
| 颜色数量 | 不超过3种主色 |
| 对比度 | 文字与背景对比 > 70% |
| 信息密度 | 标题 ≤ 15字 |

## 文字排版模板

### 模板1：数字冲击
```
[大数字]
[一句话副标题]
```

### 模板2：对比冲突
```
[A] vs [B]
[结论]
```

### 模板3：清单预告
```
[X个] [主题]
[钩子短句]
```

## 快速生成流程

1. 确定内容类型
2. 选择对应封面类型
3. 填充提示词模板
4. 用Midjourney/DALL-E生成
5. 用Canva添加文字

## 输出格式

```markdown
## 封面方案

**类型**：[A/B/C/D]
**提示词**：
```
[完整提示词]
```

**文字内容**：
- 主标题：___
- 副标题：___

**预计效果**：
- 视觉风格：___
- 情绪调性：___

---

🦞 大龙猫制作
```

---

## 注意事项

1. **人物统一** — 同一系列用同一风格的人物描述
2. **色调一致** — 建立账号专属色系
3. **留白足够** — 文字区域要预留空间
4. **避免杂乱** — 简洁比丰富更重要
5. **手机优先** — 设计时考虑手机屏幕效果

---

🦞 大龙猫制作
