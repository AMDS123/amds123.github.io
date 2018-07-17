---
layout: post
title: "LATE Ain'T Earley: A Faster Parallel Earley Parser"
date: 2018-07-16 00:50:00
categories: arXiv_CL
tags: arXiv_CL
author: Peter Ahrens, John Feser, Robin Hui
mathjax: true
---

* content
{:toc}

##### Abstract
We present the LATE algorithm, an asynchronous variant of the Earley algorithm for parsing context-free grammars. The Earley algorithm is naturally task-based, but is difficult to parallelize because of dependencies between the tasks. We present the LATE algorithm, which uses additional data structures to maintain information about the state of the parse so that work items may be processed in any order. This property allows the LATE algorithm to be sped up using task parallelism. We show that the LATE algorithm can achieve a 120x speedup over the Earley algorithm on a natural language task.

##### Abstract (translated by Google)
我们提出了LATE算法，这是用于解析无上下文语法的Earley算法的异步变体。 Earley算法自然是基于任务的，但由于任务之间的依赖性，很难并行化。我们提出了LATE算法，该算法使用其他数据结构来维护有关解析状态的信息，以便可以按任何顺序处理工作项。此属性允许使用任务并行性加速LATE算法。我们证明了LATE算法在自然语言任务上可以比Earley算法实现120倍的加速。

##### URL
[http://arxiv.org/abs/1807.05642](http://arxiv.org/abs/1807.05642)

##### PDF
[http://arxiv.org/pdf/1807.05642](http://arxiv.org/pdf/1807.05642)

