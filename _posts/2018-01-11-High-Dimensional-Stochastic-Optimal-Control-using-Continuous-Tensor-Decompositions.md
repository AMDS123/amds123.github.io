---
layout: post
title: "High-Dimensional Stochastic Optimal Control using Continuous Tensor Decompositions"
date: 2018-01-11 06:22:57
categories: arXiv_RO
tags: arXiv_RO
author: Alex A. Gorodetsky, Sertac Karaman, Youssef M. Marzouk
mathjax: true
---

* content
{:toc}

##### Abstract
Motion planning and control problems are embedded and essential in almost all robotics applications. These problems are often formulated as stochastic optimal control problems and solved using dynamic programming algorithms. Unfortunately, most existing algorithms that guarantee convergence to optimal solutions suffer from the curse of dimensionality: the run time of the algorithm grows exponentially with the dimension of the state space of the system. We propose novel dynamic programming algorithms that alleviate the curse of dimensionality in problems that exhibit certain low-rank structure. The proposed algorithms are based on continuous tensor decompositions recently developed by the authors. Essentially, the algorithms represent high-dimensional functions (e.g., the value function) in a compressed format, and directly perform dynamic programming computations (e.g., value iteration, policy iteration) in this format. Under certain technical assumptions, the new algorithms guarantee convergence towards optimal solutions with arbitrary precision. Furthermore, the run times of the new algorithms scale polynomially with the state dimension and polynomially with the ranks of the value function. This approach realizes substantial computational savings in "compressible" problem instances, where value functions admit low-rank approximations. We demonstrate the new algorithms in a wide range of problems, including a simulated six-dimensional agile quadcopter maneuvering example and a seven-dimensional aircraft perching example. In some of these examples, we estimate computational savings of up to ten orders of magnitude over standard value iteration algorithms. We further demonstrate the algorithms running in real time on board a quadcopter during a flight experiment under motion capture.

##### Abstract (translated by Google)
运动规划和控制问题已经成为几乎所有机器人应用的基础和必要条件。这些问题通常被表述为随机最优控制问题，并使用动态规划算法来解决。不幸的是，大多数保证收敛到最优解的算法都受到维数灾难的影响：算法的运行时间随着系统状态空间的维数呈指数增长。我们提出了新颖的动态规划算法，以减少展现某些低秩结构的问题中的维度诅咒。所提出的算法是基于作者最近开发的连续张量分解。本质上，算法以压缩格式表示高维函数（例如，值函数），并且以这种格式直接执行动态编程计算（例如，值迭代，策略迭代）。在一定的技术假设下，新算法保证了以任意精度收敛到最优解。此外，新算法的运行时间随着状态维度而多项式地缩放并且与值函数的秩次多项式地缩放。这种方法在“可压缩”问题实例中实现了实质性的计算节省，其中值函数允许低秩逼近。我们在广泛的问题中展示了新的算法，其中包括一个模拟六维敏捷四旋翼飞行器机动示例和一个七维飞机栖息示例。在这些例子中的一些例子中，我们估计在标准值迭代算法上多达十个数量级的计算节省。我们进一步演示了在运动捕捉下的飞行实验期间在四轴飞行器上实时运行的算法。

##### URL
[http://arxiv.org/abs/1611.04706](http://arxiv.org/abs/1611.04706)

##### PDF
[http://arxiv.org/pdf/1611.04706](http://arxiv.org/pdf/1611.04706)

