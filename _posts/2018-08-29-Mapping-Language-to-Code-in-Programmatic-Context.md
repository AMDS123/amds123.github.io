---
layout: post
title: "Mapping Language to Code in Programmatic Context"
date: 2018-08-29 00:08:25
categories: arXiv_CL
tags: arXiv_CL
author: Srinivasan Iyer, Ioannis Konstas, Alvin Cheung, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
Source code is rarely written in isolation. It depends significantly on the programmatic context, such as the class that the code would reside in. To study this phenomenon, we introduce the task of generating class member functions given English documentation and the programmatic context provided by the rest of the class. This task is challenging because the desired code can vary greatly depending on the functionality the class provides (e.g., a sort function may or may not be available when we are asked to "return the smallest element" in a particular member variable list). We introduce CONCODE, a new large dataset with over 100,000 examples consisting of Java classes from online code repositories, and develop a new encoder-decoder architecture that models the interaction between the method documentation and the class environment. We also present a detailed error analysis suggesting that there is significant room for future work on this task.

##### Abstract (translated by Google)
源代码很少孤立地编写。它在很大程度上取决于程序化上下文，例如代码所在的类。为了研究这种现象，我们引入了生成类成员函数的任务，给出了英文文档和类的其余部分提供的编程上下文。该任务具有挑战性，因为期望的代码可以根据类提供的功能而有很大变化（例如，当我们被要求“返回特定成员变量列表中的最小元素”时，排序函数可能可用或者可能不可用）。我们介绍了CONCODE，这是一个新的大型数据集，包含来自在线代码库的Java类的100,000多个示例，并开发了一种新的编码器 - 解码器架构，用于模拟方法文档和类环境之间的交互。我们还提供了详细的错误分析，表明此任务的未来工作有很大的空间。

##### URL
[http://arxiv.org/abs/1808.09588](http://arxiv.org/abs/1808.09588)

##### PDF
[http://arxiv.org/pdf/1808.09588](http://arxiv.org/pdf/1808.09588)

