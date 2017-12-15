---
layout: post
title: "Efficient non-greedy optimization of decision trees"
date: 2015-11-12 20:32:28
categories: arXiv_CV
tags: arXiv_CV Optimization Classification Prediction Gradient_Descent
author: Mohammad Norouzi, Maxwell D. Collins, Matthew Johnson, David J. Fleet, Pushmeet Kohli
mathjax: true
---

* content
{:toc}

##### Abstract
Decision trees and randomized forests are widely used in computer vision and machine learning. Standard algorithms for decision tree induction optimize the split functions one node at a time according to some splitting criteria. This greedy procedure often leads to suboptimal trees. In this paper, we present an algorithm for optimizing the split functions at all levels of the tree jointly with the leaf parameters, based on a global objective. We show that the problem of finding optimal linear-combination (oblique) splits for decision trees is related to structured prediction with latent variables, and we formulate a convex-concave upper bound on the tree's empirical loss. The run-time of computing the gradient of the proposed surrogate objective with respect to each training exemplar is quadratic in the the tree depth, and thus training deep trees is feasible. The use of stochastic gradient descent for optimization enables effective training with large datasets. Experiments on several classification benchmarks demonstrate that the resulting non-greedy decision trees outperform greedy decision tree baselines.

##### Abstract (translated by Google)
决策树和随机森林被广泛用于计算机视觉和机器学习。用于决策树归纳的标准算法根据一些拆分标准一次优化一个节点的拆分函数。这个贪婪的过程往往会导致次优树。在本文中，我们提出了一个基于全局目标的叶子参数优化树的各级分裂函数的算法。我们证明为决策树寻找最优线性组合（倾斜）分裂的问题与具有潜在变量的结构化预测有关，并且我们在树的经验损失上制定了一个凸凹上界。针对每个训练样本计算所提出的替代目标的梯度的运行时间在树深度上是二次的，因此训练深度树是可行的。使用随机梯度下降法进行优化可以使用大型数据集进行有效的训练。在几个分类基准上的实验表明，所得到的非贪婪决策树优于贪婪的决策树基线。

##### URL
[https://arxiv.org/abs/1511.04056](https://arxiv.org/abs/1511.04056)

##### PDF
[https://arxiv.org/pdf/1511.04056](https://arxiv.org/pdf/1511.04056)

