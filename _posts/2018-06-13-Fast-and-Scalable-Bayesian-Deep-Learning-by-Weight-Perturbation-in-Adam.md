---
layout: post
title: "Fast and Scalable Bayesian Deep Learning by Weight-Perturbation in Adam"
date: 2018-06-13 05:45:22
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Optimization Inference Deep_Learning
author: Mohammad Emtiyaz Khan, Didrik Nielsen, Voot Tangkaratt, Wu Lin, Yarin Gal, Akash Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Uncertainty computation in deep learning is essential to design robust and reliable systems. Variational inference (VI) is a promising approach for such computation, but requires more effort to implement and execute compared to maximum-likelihood methods. In this paper, we propose new natural-gradient algorithms to reduce such efforts for Gaussian mean-field VI. Our algorithms can be implemented within the Adam optimizer by perturbing the network weights during gradient evaluations, and uncertainty estimates can be cheaply obtained by using the vector that adapts the learning rate. This requires lower memory, computation, and implementation effort than existing VI methods, while obtaining uncertainty estimates of comparable quality. Our empirical results confirm this and further suggest that the weight-perturbation in our algorithm could be useful for exploration in reinforcement learning and stochastic optimization.

##### Abstract (translated by Google)
深度学习中的不确定性计算对于设计稳健可靠的系统至关重要。变分推理（VI）是这种计算的一种有前途的方法，但与最大似然方法相比，需要更多的努力来实现和执行。在本文中，我们提出了新的自然梯度算法，以减少高斯平均场VI的工作量。我们的算法可以在Adam优化器中通过扰动梯度评估期间的网络权重来实现，并且通过使用适应学习速率的向量可以便宜地获得不确定性估计。与现有的VI方法相比，这需要较低的存储器，计算和实施工作量，同时获得可比质量的不确定性估计。我们的实证结果证实了这一点，并进一步表明，我们的算法中的权重扰动可以用于强化学习和随机优化的探索。

##### URL
[http://arxiv.org/abs/1806.04854](http://arxiv.org/abs/1806.04854)

##### PDF
[http://arxiv.org/pdf/1806.04854](http://arxiv.org/pdf/1806.04854)

