# Humanizer-ZH-Academic

> 🎓 降低中文学术写作 AIGC 检测率的 Claude Code Skill | Reduce AIGC detection rate for Chinese academic writing

[中文说明](#中文) | [English](#english)

---

## 中文

### 简介

`humanizer-zh-academic` 是一个专为 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) 设计的 Skill，用于降低中文学术写作（论文、期刊文章、毕业论文等）的 AIGC 检测率。

**核心理念：** AIGC 检测器识别的不是「内容」，而是「写作模式」的统计规律。本 Skill 通过打破 AI 写作的模式规律性，注入人类写作的随机性与真实感，从而有效降低检测率。

### 效果

基于真实论文改写实验：

| 指标 | AI 原稿 | 人工化处理后 |
|------|---------|-------------|
| AIGC 检测率 | >50% | **11%** |

### 核心特性

- 🔍 **16 种 AI 模式识别** — 覆盖内容、语言、风格三个层面
- ⚠️ **7 项硬约束** — 命中即修复，确保输出质量
- 📋 **标准化 SOP** — 四步操作流程，从风险扫描到噪声保留
- 📊 **6 维质量评分** — 含独创的「抗检测性」维度
- 🎯 **噪声预算** — 防止过度修改导致另一种不自然
- 🎓 **学术语域适配** — 区分期刊论文、毕业论文、研究报告等文体

### 安装

将本仓库克隆到你的 Claude Code Skills 目录：

```bash
# 全局安装
git clone https://github.com/redbaronyyyyy-eng/humanizer-zh-academic.git \
  ~/.gemini/antigravity/skills/humanizer-zh-academic

# 或项目级安装
git clone https://github.com/redbaronyyyyy-eng/humanizer-zh-academic.git \
  .gemini/skills/humanizer-zh-academic
```

### 使用方法

在 Claude Code 中触发关键词：

- `降低AI率`
- `降低AIGC`
- `去AI味`
- `人工润色`
- `humanize`
- `学术写作润色`

### 适用范围

| 适用 ✅ | 不适用 ❌ |
|---------|----------|
| 中文学术论文 | 营销文案 |
| 期刊文章 | 新闻稿 |
| 毕业论文 | 小说/文学创作 |
| 研究报告 | 社交媒体内容 |
| 英文论文的中文翻译稿 | 日常对话文本 |

---

## English

### Introduction

`humanizer-zh-academic` is a [Claude Code](https://docs.anthropic.com/en/docs/claude-code) Skill designed to reduce AIGC (AI-Generated Content) detection rates in Chinese academic writing (papers, journal articles, theses, etc.).

**Core Insight:** AIGC detectors identify statistical patterns in writing, not content itself. This Skill breaks the predictability of AI writing patterns and injects the randomness and authenticity of human writing.

### Results

Based on real paper rewriting experiments:

| Metric | AI Draft | After Humanization |
|--------|----------|-------------------|
| AIGC Detection Rate | >50% | **11%** |

### Key Features

- 🔍 **16 AI Pattern Recognition** — Covering content, language, and style layers
- ⚠️ **7 Hard Constraints** — Auto-fix on match, ensuring output quality
- 📋 **Standardized SOP** — Four-step workflow from risk scanning to noise preservation
- 📊 **6-Dimension Quality Score** — Including novel "anti-detection" dimension
- 🎯 **Noise Budget** — Prevents over-editing from creating a different kind of unnaturalness
- 🎓 **Academic Register Adaptation** — Distinguishes journal papers, theses, reports, etc.

### Installation

Clone this repository to your Claude Code Skills directory:

```bash
# Global installation
git clone https://github.com/redbaronyyyyy-eng/humanizer-zh-academic.git \
  ~/.gemini/antigravity/skills/humanizer-zh-academic

# Or project-level installation
git clone https://github.com/redbaronyyyyy-eng/humanizer-zh-academic.git \
  .gemini/skills/humanizer-zh-academic
```

### Usage

Trigger keywords in Claude Code:

- `降低AI率` (reduce AI rate)
- `降低AIGC` (reduce AIGC)
- `去AI味` (remove AI flavor)
- `humanize`
- `学术写作润色` (academic writing polish)

---

## References

- [Wikipedia: Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) (WikiProject AI Cleanup)
- Real Chinese paper multi-version comparison experiments
- [de-AI-writing skill](https://github.com/OUBIGFA) (OUBIGFA) — Hard constraint design reference
- [humanizer-zh](https://github.com/op7418) (op7418) — Pattern classification reference

## License

[MIT](LICENSE)
