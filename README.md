# 大模型学习路线图 · LLM Learning Roadmap

> **这是一个什么东西？** 一张单页、可点击的大模型（LLM）学习地图：把「先学什么、往哪儿深入、手上练什么」三件事画进同一张图，119 个资源直接跳到论文、代码与文档，不需要在收藏夹里翻找。
>
> **What it is**: a single-page, clickable roadmap for learning large language models — a 9-stage main path, 5 deep-dive branches, and a 30-day paper practicum, with 119 curated links straight to papers, official code and docs.

**在线预览 / Live demo**：<https://yunxingwoo.github.io/llm-learning-roadmap/>

---

## 中文

### 这是什么

一份 2026 年的大模型学习路线图，把散落在博客、论文和课程里的知识压成一张能从头走到尾的地图。它不是资源合集，而是一条有先后顺序的路线：每个阶段都为下一个阶段提供参照物，第 02 阶段（GPT-2）是整张图的锚点。

### 包含什么

| 部分 | 内容 | 解决的问题 |
| --- | --- | --- |
| 主线 · 9 个阶段 | 前置基础 → Transformer → GPT-2 → 预训练 → SFT/对齐 → …… → 多模态 | 先学什么，按什么顺序学 |
| 支线 · 5 条 | 推理、训练、对齐、架构、应用 | 想往哪个方向深入，从哪篇论文/项目切入 |
| 论文实训 · 30 天 | 每天一篇论文，标注它补在主线的哪一段 | 手上练什么，怎么把读论文变成习惯 |
| 资源 · 119 个 | 论文、官方代码、文档、博客 | 每学一个概念，去哪儿看原文 |

### 适合谁

- 想系统入门大模型、但被资料淹没的人
- 已会调 API、想搞清底层原理的工程师
- 准备转岗/面试，需要一条可讲清楚的知识主线的人

### 怎么用

1. 从阶段 00 顺着主线走，不要跳段；
2. 走到第 02 阶段后，挑 1–2 条支线深入，不需要五条全走；
3. 主线 + 支线并行的同时，按 30 天清单读论文，读完当天那篇再继续。

### 本地打开

单文件、无构建、无后端依赖（只有字体走 Google Fonts，加载失败会自动回退系统字体）：

```bash
open index.html        # macOS
# 或在浏览器里直接拖入 index.html
```

## English

### What this is

A 2026 learning roadmap for large language models that compresses blogs, papers and courses into one walkable map. It is a route, not a link dump: each stage is the reference point for the next, and Stage 02 (GPT-2) anchors the whole map.

### What's inside

| Part | Content | Question it answers |
| --- | --- | --- |
| Main path · 9 stages | Prerequisites → Transformer → GPT-2 → Pretraining → SFT/Alignment → … → Multimodal | What to learn first, and in what order |
| Branches · 5 tracks | Inference, Training, Alignment, Architecture, Applications | Where to go deep, and which paper/project to start from |
| Paper practicum · 30 days | One paper a day, each mapped back to a stage on the main path | What to practise, and how to build a reading habit |
| Resources · 119 links | Papers, official code, docs, blogs | Where to read the primary source for each concept |

### Who it is for

- People who want a systematic entry into LLMs but are drowning in material
- Engineers who already call APIs and want the underlying mechanics
- Anyone preparing for a role change or interview who needs one clear story to tell

### How to use it

1. Start at Stage 00 and follow the main path; do not skip stages.
2. After Stage 02, pick one or two branches to go deep — you don't need all five.
3. Run the 30-day paper list alongside the main path: read that day's paper before moving on.

### Run locally

Single file, no build step, no backend. Only the web fonts come from Google Fonts, and they fall back to system fonts if the CDN is unavailable:

```bash
open index.html        # macOS
# or simply drag index.html into a browser
```

---

## 内容来源与致谢 / Credits

- 论文链接以 arXiv 原文为准；代码与文档链接指向各项目官方仓库。
- 三十天论文清单参考 [30u30](https://ojhaharsh.github.io/30u30/)（作者 Ojhaharsh，CC BY-NC-ND 4.0），按其许可要求保留署名、不用于商业用途。
- 页面为静态单文件 HTML + CSS + 原生 JS，图表与交互均为自绘，无第三方 UI 框架。

---

2026 · 大模型学习路线图 · built as a single self-contained HTML page
