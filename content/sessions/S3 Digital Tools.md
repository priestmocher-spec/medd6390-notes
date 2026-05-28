# S3 Digital Tools

**文件：** Digital Tools 2026.pdf（19 页）

## 本讲定位

属于课程 "Building Blocks" 模块的 Tools & Representations 部分。在 [[S1 Introduction]] 和 [[S2 Task Design]] 建立了任务设计的理论基础后，本讲聚焦于数字工具如何改变数学教学。核心不是"用什么软件"，而是两个理论问题：(1) 教师需要什么知识才能有效整合技术（TPACK）；(2) 学生如何将技术工具转化为自己的学习工具（instrumental genesis）。

## 核心内容 1：TPACK 框架

### TPACK 的构成 (Mishra & Koehler, 2006)

TPACK = Technological Pedagogical Content Knowledge，是三种基础知识的交叉：

- **CK (Content Knowledge)**：学科知识本身
- **PK (Pedagogical Knowledge)**：一般性教学知识
- **TK (Technological Knowledge)**：技术操作和理解能力

两两交叉产生：
- **PCK (Pedagogical Content Knowledge)**：Shulman (1986) 的经典概念，知道如何教特定学科内容
- **TCK (Technological Content Knowledge)**：知道技术如何表征和改变学科内容
- **TPK (Technological Pedagogical Knowledge)**：知道技术如何支持教学策略

三者交叉的核心：
- **TPACK**：知道如何用特定技术来教特定内容，使学生更好地理解

### TPACK 对数学教学的意义

拥有 TPACK 意味着教师不仅会操作 GeoGebra，还知道什么时候用 GeoGebra 比不用更好，以及如何设计利用 GeoGebra 动态特性的任务。这不是三种知识的简单相加，而是一种整合性的专业判断。

## 核心内容 2：Instrumental Genesis

### Rabardel 的 Instrumental Approach

Instrumental genesis（工具生成）源于法国学者 Rabardel 的工作，区分了两个关键概念：

- **Artifact（制品）**：工具本身，作为物质或符号客体（如 GeoGebra 软件本身）
- **Instrument（工具/乐器）**：artifact + 使用者的 schemes（使用方案），是人与 artifact 互动后形成的心理构造

从 artifact 到 instrument 的转化过程就是 instrumental genesis。这个过程有两个方向：

- **Instrumentation（工具化）**：工具塑造使用者。工具的功能和限制影响使用者的思考方式和行为。例：使用计算器的学生倾向于把计算当作独立步骤而非推理的一部分
- **Instrumentalization（使用者化）**：使用者塑造工具。使用者发现工具的新用途、定制工具、赋予工具超出设计者意图的功能。例：学生用 GeoGebra 的 trace 功能来探索函数图像的变化趋势

### 对数学教学的启示

1. 给学生一个软件不等于学生就获得了学习工具。需要时间让 instrumental genesis 发生
2. 同一个 artifact 在不同学生手中可能生成不同的 instruments
3. 教师需要预判工具可能如何塑造学生的思维（instrumentation 的方向）
4. 任务设计需要考虑工具的 affordances（可供性）和 constraints（限制性）

### Affordances 和 Constraints

- **Affordances**：工具使可能的行为。如 GeoGebra 的 drag 功能让学生可以连续变化几何图形，这是纸笔做不到的
- **Constraints**：工具施加的限制。如计算器只显示有限小数位、GeoGebra 中的点只能在预设的对象上移动

好的任务设计需要利用 affordances 同时意识到 constraints 的影响。

### Instrumental Orchestration

教师在课堂中协调学生使用数字工具的方式。包括如何安排学生与工具的互动顺序、何时全班共享屏幕讨论、何时让学生独立探索。

## 核心内容 3：Dynamic Geometry 和 GeoGebra

### 动态几何的教学价值

动态几何环境（DGE）的独特教学价值在于 dragging（拖拽）。通过拖拽，学生可以：
- 在连续变化中观察不变性（invariance）
- 快速生成大量例子来检验猜想
- 区分偶然的视觉特征和本质的几何性质
- 在 exploration 中发展 conjecture（猜想）

### 拖拽的类型（Arzarello et al., 2002）

- **Wandering dragging**：随意拖动，探索性地观察变化
- **Guided dragging**：有目的地拖动以检验特定猜想
- **Validation dragging**：拖动以验证已经形成的数学命题

### GeoGebra 的功能

