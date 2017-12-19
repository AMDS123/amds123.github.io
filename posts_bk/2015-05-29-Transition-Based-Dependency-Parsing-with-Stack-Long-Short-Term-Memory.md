---
layout: post
title: "Transition-Based Dependency Parsing with Stack Long Short-Term Memory"
date: 2015-05-29 14:58:12
categories: arXiv_CL
tags: arXiv_CL Face Embedding RNN
author: Chris Dyer, Miguel Ballesteros, Wang Ling, Austin Matthews, Noah A. Smith
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a technique for learning representations of parser states in transition-based dependency parsers. Our primary innovation is a new control structure for sequence-to-sequence neural networks---the stack LSTM. Like the conventional stack data structures used in transition-based parsing, elements can be pushed to or popped from the top of the stack in constant time, but, in addition, an LSTM maintains a continuous space embedding of the stack contents. This lets us formulate an efficient parsing model that captures three facets of a parser's state: (i) unbounded look-ahead into the buffer of incoming words, (ii) the complete history of actions taken by the parser, and (iii) the complete contents of the stack of partially built tree fragments, including their internal structures. Standard backpropagation techniques are used for training and yield state-of-the-art parsing performance.

##### Abstract (translated by Google)
我们提出了一种在基于转换的依赖关系解析器中学习解析器状态表示的技术。我们的主要创新是序列 - 序列神经网络 - 堆栈LSTM的新的控制结构。像在基于转换的解析中使用的传统堆栈数据结构一样，元素可以在时间上从堆栈的顶部被推入或弹出，但是，另外，LSTM保持堆栈内容的连续空间嵌入。这使我们能够制定出一个高效的解析模型，它捕获解析器状态的三个方面：（i）无界限的预测到输入单词的缓冲区，（ii）解析器所采取的动作的完整历史记录，以及（iii）部分构建的碎片堆栈的内容，包括它们的内部结构。标准的反向传播技术被用于训练并产生最先进的解析性能。

##### URL
[https://arxiv.org/abs/1505.08075](https://arxiv.org/abs/1505.08075)

##### PDF
[https://arxiv.org/pdf/1505.08075](https://arxiv.org/pdf/1505.08075)

