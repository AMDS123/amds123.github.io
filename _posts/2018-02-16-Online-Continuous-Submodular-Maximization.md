---
layout: post
title: "Online Continuous Submodular Maximization"
date: 2018-02-16 17:56:48
categories: arXiv_AI
tags: arXiv_AI Optimization
author: Lin Chen, Hamed Hassani, Amin Karbasi
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we consider an online optimization process, where the objective functions are not convex (nor concave) but instead belong to a broad class of continuous submodular functions. We first propose a variant of the Frank-Wolfe algorithm that has access to the full gradient of the objective functions. We show that it achieves a regret bound of $O(\sqrt{T})$ (where $T$ is the horizon of the online optimization problem) against a $(1-1/e)$-approximation to the best feasible solution in hindsight. However, in many scenarios, only an unbiased estimate of the gradients are available. For such settings, we then propose an online stochastic gradient ascent algorithm that also achieves a regret bound of $O(\sqrt{T})$ regret, albeit against a weaker $1/2$-approximation to the best feasible solution in hindsight. We also generalize our results to $\gamma$-weakly submodular functions and prove the same sublinear regret bounds. Finally, we demonstrate the efficiency of our algorithms on a few problem instances, including non-convex/non-concave quadratic programs, multilinear extensions of submodular set functions, and D-optimal design.

##### Abstract (translated by Google)
在本文中，我们考虑一个在线优化过程，其中目标函数不是凸的（也不是凹形的），而是属于广泛的连续子模函数类。我们首先提出一个Frank-Wolfe算法的变体，它可以访问目标函数的完整梯度。我们表明，它达到$ O（\ sqrt {T}）$（其中$ T $是在线优化问题的范围）与$（1-1 / e）$  - 的最佳可行性的近似值事后解决方案。但是，在很多情况下，只有斜率的无偏估计是可用的。对于这样的设置，我们随后提出了一种在线随机梯度上升算法，该算法也实现了$ O（\ sqrt {T}）$遗憾的遗憾限制，尽管在后见之下对最佳可行解决方案的较弱$ 1/2 $逼近。我们还将我们的结果推广到$ \ gamma $  - 弱子模块函数并证明相同的次线性遗憾边界。最后，我们证明了我们的算法在几个问题实例上的效率，包括非凸/非凹二次规划，子模块集函数的多线性扩展和D优化设计。

##### URL
[https://arxiv.org/abs/1802.06052](https://arxiv.org/abs/1802.06052)

##### PDF
[https://arxiv.org/pdf/1802.06052](https://arxiv.org/pdf/1802.06052)