GeoGebra 集成了动态几何（geometry view）、函数图像（algebra/graphing view）、电子表格（spreadsheet）、CAS（Computer Algebra System）和 3D 图形。免费开源，支持在线使用。

### Multiple Representations（多重表征）

数字工具的核心优势之一是同时呈现代数、几何、数值等表征并动态链接。改变一种表征时，其他表征同步更新。这让学生可以在不同表征之间建立联系，与 [[S5 Mathematical Concepts]] 中 Bruner 和 Lesh 的表征理论对应。

## 核心内容 4：Desmos

### Desmos 的特色

Desmos 是基于浏览器的图形计算器和课堂活动平台，特色包括：
- 交互式图形探索
- Teacher Dashboard 让教师实时看到所有学生的屏幕
- Activity Builder 让教师创建自定义的探索序列
- Computation Layer 支持复杂的条件反馈

Desmos 在函数和统计方面的交互体验流畅，Teacher Dashboard 对课堂管理友好。与 GeoGebra 互补使用。

## 核心内容 5：Computational Thinking 和 Coding

### Computational Thinking 在数学中的角色

Computational thinking（计算思维）不等于学编程。核心要素包括：
- **Decomposition（分解）**：把复杂问题分解为小问题
- **Pattern recognition（模式识别）**：识别结构和规律
- **Abstraction（抽象）**：提取关键特征，忽略无关细节
- **Algorithm design（算法设计）**：设计逐步解决方案

这些要素与数学思维高度重叠。数学本身就包含大量的 decomposition（因式分解）、pattern recognition（数列规律）、abstraction（代数泛化）和 algorithm design（计算方法）。

### Coding 与数学教学的整合

将编程活动整合到数学教学中的可能性：
- 用 Scratch 或 Python 画几何图案来理解角度和旋转
- 用循环结构理解数列和迭代
- 用条件语句理解分类和逻辑
- 用变量理解代数中的未知数

编程不是替代数学，而是提供另一种探索数学的 representation 方式。

## 核心内容 6：教师在技术整合中的角色

### 技术不是自动改善教学的

关键取决于教师如何使用技术。技术整合不等于用技术做传统任务，而是设计只有通过技术才可能的数学活动。工具选择应基于数学目标，而非技术的新颖性。

### 工具选择的判断标准

- 这个工具是否让学生接触到了用其他方式难以接触到的数学？
- 工具的 affordances 是否支持了任务的数学目标？
- 工具的 constraints 是否可能产生误导性的理解？
- 学生需要多少 instrumental genesis 时间？

## 关键学者

- Mishra, P. & Koehler, M. J. (2006)：TPACK 框架
- Shulman, L. (1986)：PCK（Pedagogical Content Knowledge）
- Rabardel, P.：instrumental genesis（artifact vs instrument, instrumentation vs instrumentalization）
- Trouche, L. (2004)：instrumental orchestration
- Drijvers, P. et al. (2010)：instrumental genesis 在数学教育中的应用
- Arzarello, F. et al. (2002)：dragging 的类型（wandering / guided / validation）
- Laborde, C. (2001)：动态几何环境中的任务设计
- Hoyles, C. & Noss, R. (2003)：数字技术与数学学习
- Wing, J. (2006)：computational thinking
- Papert, S.：Logo 和 constructionism，用编程学数学

## 交叉引用

- [[S1 Introduction]]：Askew 的 Tools 维度（Contexts-Models-Actions-Symbols）为本讲的技术工具讨论提供了更广的框架
- [[S2 Task Design]]：技术工具改变了任务设计的可能性。GeoGebra 的拖拽让 variation 可以被直接操作。Watson & Mason 的任务变换策略可在数字环境中更灵活实施
- [[S4 Maths Talk]]：技术环境改变了课堂话语模式。Desmos Teacher Dashboard 让教师可以选择学生的屏幕来引发讨论，支持 Smith & Stein 的 Five Practices（selecting, sequencing）
- [[S5 Mathematical Concepts]]：Bruner 的三种表征（enactive, iconic, symbolic）与数字工具的多表征功能相呼应。GeoGebra 同时展示代数和几何表征，支持 Lesh Translation Model 中表征间的翻译
- [[S6 Mathematical Thinking]]：computational thinking 与 mathematical thinking 的要素（conjecturing, generalising）高度重叠
- [[S7 Mastery and Variation]]：GeoGebra 的拖拽功能是实现 variation theory 的理想工具，可以系统展示 dimensions of variation 和 range of change
