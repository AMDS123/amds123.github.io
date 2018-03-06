---
layout: post
title: "DAGs with NO TEARS: Smooth Optimization for Structure Learning"
date: 2018-03-04 21:09:13
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Xun Zheng, Bryon Aragam, Pradeep Ravikumar, Eric P. Xing
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the structure of directed acyclic graphs (DAGs, also known as Bayesian networks) is a challenging problem since the search space of DAGs is combinatorial and scales superexponentially with the number of nodes. Existing approaches rely on various local heuristics for enforcing the acyclicity constraint and are not well-suited to general purpose optimization packages for their solution. In this paper, we introduce a fundamentally different strategy: We formulate the structure learning problem as a smooth, constrained optimization problem over real matrices that avoids this combinatorial constraint entirely. This is achieved by a novel characterization of acyclicity that is not only smooth but also exact. The resulting nonconvex, constrained program involves smooth functions whose gradients are easy to compute and only involve elementary matrix operations. By using existing black-box optimization routines, our method uses global search to find an optimal DAG and can be implemented in about 50 lines of Python and outperforms existing methods without imposing any structural constraints.

##### Abstract (translated by Google)
估计有向无环图（DAG，也称为贝叶斯网络）的结构是一个具有挑战性的问题，因为DAG的搜索空间是组合的并且与节点的数目成超指数地缩放。现有的方法依赖于各种本地启发式方法来实施非循环约束，并且不适合用于其解决方案的通用优化包。在本文中，我们引入了一个根本不同的策略：我们将结构学习问题作为一个平滑的约束优化问题，在真正的矩阵上完全避免这种组合约束。这是通过非循环的新特征来实现的，它不仅平滑而且精确。由此产生的非凸约束程序涉及平滑函数，其梯度易于计算并且仅涉及基本矩阵运算。通过使用现有的黑盒子优化例程，我们的方法使用全局搜索来寻找最佳的DAG，并且可以在大约50行Python中实现，并且在不施加任何结构限制的情况下胜过现有方法。

##### URL
[http://arxiv.org/abs/1803.01422](http://arxiv.org/abs/1803.01422)

##### PDF
[http://arxiv.org/pdf/1803.01422](http://arxiv.org/pdf/1803.01422)

