---
type: concept
title: 数据墨水比 (Data-Ink Ratio)
tags: [data-visualization, design, information-design, tufte]
related:
  - concepts/PPT-Design-System
  - concepts/Semantic-Color
source_files:
  - raw/prompt/ppt-design-system.md
source_count: 1
last_updated: 2026-04-20
confidence: high
---

## 定义

数据墨水比（Data-Ink Ratio）由 Edward Tufte 提出，指图表中用于呈现数据的"墨水"（视觉元素）与总墨水量的比例。核心原则：**最大化数据墨水，最小化非数据墨水**。

## 核心机制

### 非数据墨水（应去除）
- 冗余的网格线、背景色块
- 无意义的图例边框
- 重复的标签、3D 效果
- 渐变色填充、过重阴影

### 数据墨水（应保留/强化）
- 数据点本身（柱形、折线、饼图扇区）
- 必要的坐标轴和刻度
- 直接标注的数据标签
- 区分数据系列的色彩

## 应用与用例

在 [[summaries/PPT-Design-System]] 中，数据墨水比被具体化为：
- 隐藏纵向网格线，仅保留浅灰横向基准线
- 图例不放底部，避免与注释混淆
- 删除图表标题外的所有装饰性元素
- 数据标签直接显示在图上，而非依赖图例查找

## 与其他概念的关系

- 与 [[concepts/PPT-Design-System]] 的关系：设计系统是将数据墨水比原则落地到企业 PPT 场景的操作手册
- 与 [[concepts/Semantic-Color]] 的关系：色彩作为数据墨水的一部分，必须服务于信息传达而非装饰

## 来源引用

- (source: raw/prompt/ppt-design-system.md)
