---
type: concept
title: LLM Wiki
aliases: [LLM 知识库, 大模型 Wiki]
tags: [knowledge-management, ai, markdown, obsidian]
related:
  - concepts/RAG
  - concepts/Zettelkasten
  - concepts/Memex
  - concepts/Idea-File
source_files:
  - raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

LLM Wiki 是由 Andrej Karpathy 提出的一种知识管理模式：让大模型在后台持续构建、维护一个结构化、相互链接的本地 Markdown 知识库，而不是在每次提问时临时去海量原始数据里翻找。

## 核心机制

### 三层架构

1. **Raw Sources（原始数据层）**：不可变的原始文件（文章、论文、笔记、图片），LLM 只读不写
2. **The Wiki（编译输出层）**：LLM 全权维护的 Markdown 文件集合，包括摘要、概念、实体、综合判断等
3. **The Schema（控制协议层）**：定义目录结构、页面格式、操作流程的配置文档（如 `CLAUDE.md`）

### 三大操作

| 操作 | 功能 | 人类角色 | LLM 角色 |
|------|------|----------|----------|
| Ingest | 摄入新材料，更新知识体系 | 确认重点、引导方向 | 提取要点、建立链接、更新页面 |
| Query | 提问并获得带引用的答案 | 提出好问题 | 搜索、综合、生成答案 |
| Lint | 健康检查 | 审阅报告 | 检测矛盾、发现孤岛、标记过时内容 |

## 应用与用例

- **个人研究**：将阅读的文章、论文自动整合为结构化知识库
- **企业知识管理**：将 Slack 日志、内部 Wiki、PDF 报告编译为实时更新的"公司知识圣经"
- **项目文档**：代码仓库配合 `.brain` 文件夹，作为 AI 会话间的持久记忆

## 与其他概念的关系

- **vs [[concepts/RAG|RAG]]**：RAG 是查询时处理（阅后即焚），LLM Wiki 是摄入时处理（复利增长）
- **vs [[concepts/Zettelkasten|Zettelkasten]]**：Zettelkasten 强调"认知摩擦"（用自己的话写卡片就是思考本身），LLM Wiki 消除了这种摩擦，可能削弱深度认知整合
- **vs [[concepts/Memex|Memex]]**：更接近 Vannevar Bush 1945 年设想的私有、精心策展的联想记忆系统

## 来源引用

- Karpathy 原始 Gist (source: raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md)
- 掘金文章完整梳理 (source: raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md)
