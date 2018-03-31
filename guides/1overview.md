原文出自：https://developers.google.com/blockly/guides/overview
# 介绍blockly
Blockly是一个库，它为Web和Android应用程序添加了一个可视代码编辑器。 Blockly编辑器使用互锁图形块来表示代码概念，如变量，逻辑表达式，循环等。 它允许用户应用编程原则，而不必担心命令行中的语法或闪烁光标的威胁。

> 注意:blockly是给开发人员使用的。用它开发的app是给学生使用的。Blockly是一个针对有经验的开发人员的复杂库。如果你只是希望去使用教育类的应用程序，而不是构建它们，请查看[这些]（https://www.google.com/edu/resources/computerscience/learning/）

## 构建一个Blockly应用程序

从用户的角度来看，Blockly是构建代码的直观，可视化的方式。从开发人员的角度来看，Blockly本质上是一个文本框，这个文本框的内容是：用户生成的，语法上正确的代码。Blockly可以将模块导出到多种语言，包括以下常用选项：

- JavaScript的
- python
- PHP
- LUA
- Dart

### 构建Blockly应用程序的大致步骤：

1. 集成Blockly编辑器。最简单的Blockly编辑器由两个部分组成：一个工具箱，用来保存各种类型的块。另一个是工作区，用户从工具箱中取出块，然后在工作区内去组装。详细了解如何在[Web](https://developers.google.com/blockly/guides/get-started/web)或[Android](https://developers.google.com/blockly/guides/get-started/android)中集成Blockly 。

2. 创建您的应用程序块。在应用中集成了Blockly之后，你需要为用户创建各种模块，然后将它们添加到Blockly工具箱中，以便用户通过这些模块进行编码。从[这里](https://developers.google.com/blockly/guides/create-custom-blocks/overview)了解如何创建自定义块。

3. 构建应用程序的其余部分。Blockly本身只是一种生成代码的方式，如何处理该代码应该由您的应用程序的核心来决定。


## Blockly的优势和其他选择
可视化编程环境越来越多，Blockly只是其中之一。决定在您的应用中使用哪一个编程环境是重要的一环，以下是选择Blockly的最大优势：

1. 可导出的代码。用户可以将基于块的程序提取为常用编程语言，并平滑过渡到基于文本的编程语言。

2. 开源。关于Blockly的一切都是开放的：您可以将其分解，破解，并将其用于您自己的网站和Android应用程序。

3. 扩展性。通过为您的API添加自定义块或删除不需要的块和功能来调整块以适应您的需求。

4. 高能。Blockly不是玩具。您可以执行复杂的编程任务，如在某一个块中进行标准偏差的计算。

5. 国际。Blockly已被翻译成40多种语言，包括阿拉伯语和希伯来语的右向风格的版本。

即便拥有上述优势，Blockly不是每个应用程序的解决方案。以下是您可能会发现的其他一些可视编辑器：

1. Scratch Blocks（https://scratch.mit.edu/developers）：由来自MIT的Scratch，基于Blockly代码库，Scratch Blocks提供了一个适合年轻学习者的简化编程模型。

2. Droplet（https://github.com/PencilCode/droplet）：支持Pencil Code的图形化编程编辑器，其独特之处在于可以将代码转换为块。

3. Snap（https://github.com/jmoenig/Snap--Build-Your-Own-Blocks）： Scratch灵感的图形化编程语言，它不是一个库，而是一个集成执行环境的完整应用程序。


