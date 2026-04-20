---
type: concept
title: RAG (Retrieval-Augmented Generation)
aliases: [检索增强生成]
tags: [ai, llm, architecture]
related:
  - concepts/LLM-Wiki
source_files:
  - raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

RAG（Retrieval-Augmented Generation，检索增强生成）是一种将外部知识检索与大语言模型生成能力结合的架构。文档被切分为 Chunk，转成向量存入数据库，查询时做相似性搜索，再将检索结果喂给大模型生成答案。

## 核心机制

1. **索引阶段**：文档 → 分块 → 向量化 → 存入向量数据库
2. **查询阶段**：用户提问 → 向量化查询 → 相似性搜索 → 将检索到的上下文注入 Prompt → LLM 生成答案

## 与 LLM Wiki 的对比

| 维度 | RAG | LLM Wiki |
|------|-----|----------|
| 知识处理时机 | 查询时（每次提问重新处理） | 摄入时（每个来源只处理一次） |
| 交叉引用 | 每次查询临时发现 | 预先构建并持续维护 |
| 矛盾检测 | 可能完全不会被注意到 | 摄入时主动标记 |
| 知识积累 | 无——每次从零开始 | 复利式增长 |
| 输出格式 | 聊天回复（转瞬即逝） | 持久化的 Markdown 文件 |
| 维护者 | 系统黑箱 | LLM（透明、可编辑、可追溯） |

## 局限性

- **没有沉淀**：每次回答同样的问题都要重新检索、重新拼凑
- **缺乏全局视角**：无法自动发现跨文档的关联和矛盾
- **输出不可复用**：答案留在聊天记录中，无法成为知识资产

## 来源引用

- (source: raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md)
