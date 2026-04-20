---
type: entity
entity_type: tool
title: Obsidian
aliases: []
related:
  - concepts/LLM-Wiki
source_files:
  - raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md
last_updated: 2026-04-20
---

## 简介

Obsidian 是一款基于本地 Markdown 文件的知识库编辑器，支持双向链接、图谱视图和丰富的插件生态。

## 核心功能

- **本地优先**：所有数据存储在本地纯文本文件，用户完全拥有数据
- **双向链接**：`[[wiki-link]]` 语法建立页面间关联
- **图谱视图**：可视化展示页面间的连接关系
- **插件生态**：Web Clipper、Dataview、Marp 等扩展

## 在 LLM Wiki 中的角色

Karpathy 将 Obsidian 比作"IDE"：

> **Obsidian 是你的 IDE，大模型是你的程序员，而这个 Markdown 知识库就是你们共同维护的代码库。**

- 人类用 Obsidian 浏览和阅读 Wiki
- LLM 负责撰写和维护 Wiki 内容
- Web Clipper 用于快速采集网页到 `raw/` 目录

## 相关概念

- [[concepts/LLM-Wiki]] — 使用 Obsidian 作为前端的知识管理模式

## 来源引用

- (source: raw/my-notes/LLM Wiki：让大模型替你打理知识库的完整指南.md)
