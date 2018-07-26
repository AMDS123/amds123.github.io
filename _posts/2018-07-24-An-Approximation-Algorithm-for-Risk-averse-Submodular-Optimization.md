---
layout: post
title: "An Approximation Algorithm for Risk-averse Submodular Optimization"
date: 2018-07-24 21:10:50
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Lifeng Zhou, Pratap Tokekar
mathjax: true
---

* content
{:toc}

##### Abstract
We study the problem of incorporating risk while making combinatorial decisions under uncertainty. We formulate a discrete submodular maximization problem for selecting a set using Conditional-Value-at-Risk (CVaR), a risk metric commonly used in financial analysis. While CVaR has recently been used in optimization of linear costs functions in robotics, we take the first stages towards extending this to discrete submodular optimization and provide several positive results. Specifically, we propose the Sequential Greedy Algorithm that provides an approximation guarantee on finding the maxima of the CVaR cost function under a matroidal constraint. The approximation guarantee shows that the solution produced by our algorithm is within a constant factor of the optimal and an additive term that depends on the optimal. Our analysis uses the curvature of the submodular set function, and proves that the algorithm runs in polynomial time. This formulates a number of combinatorial optimization problems that appear in robotics. We use two such problems, vehicle assignment under uncertainty for mobility-on-demand and sensor selection with failures for environmental monitoring, as case studies to demonstrate the efficacy of our formulation.

##### Abstract (translated by Google)
我们研究了在不确定性下进行组合决策时融入风险的问题。我们使用条件风险值（CVaR）（财务分析中常用的风险度量）来制定离散子模块最大化问题，以选择集合。虽然CVaR最近已被用于优化机器人中的线性成本函数，但我们将第一阶段扩展到离散子模块优化，并提供了几个积极的结果。具体来说，我们提出了顺序贪心算法，它提供了在matroidal约束下找到CVaR成本函数的最大值的近似保证。近似保证表明，我们的算法产生的解决方案在最优的常数因子和取决于最优的附加项内。我们的分析使用子模块集函数的曲率，并证明该算法在多项式时间内运行。这制定了机器人中出现的许多组合优化问题。我们使用两个这样的问题，即在不确定性下的车辆分配对于按需移动和传感器选择与环境监测失败，作为案例研究来证明我们的配方的功效。

##### URL
[http://arxiv.org/abs/1807.09358](http://arxiv.org/abs/1807.09358)

##### PDF
[http://arxiv.org/pdf/1807.09358](http://arxiv.org/pdf/1807.09358)

