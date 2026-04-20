---
type: summary
title: "PPT 页面设计规范 v2.0"
source_files:
  - raw/prompt/ppt-design-system.md
source_type: note
date: 2026-04-20
tags: [ppt, design-system, data-visualization, business-report, ui]
---

## 关键要点

- **适用范围**：业务数据周报、月报、专题分析、经营复盘等内部分析型报告
- **页面基础**：16:9 宽屏，纯白/浅灰背景，安全边距 0.40 in，内容区宽度 12.53 in
- **色彩体系**：主题蓝 `#00467F` / `#0070C0` 为主色，语义化着色（绿=达标/增长，红=预警/下降，橙=关注）
- **字号体系**：D0 封面 36-40pt → D1 主标题 22-24pt → D2 模块标题 16-18pt → D3 小节 14-15pt → B1 正文 13-14pt → B2 辅助 11-12pt → B3 注释 9-10pt
- **图表规范**：数据墨水比优先，去除冗余网格线；柱状图/折线图/饼图/瀑布图/KPI 卡片均有详细样式定义
- **表格风格**：无外框线 + 内部横线，表头深蓝底白字，数据行斑马纹，条件格式自动标红/绿
- **排版原则**：结论前置、层级分明、密度适中（每页文字不超过 200 字）、色彩语义化、对齐严格
- **ECharts 配置**：提供完整的主题色板、字体、坐标轴、图例、数据标签配置代码

## 关键概念

- [[concepts/PPT-Design-System]] — PPT 设计系统与企业内部分析报告规范
- [[concepts/Data-Ink-Ratio]] — 数据墨水比——去除非必要视觉元素
- [[concepts/Semantic-Color]] — 语义化着色——颜色承载信息而非装饰
- [[concepts/Executive-Summary-First]] — 结论前置——每页顶部给出明确结论

## 关键实体

- [[entities/Huyun]] — 规范作者

## 与现有页面的连接

- 与 [[summaries/PPT-WeekReview-4]] 形成实践对照——设计规范在实际周调度会 PPT 中的应用

## 来源链接

- 原始文件：`raw/prompt/ppt-design-system.md`
