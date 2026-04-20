---
type: concept
title: Semantic Color
aliases: [语义化着色, 色彩语义]
tags: [design, data-visualization, color, information-design]
related:
  - concepts/PPT-Design-System
  - concepts/Data-Ink-Ratio
source_files:
  - raw/prompt/ppt-design-system.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

语义化着色（Semantic Color）是指颜色在界面/图表中承载特定信息含义，而非仅用于装饰或品牌表达。观众看到颜色即可快速理解数据状态，无需额外阅读文字说明。

## 核心机制

### 企业分析报告的语义色映射
| 语义 | 颜色 | HEX | 应用场景 |
|------|------|-----|----------|
| 主题/中性 | 深蓝 | `#00467F` | 标题、主色调、中性信息 |
| 二级主题 | 中蓝 | `#0070C0` | 二级标题、图表主系列 |
| 正向/达标 | 增长绿 | `#1AAB55` | 同比增长、完成率达标、排名上升 |
| 超额完成 | 深绿 | `#0B6E31` | 完成率 >110%、显著超额 |
| 负向/预警 | 警示红 | `#CF1322` | 同比下降、未达标、排名下降 |
| 严重落后 | 深红 | `#820014` | 完成率 <80%、严重预警 |
| 关注/待确认 | 暖橙 | `#FA8C16` | 需关注、风险提示、待确认 |

### 禁止模式
- 同一页使用超过 4 种颜色（图表系列色除外）
- 纯黑 `#000000` 作为正文色（应使用深灰 `#1A1A1A`）
- 渐变色填充柱子（打印失真、视觉干扰）

## 应用与用例

- **条件格式**：表格中完成率低于 50% 自动标红，正增长标绿
- **趋势符号**：▲ 绿色表示增长，▼ 红色表示下降
- **KPI 卡片**：数字根据状态变色（达标=深蓝，超额=绿色，落后=红色）

## 与其他概念的关系

- 与 [[concepts/PPT-Design-System]] 的关系：语义化着色是设计系统的核心组成部分
- 与 [[concepts/Data-Ink-Ratio]] 的关系：色彩作为"数据墨水"必须服务于信息，去除装饰性用色

## 来源引用

- (source: raw/prompt/ppt-design-system.md)
