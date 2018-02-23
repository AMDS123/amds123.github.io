---
layout: post
title: "Projection-Free Online Optimization with Stochastic Gradient: From Convexity to Submodularity"
date: 2018-02-22 17:13:36
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization
author: Lin Chen, Christopher Harshaw, Hamed Hassani, Amin Karbasi
mathjax: true
---

* content
{:toc}

##### Abstract
Online optimization has been a successful framework for solving large-scale problems under computational constraints and partial information. Current methods for online convex optimization require either a projection or exact gradient computation at each step, both of which can be prohibitively expensive for large-scale applications. At the same time, there is a growing trend of non-convex optimization in machine learning community and a need for online methods. Continuous submodular functions, which exhibit a natural diminishing returns condition, have recently been proposed as a broad class of non-convex functions which may be efficiently optimized. Although online methods have been introduced, they suffer from similar problems. In this work, we propose Meta-Frank-Wolfe, the first online projectionfree algorithm that uses stochastic gradient estimates. The algorithm relies on a careful sampling of gradients in each round and achieves the optimal $O(\sqrt{T})$ adversarial regret bounds for convex and continuous submodular optimization. We also propose One-Shot Frank-Wolfe, a simpler algorithm which requires only a single stochastic gradient estimate in each round and achieves a $O(T^{2/3})$ stochastic regret bound for convex and continuous submodular optimization. We apply our methods to develop a novel "lifting" framework for the online discrete submodular maximization and also see that they outperform current state of the art techniques on an extensive set of experiments.

##### Abstract (translated by Google)
在计算约束和部分信息下，在线优化一直是解决大规模问题的成功框架。在线凸优化的当前方法需要在每个步骤进行投影或精确梯度计算，这两者对于大规模应用来说都是非常昂贵的。与此同时，机器学习社区中非凸优化的发展趋势和对在线方法的需求也在增长。最近已经提出了表现出自然递减收益条件的连续子​​模块函数作为可以被有效优化的广泛类别的非凸函数。虽然已经引入了在线方法，但也存在类似的问题。在这项工作中，我们提出Meta-Frank-Wolfe，这是第一个使用随机梯度估计的在线投影免费算法。该算法依赖于每轮中梯度的仔细采样，并实现凸和连续子模块优化的最优$ O（\ sqrt {T}）$对抗遗憾边界。我们还提出了一次性Frank-Wolfe算法，该算法在每一轮中只需要一个随机梯度估计，并且实现了一个$ O（T ^ {2/3}）$随机后悔边界，用于凸和连续子模块优化。我们应用我们的方法为在线离散子模块最大化开发了一种新颖的“提升”框架，并且还看到它们在广泛的一系列实验中超越了当前最先进的技术。

##### URL
[http://arxiv.org/abs/1802.08183](http://arxiv.org/abs/1802.08183)

##### PDF
[http://arxiv.org/pdf/1802.08183](http://arxiv.org/pdf/1802.08183)

