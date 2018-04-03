---
layout: post
title: "Aggregated Momentum: Stability Through Passive Damping"
date: 2018-04-01 17:53:03
categories: arXiv_AI
tags: arXiv_AI Optimization Gradient_Descent
author: James Lucas, Richard Zemel, Roger Grosse
mathjax: true
---

* content
{:toc}

##### Abstract
Momentum is a simple and widely used trick which allows gradient-based optimizers to pick up speed in low curvature directions. Its performance depends crucially on a damping coefficient $\beta$. Large $\beta$ values can potentially deliver much larger speedups, but are prone to oscillations and instability; hence one typically resorts to small values such as 0.5 or 0.9. We propose Aggregated Momentum (AggMo), a variant of momentum which combines multiple velocity vectors with different $\beta$ parameters. AggMo is trivial to implement, but significantly dampens oscillations, enabling it to remain stable even for aggressive $\beta$ values such as 0.999. We reinterpret Nesterov's accelerated gradient descent as a special case of AggMo and provide theoretical convergence bounds for online convex optimization. Empirically, we find that AggMo is a suitable drop-in replacement for other momentum methods, and frequently delivers faster convergence.

##### Abstract (translated by Google)
动量是一个简单且广泛使用的技巧，它允许基于梯度的优化器在低曲率方向上提高速度。其性能主要取决于阻尼系数$ \ beta $。大$ \ beta $值可能会提供更大的加速，但容易产生振荡和不稳定;因此通常采用0.5或0.9等小值。我们提出Aggregated Momentum（AggMo），这是一个将多个速度向量与不同$ \ beta $参数组合在一起的动量变量。 AggMo实施起来微不足道，但可大大减少振荡，使其即使在激进的$ \ beta $值（例如0.999）下也能保持稳定。我们将Nesterov的加速梯度下降重新解释为AggMo的一个特例，并为在线凸优化提供了理论收敛范围。从经验上讲，我们发现AggMo是其他动量方法的一个适合的替代品，并且经常会提供更快的收敛性。

##### URL
[http://arxiv.org/abs/1804.00325](http://arxiv.org/abs/1804.00325)

##### PDF
[http://arxiv.org/pdf/1804.00325](http://arxiv.org/pdf/1804.00325)

