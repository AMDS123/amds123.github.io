---
layout: post
title: "Learning to Branch"
date: 2018-03-27 15:47:24
categories: arXiv_AI
tags: arXiv_AI
author: Maria-Florina Balcan, Travis Dick, Tuomas Sandholm, Ellen Vitercik
mathjax: true
---

* content
{:toc}

##### Abstract
Tree search algorithms, such as branch-and-bound, are the most widely used tools for solving combinatorial and nonconvex problems. For example, they are the foremost method for solving (mixed) integer programs and constraint satisfaction problems. Tree search algorithms recursively partition the search space to find an optimal solution. In order to keep the tree size small, it is crucial to carefully decide, when expanding a tree node, which question (typically variable) to branch on at that node in order to partition the remaining space. Numerous partitioning techniques (e.g., variable selection) have been proposed, but there is no theory describing which technique is optimal. We show how to use machine learning to determine an optimal weighting of any set of partitioning procedures for the instance distribution at hand using samples from the distribution. We provide the first sample complexity guarantees for tree search algorithm configuration. These guarantees bound the number of samples sufficient to ensure that the empirical performance of an algorithm over the samples nearly matches its expected performance on the unknown instance distribution. This thorough theoretical investigation naturally gives rise to our learning algorithm. Via experiments, we show that learning an optimal weighting of partitioning procedures can dramatically reduce tree size, and we prove that this reduction can even be exponential. Through theory and experiments, we show that learning to branch is both practical and hugely beneficial.

##### Abstract (translated by Google)
树搜索算法（如分支定界）是解决组合问题和非凸问题的最广泛使用的工具。例如，它们是解决（混合）整数程序和约束满足问题的最重要的方法。树搜索算法递归地划分搜索空间以找到最佳解决方案。为了保持较小的树大小，在扩展树节点时仔细决定要在该节点上分支的哪个问题（通常是变量）以分区剩余空间是至关重要的。许多分区技术（例如变量选择）已经被提出，但是没有理论描述哪种技术是最优的。我们展示了如何使用机器学习为使用分布样本的实例分布确定任何分割过程集的最优加权。我们为树搜索算法配置提供了第一个样本复杂度保证。这些保证限制了样本数量，足以确保样本上的算法的经验性能几乎与未知实例分布上的预期性能相匹配。这种彻底的理论研究自然会产生我们的学习算法。通过实验，我们发现学习分区过程的最优权重可以大大减少树的大小，并且我们证明这种减少甚至可以是指数级的。通过理论和实验，我们表明，学习分支是既实用又非常有益的。

##### URL
[https://arxiv.org/abs/1803.10150](https://arxiv.org/abs/1803.10150)

##### PDF
[https://arxiv.org/pdf/1803.10150](https://arxiv.org/pdf/1803.10150)

