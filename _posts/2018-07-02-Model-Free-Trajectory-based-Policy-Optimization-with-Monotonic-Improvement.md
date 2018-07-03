---
layout: post
title: "Model-Free Trajectory-based Policy Optimization with Monotonic Improvement"
date: 2018-07-02 12:40:05
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Riad Akrour, Abbas Abdolmaleki, Hany Abdulsamad, Jan Peters, Gerhard Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
Many of the recent trajectory optimization algorithms alternate between linear approximation of the system dynamics around the mean trajectory and conservative policy update. One way of constraining the policy change is by bounding the Kullback-Leibler (KL) divergence between successive policies. These approaches already demonstrated great experimental success in challenging problems such as end-to-end control of physical systems. However, the linear approximation of the system dynamics can introduce a bias in the policy update and prevent convergence to the optimal policy. In this article, we propose a new model-free trajectory-based policy optimization algorithm with guaranteed monotonic improvement. The algorithm backpropagates a local, quadratic and time-dependent \qfunc~learned from trajectory data instead of a model of the system dynamics. Our policy update ensures exact KL-constraint satisfaction without simplifying assumptions on the system dynamics. We experimentally demonstrate on highly non-linear control tasks the improvement in performance of our algorithm in comparison to approaches linearizing the system dynamics. In order to show the monotonic improvement of our algorithm, we additionally conduct a theoretical analysis of our policy update scheme to derive a lower bound of the change in policy return between successive iterations.

##### Abstract (translated by Google)
许多最近的轨迹优化算法在围绕平均轨迹的系统动态的线性近似和保守的策略更新之间交替。限制政策变化的一种方法是通过限制连续政策之间的Kullback-Leibler（KL）差异。这些方法已经在挑战诸如物理系统的端到端控制等问题方面取得了巨大的实验成功。但是，系统动态的线性近似可能会在策略更新中引入偏差并阻止收敛到最优策略。在本文中，我们提出了一种新的基于轨迹的基于轨迹的策略优化算法，该算法具有保证的单调改进。该算法反向传播从轨迹数据而不是系统动力学模型中学习的局部，二次和时间相关的\ qfunc_。我们的政策更新可确保精确的KL约束满足，而无需简化系统动态的假设。我们通过实验证明了高度非线性控制任务，与线性化系统动力学的方法相比，我们的算法性能得到了提高。为了显示我们的算法的单调改进，我们另外对我们的策略更新方案进行理论分析，以得出连续迭代之间的策略回报变化的下限。

##### URL
[http://arxiv.org/abs/1606.09197](http://arxiv.org/abs/1606.09197)

##### PDF
[http://arxiv.org/pdf/1606.09197](http://arxiv.org/pdf/1606.09197)

