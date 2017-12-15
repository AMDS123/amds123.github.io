---
layout: post
title: "Truncated Max-of-Convex Models"
date: 2016-12-03 15:56:12
categories: arXiv_CV
tags: arXiv_CV
author: Pankaj Pansari, M. Pawan Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
Truncated convex models (TCM) are a special case of pairwise random fields that have been widely used in computer vision. However, by restricting the order of the potentials to be at most two, they fail to capture useful image statistics. We propose a natural generalization of TCM to high-order random fields, which we call truncated max-of-convex models (TMCM). The energy function of TMCM consistsof two types of potentials: (i) unary potential, which has no restriction on its form; and (ii) clique potential, which is the sum of the m largest truncated convex distances over all label pairs in a clique. The use of a convex distance function encourages smoothness, while truncation allows for discontinuities in the labeling. By using m > 1, TMCM provides robustness towards errors in the definition of the cliques. In order to minimize the energy function of a TMCM over all possible labelings, we design an efficient st-MINCUT based range expansion algorithm. We prove the accuracy of our algorithm by establishing strong multiplicative bounds for several special cases of interest. Using synthetic and standard real data sets, we demonstrate the benefit of our high-order TMCM over pairwise TCM, as well as the benefit of our range expansion algorithm over other st-MINCUT based approaches.

##### Abstract (translated by Google)
截断凸模型（TCM）是计算机视觉中广泛使用的成对随机场的一个特例。但是，通过限制电位的顺序最多为两个，它们不能捕获有用的图像统计。我们提出了TCM的高阶随机场的一种自然推广，我们称之为截断最大凸模型（TMCM）。 TMCM的能源功能包括两种潜力：（一）一元潜力，其形式没有限制;和（ii）集团势，它是集团中所有标签对上的m个最大截断凸距之和。凸距函数的使用可以提高平滑度，而截断可以减少标签的不连续性。通过使用m> 1，TMCM提供了对派系定义中的错误的鲁棒性。为了最小化TMCM在所有可能的标签上的能量函数，我们设计了一个高效的基于st-MINCUT的距离扩展算法。我们通过为几个感兴趣的特殊情况建立强乘法界限来证明算法的准确性。使用合成的和标准的实际数据集，我们证明了我们的高阶TMCM优于成对TCM的好处，以及我们的范围扩展算法相对于其他基于st-MINCUT的方法的好处。

##### URL
[https://arxiv.org/abs/1512.07815](https://arxiv.org/abs/1512.07815)

##### PDF
[https://arxiv.org/pdf/1512.07815](https://arxiv.org/pdf/1512.07815)

