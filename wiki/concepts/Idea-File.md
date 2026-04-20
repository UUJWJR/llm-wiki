---
type: concept
title: Idea File
tags: [ai, sharing, open-source, pattern]
related:
  - concepts/LLM-Wiki
source_files:
  - raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

Idea File 是 Karpathy 提出的一种新的分享范式：故意保持抽象的概念文档，设计目的是让读者复制粘贴给自己的 LLM Agent，由 Agent 根据具体需求去实例化。

## 核心洞察

> "在 LLM Agent 的时代，分享具体的代码或应用已经不那么必要了。你只需要分享想法，然后对方的 Agent 会根据具体需求去定制和构建。"

## 与传统开源的对比

| 维度 | 传统开源 | Idea File |
|------|----------|-----------|
| 分享内容 | 代码、应用、Docker 镜像 | 想法、模式、流程 |
| 接收者操作 | 克隆、配置、调试 | 复制粘贴给 Agent |
| 可移植性 | 依赖特定技术栈 | 跨平台、跨工具 |
| 维护成本 | 需要持续维护代码 | 想法本身不需要维护 |

## 实例

Karpathy 的 LLM Wiki Gist 就是一个典型的 Idea File：
- 他用 Obsidian + macOS + Claude Code
- 你可能用 VS Code + Linux + Codex
- 一份 idea file 复制粘贴给你的 Agent，Agent 就能构建适配你环境的版本

## 意义

这是开源的一种新形态：**不是 open code，而是 open ideas**。

## 来源引用

- Karpathy 原始 Gist (source: raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md)
