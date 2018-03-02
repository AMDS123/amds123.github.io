---
layout: post
title: "Learning Sampling Distributions for Robot Motion Planning"
date: 2018-03-01 02:41:09
categories: arXiv_RO
tags: arXiv_RO
author: Brian Ichter, James Harrison, Marco Pavone
mathjax: true
---

* content
{:toc}

##### Abstract
A defining feature of sampling-based motion planning is the reliance on an implicit representation of the state space, which is enabled by a set of probing samples. Traditionally, these samples are drawn either probabilistically or deterministically to uniformly cover the state space. Yet, the motion of many robotic systems is often restricted to "small" regions of the state space, due to e.g. differential constraints or collision-avoidance constraints. To accelerate the planning process, it is thus desirable to devise non-uniform sampling strategies that favor sampling in those regions where an optimal solution might lie. This paper proposes a methodology for non-uniform sampling, whereby a sampling distribution is learnt from demonstrations, and then used to bias sampling. The sampling distribution is computed through a conditional variational autoencoder, allowing sample generation from the latent space conditioned on the specific planning problem. This methodology is general, can be used in combination with any sampling-based planner, and can effectively exploit the underlying structure of a planning problem while maintaining the theoretical guarantees of sampling-based approaches. Specifically, on several planning problems, the proposed methodology is shown to effectively learn representations for the relevant regions of the state space, resulting in an order of magnitude improvement in terms of success rate and convergence to the optimal cost.

##### Abstract (translated by Google)
基于抽样的运动规划的一个定义特征是依赖于状态空间的隐式表示，这是通过一组探测样本实现的。传统上，这些样本是以概率或确定性方式绘制，以均匀覆盖状态空间。然而，许多机器人系统的运动通常限于状态空间的“小”区域，这是由于例如，差分约束或碰撞避免约束。为了加速规划过程，因此需要制定非均匀抽样策略，以便在最佳解决方案可能存在的地区有利于抽样。本文提出了一种非均匀抽样的方法，即从示例中学习抽样分布，然后用于偏置抽样。采样分布是通过条件变分自动编码器计算的，允许从特定计划问题的潜在空间生成样本。这种方法是一般性的，可以与任何基于抽样的规划人员结合使用，并且可以有效利用计划问题的基础结构，同时保持基于抽样的方法的理论保证。具体而言，在几个规划问题上，所提出的方法被证明可以有效地学习状态空间相关区域的表示，从而在成功率和收敛到最优成本方面提高了一个数量级。

##### URL
[http://arxiv.org/abs/1709.05448](http://arxiv.org/abs/1709.05448)

##### PDF
[http://arxiv.org/pdf/1709.05448](http://arxiv.org/pdf/1709.05448)

