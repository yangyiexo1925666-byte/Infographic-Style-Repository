# 02 主题内容分析

## 目标

通过与大模型进行结构化讨论，把宽泛主题转化为可被数据支撑、可被视觉表达的信息主题，并确定适合的类型标签组合。

## 与大模型讨论的步骤

1. 输入选题背景、调研材料、目标受众和设计限制。
2. 拆解主题中的对象、属性、事件、地点、时间、数量、关系与观点。
3. 识别主导数据逻辑：编年型、层级型、编目型、字母表型、地理图形型；必要时标记混合逻辑。
4. 判断表现媒介：数据图表、文字/列表、照片、插画、地图、图解、图标/象形符号、档案材料等。
5. 判断视觉风格：平面矢量、编辑插画、照片纪实、档案拼贴、信息设计、三维/等距、手绘等。风格是视觉语言，不等于数据逻辑。
6. 判断具体图表/信息形式：词云、时间轴、地图、矩阵、树状图、排行、比例图、流程图、图鉴、照片标注、文字型信息图等。
7. 评估每种组合的数据可得性、叙事能力、视觉适配性与误读风险。
8. 输出推荐方案、备选方案与不推荐方案，并说明依据。

## 标签体系（分层标注，避免混为一谈）

- **数据逻辑标签：** chronological、hierarchical、catalog、alphabetical、geographic、network、process、comparative。
- **信息形式标签：** mixed charts、informational/list、timeline、map infographic、pictorial infographic、photo infographic、typographic infographic。
- **图表/图解标签：** word cloud、bar chart、line chart、scatter plot、treemap、matrix、flow chart、Sankey、calendar、small multiples 等。
- **媒介标签：** text、photograph、illustration、icon、diagram、map、chart、archive material。
- **风格标签：** flat vector、editorial、documentary、minimal、Swiss grid、hand-drawn、collage、isometric、3D 等。
- **叙事标签：** evolution、comparison、classification、ranking、distribution、journey、cause-and-effect（需证据）、profile、explainer。

## 大模型讨论提示词

```text
你是信息设计研究与数据叙事顾问。请基于我提供的选题资料，不要直接给出单一风格结论。
请依次分析：
1. 主题对象、核心问题、范围和目标受众；
2. 可能的数据逻辑（编年、层级、编目、字母表、地理及混合逻辑）；
3. 适合的信息形式（混合图表、文字列表、时间轴、照片型、地图型、图解型等）；
4. 适合的统计图表和非统计图解（例如词云仅用于词频/关键词概览，不替代严谨比较）；
5. 平面、照片、插画、档案拼贴等媒介与风格的适配性；
6. 每种方案需要哪些字段、数据来源和计算；
7. 视觉叙事的可能路径及误读风险。
最后给出 3 套不同方向的方案，用“适配度、数据可得性、叙事清晰度、设计表现力、制作成本”逐项比较，并推荐一套，说明理由和待验证事项。
所有事实与推断分开；没有材料支持的内容标注待核实。
```

## 方案决策表

| 方案 | 主数据逻辑 | 信息形式 | 媒介/风格 | 核心图表 | 所需字段 | 风险 |
|---|---|---|---|---|---|---|
| A | | | | | | |
| B | | | | | | |
| C | | | | | | |

## 阶段出口

确定主导逻辑、辅助逻辑、媒介风格标签、图表标签、叙事命题及需要搜集的数据字段。
