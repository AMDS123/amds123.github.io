---
layout: post
title: "Constant Factor Time Optimal Multi-Robot Routing on High-Dimensional Grids in Mostly Sub-Quadratic Time"
date: 2018-01-31 14:40:29
categories: arXiv_RO
tags: arXiv_RO
author: Jingjin Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Let $G = (V, E)$ be an $m_1 \times \ldots \times m_k$ grid. Assuming that each $v \in V$ is occupied by a robot and a robot may move to a neighboring vertex in a step via synchronized rotations along cycles of $G$, we first establish that the arbitrary reconfiguration of labeled robots on $G$ can be performed in $O(k\sum_i m_i)$ makespan and requires $O(|V|^2)$ running time in the worst case and $o(|V|^2)$ when $G$ is non-degenerate (i.e., nearly one dimensional). The resulting algorithm, \isag, provides average case $O(1)$-approximate (i.e., constant factor) time optimality guarantee. In the case when all dimensions are of similar size $O(|V|^{\frac{1}{k}})$, the running time of \isag approaches a linear $O(|V|)$. Define $d_g(p)$ as the largest distance between individual initial and goal configurations over all robots for a given problem instance $p$, building on \isag, we develop the \pafalgo (\paf) algorithm that computes $O(d_g(p))$ makespan solutions for $k = 2, 3$ using mostly $o(|V|^2)$ running time. \paf provides worst case $O(1)$-approximation regarding solution time optimality. We note that the worst case running time for the problem is $\Omega(|V|^2)$.

##### Abstract (translated by Google)
令$ G =（V，E）$为$ m_1 \ times \ ldots \ times m_k $格。假设V $中的每个$ v \被一个机器人占用，并且一个机器人可以通过沿着$ G $的周期的同步旋转在一个步骤中移动到邻近的顶点，我们首先确定在$ G $上标记的机器人的任意重新配置可以在$ O（k \ sum_i m_i）$ makespan中执行，并且在$ G（$ V $ ^ $）$ $ $（$ V $ ^ $）退化（即近一维）。得到的算法\ isag提供平均情况$ O（1）$  - 近似（即，常数因子）时间最优性保证。在所有维度都是相似大小$ O（| V | ^ {\ frac {1} {k}}）$的情况下，\ isag的运行时间接近线性$ O（| V |）$。定义$ d_g（p）$作为给定问题实例上所有机器人的初始配置和目标配置之间的最大距离$ p $，基于\ isag，我们开发计算$ O（d_g）的\ pafalgo（\ paf）算法（p））$ makepan解决方案$ k = 2，3 $大部分使用$ o（| V | ^ 2）$运行时间。 \ paf提供最坏情况$ O（1）$  - 关于求解时间最优性的近似。我们注意到问题的最坏情况运行时间是$ \ Omega（| V | ^ 2）$。

##### URL
[http://arxiv.org/abs/1801.10465](http://arxiv.org/abs/1801.10465)

##### PDF
[http://arxiv.org/pdf/1801.10465](http://arxiv.org/pdf/1801.10465)

