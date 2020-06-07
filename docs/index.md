当前社区有很多 React 源码分析文章，但不够成体系，内容质量也参差不齐。基于此原因，本书意在通俗易懂、高质量的讲解React源码体系。为了达到这个目标，在行文上，本书会遵循：

1. 不预设观点 —— 所有观点来自React核心团队成员在公开场合发表的内容。
2. 辅助资料详尽 —— 提供丰富的Demo、参考资源。
3. 保持更新 —— 在React版本更新后会及时补充。当前版本`v16.13.1`

## 章节说明
从章节列表可以看到，我们并没有从如`ReactDOM.render`、`this.setState`或`hooks`等这样日常开发耳熟能详的`API`入手，而是从**理念**这样比较高的抽象层次开始，这是有意为之的。

由理念推导出架构，再讲解架构的每个部分是如何互相配合完成UI渲染，最后讲解具体的`API`是如何接入这套架构。这是个自顶向下、抽象程度递减的过程。如果直接讲解API，那么很容易陷入源码的汪洋大海。

## 章节列表

### 第一章 前置知识

✅ React理念

✅ 老的React架构

✅ 新的React架构

✅ 源码的文件结构

✅ 深入理解JSX

### 第二章 整体流程概览

:black_square_button: Fiber架构

:black_square_button: Mount

:black_square_button: Update

### 第三章 协调流程

:black_square_button: key

:black_square_button: 单一组件协调

:black_square_button: 多组件协调

### 第四章 渲染流程

### 第五章 调度流程