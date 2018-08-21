---
layout: post
title: "Triangle Lasso for Simultaneous Clustering and Optimization in Graph Datasets"
date: 2018-08-20 16:31:30
categories: arXiv_CV
tags: arXiv_CV Attention Optimization
author: Yawei Zhao, Kai Xu, Xinwang Liu, En Zhu, Xinzhong Zhu, Jianping Yin
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, network lasso has drawn many attentions due to its remarkable performance on simultaneous clustering and optimization. However, it usually suffers from the imperfect data (noise, missing values etc), and yields sub-optimal solutions. The reason is that it finds the similar instances according to their features directly, which is usually impacted by the imperfect data, and thus returns sub-optimal results. In this paper, we propose triangle lasso to avoid its disadvantage. Triangle lasso finds the similar instances according to their neighbours. If two instances have many common neighbours, they tend to become similar. Although some instances are profiled by the imperfect data, it is still able to find the similar counterparts. Furthermore, we develop an efficient algorithm based on Alternating Direction Method of Multipliers (ADMM) to obtain a moderately accurate solution. In addition, we present a dual method to obtain the accurate solution with the low additional time consumption. We demonstrate through extensive numerical experiments that triangle lasso is robust to the imperfect data. It usually yields a better performance than the state-of-the-art method when performing data analysis tasks in practical scenarios.

##### Abstract (translated by Google)
最近，网络套索因其在同步聚类和优化方面的卓越表现而备受关注。然而，它通常会受到不完美数据（噪声，缺失值等）的影响，并产生次优解决方案。原因是它直接根据其特征找到相似的实例，这通常受到不完美数据的影响，从而返回次优结果。在本文中，我们提出三角套索，以避免其缺点。三角套索根据邻居发现类似的情况。如果两个实例有许多共同的邻居，它们往往会变得相似。尽管有些实例是由不完美的数据描述的，但它仍然能够找到类似的对应物。此外，我们开发了一种基于交替方向乘法器（ADMM）的高效算法，以获得适度精确的解。此外，我们提出了一种双重方法，以获得具有较低额外时间消耗的精确解决方案。我们通过广泛的数值实验证明，三角套索对于不完美的数据是稳健的。在实际场景中执行数据分析任务时，它通常比最先进的方法产生更好的性能。

##### URL
[http://arxiv.org/abs/1808.06556](http://arxiv.org/abs/1808.06556)

##### PDF
[http://arxiv.org/pdf/1808.06556](http://arxiv.org/pdf/1808.06556)

