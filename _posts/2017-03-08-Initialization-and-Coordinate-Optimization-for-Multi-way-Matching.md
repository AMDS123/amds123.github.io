---
layout: post
title: "Initialization and Coordinate Optimization for Multi-way Matching"
date: 2017-03-08 07:32:24
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Da Tang, Tony Jebara
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the problem of consistently matching multiple sets of elements to each other, which is a common task in fields such as computer vision. To solve the underlying NP-hard objective, existing methods often relax or approximate it, but end up with unsatisfying empirical performance due to a misaligned objective. We propose a coordinate update algorithm that directly optimizes the target objective. By using pairwise alignment information to build an undirected graph and initializing the permutation matrices along the edges of its Maximum Spanning Tree, our algorithm successfully avoids bad local optima. Theoretically, with high probability our algorithm guarantees an optimal solution under reasonable noise assumptions. Empirically, our algorithm consistently and significantly outperforms existing methods on several benchmark tasks on real datasets.

##### Abstract (translated by Google)
我们考虑一致匹配多组元素的问题，这是计算机视觉等领域的一个常见任务。为了解决潜在的NP难度目标，现有的方法往往放宽或近似，但由于目标错位而导致经验表现不理想。我们提出了一个坐标更新算法，直接优化目标的目标。通过使用成对比对信息来构建无向图，并沿着其最大生成树的边缘初始化置换矩阵，我们的算法成功地避免了局部最优解。理论上，我们的算法很有可能在合理的噪声假设下保证最优解。从经验上讲，我们的算法在真实数据集上的几个基准测试任务中始终如一地大大优于现有方法。

##### URL
[https://arxiv.org/abs/1611.00838](https://arxiv.org/abs/1611.00838)

##### PDF
[https://arxiv.org/pdf/1611.00838](https://arxiv.org/pdf/1611.00838)

