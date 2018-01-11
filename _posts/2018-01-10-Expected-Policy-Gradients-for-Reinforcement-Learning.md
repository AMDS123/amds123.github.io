---
layout: post
title: "Expected Policy Gradients for Reinforcement Learning"
date: 2018-01-10 11:59:59
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Kamil Ciosek, Shimon Whiteson
mathjax: true
---

* content
{:toc}

##### Abstract
We propose expected policy gradients (EPG), which unify stochastic policy gradients (SPG) and deterministic policy gradients (DPG) for reinforcement learning. Inspired by expected sarsa, EPG integrates (or sums) across actions when estimating the gradient, instead of relying only on the action in the sampled trajectory. For continuous action spaces, we first derive a practical result for Gaussian policies and quadric critics and then extend it to an analytical method for the universal case, covering a broad class of actors and critics, including Gaussian, exponential families, and reparameterised policies with bounded support. For Gaussian policies, we show that it is optimal to explore using covariance proportional to the matrix exponential of the scaled Hessian of the critic with respect to the actions. EPG also provides a general framework for reasoning about policy gradient methods, which we use to establish a new general policy gradient theorem, of which the stochastic and deterministic policy gradient theorems are special cases. Furthermore, we prove that EPG reduces the variance of the gradient estimates without requiring deterministic policies and with little computational overhead. Finally, we show that EPG outperforms existing approaches on six challenging domains involving the simulated control of physical systems.

##### Abstract (translated by Google)
我们提出预期策略梯度（EPG），它将强化学习的随机策略梯度（SPG）和确定性策略梯度（DPG）统一起来。受到预期的萨尔萨的启发，EPG在估计梯度时整合（或总和）行为，而不仅仅依赖于采样轨迹中的行为。对于连续行动空间，我们首先得到一个高斯政策和二次评论的实际结果，然后将其扩展到一个普适案例的分析方法，涵盖了广泛的演员和评论家，包括高斯，指数族和重新参数化的有界政策支持。对于高斯政策，我们表明，使用协方差与批评者关于行为的缩放Hessian矩阵的指数成比例是最优的。 EPG还为政策梯度方法的推理提供了一个通用的框架，我们用它来建立一个新的广义政策梯度定理，其中随机和确定性政策梯度定理是特例。此外，我们证明EPG降低了梯度估计的方差，而不需要确定性的策略，而且计算开销很小。最后，我们展示EPG在涉及物理系统的模拟控制的六个具有挑战性的领域上胜过现有的方法。

##### URL
[https://arxiv.org/abs/1801.03326](https://arxiv.org/abs/1801.03326)

##### PDF
[https://arxiv.org/pdf/1801.03326](https://arxiv.org/pdf/1801.03326)

