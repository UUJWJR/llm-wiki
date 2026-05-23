---
type: concept
title: PPT 设计系统 (PPT Design System)
aliases: [PPT 设计系统, 演示文稿设计规范]
tags: [design, ppt, data-visualization, business-report, ui]
related:
  - concepts/Data-Ink-Ratio
  - concepts/Semantic-Color
  - concepts/Executive-Summary-First
source_files:
  - raw/prompt/ppt-design-system.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

PPT Design System 是一套用于企业内部分析型报告（周报、月报、专题分析、经营复盘）的演示文稿设计规范，涵盖页面设置、色彩体系、字体字号、图表样式、表格规范、布局模板和排版原则。

## 核心机制

### 三层约束体系
1. **视觉层**：色彩、字体、字号、间距的严格定义——确保全篇视觉一致性
2. **结构层**：页面类型模板（封面、目录、数据页、对比页、汇总页）——确保信息架构清晰
3. **语义层**：结论前置、色彩语义化、条件格式——确保信息传达高效

### 色彩语义系统
| 语义 | 颜色 | 应用场景 |
|------|------|----------|
| 主题/中性 | 蓝色系 `#00467F` / `#0070C0` | 标题、主题信息、中性数据 |
| 正向/达标 | 绿色系 `#1AAB55` / `#0B6E31` | 增长、达标、超额完成 |
| 负向/预警 | 红色系 `#CF1322` / `#820014` | 下降、未达标、落后 |
| 关注/待确认 | 橙色 `#FA8C16` | 风险提示、待确认事项 |

## 应用与用例

- **电信运营周调度会**：收入/客户/宽带/存量运营数据汇报
- **企业经营复盘**：KPI 达成情况、环比变化、短板分析
- **专题分析报告**：市场竞争、用户行为、产品表现

## 与其他概念的关系

- 与 [[concepts/Data-Ink-Ratio]] 的关系：设计系统强制要求去除非必要网格线、图例边框，践行数据墨水比原则
- 与 [[concepts/Semantic-Color]] 的关系：色彩不是装饰，而是信息编码——绿色=好，红色=差，蓝色=中性
- 与 [[concepts/Executive-Summary-First]] 的关系：每页顶部摘要条必须给出明确结论，而非描述性陈述

## 来源引用

- (source: raw/prompt/ppt-design-system.md)
