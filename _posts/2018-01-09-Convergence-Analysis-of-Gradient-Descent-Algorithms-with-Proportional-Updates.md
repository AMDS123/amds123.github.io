---
layout: post
title: "Convergence Analysis of Gradient Descent Algorithms with Proportional Updates"
date: 2018-01-09 20:51:28
categories: arXiv_AI
tags: arXiv_AI Optimization Deep_Learning Gradient_Descent
author: Igor Gitman, Deepak Dilipkumar, Ben Parr
mathjax: true
---

* content
{:toc}

##### Abstract
The rise of deep learning in recent years has brought with it increasingly clever optimization methods to deal with complex, non-linear loss functions. These methods are often designed with convex optimization in mind, but have been shown to work well in practice even for the highly non-convex optimization associated with neural networks. However, one significant drawback of these methods when they are applied to deep learning is that the magnitude of the update step is sometimes disproportionate to the magnitude of the weights (much smaller or larger), leading to training instabilities such as vanishing and exploding gradients. An idea to combat this issue is gradient descent with proportional updates. Gradient descent with proportional updates was introduced in 2017. It was independently developed by You et al (Layer-wise Adaptive Rate Scaling (LARS) algorithm) and by Abu-El-Haija (PercentDelta algorithm). The basic idea of both of these algorithms is to make each step of the gradient descent proportional to the current weight norm and independent of the gradient magnitude. It is common in the context of new optimization methods to prove convergence or derive regret bounds under the assumption of Lipschitz continuity and convexity. However, even though LARS and PercentDelta were shown to work well in practice, there is no theoretical analysis of the convergence properties of these algorithms. Thus it is not clear if the idea of gradient descent with proportional updates is used in the optimal way, or if it could be improved by using a different norm or specific learning rate schedule, for example. Moreover, it is not clear if these algorithms can be extended to other problems, besides neural networks. We attempt to answer these questions by establishing the theoretical analysis of gradient descent with proportional updates, and verifying this analysis with empirical examples.

##### Abstract (translated by Google)
近年来深度学习的兴起，为处理复杂的非线性损失函数带来了越来越聪明的优化方法。这些方法通常设计时考虑了凸优化问题，但是在实际应用中，甚至在与神经网络相关的高度非凸优化方面也表现良好。然而，这些方法应用于深度学习的一个显着缺点是更新步骤的大小有时与权重的大小（小得多或者大得多）不成比例，从而导致诸如消失和爆炸梯度的训练不稳定性。解决这个问题的一个想法是与比例更新的梯度下降。 2017年推出了按比例更新的梯度下降法，由You等人（Layer-wise Adaptive Rate Scaling（LARS）算法）和Abu-El-Haija（PercentDelta算法）独立开发。这两种算法的基本思想是使梯度下降的每一步与当前的权重范数成正比，而与梯度幅度无关。在Lipschitz连续性和凸性假设下，证明收敛性或推导遗憾边界的新优化方法是很常见的。然而，即使LARS和PercentDelta在实践中表现得很好，但对这些算法的收敛性没有理论分析。因此，不清楚是否以最佳方式使用比例更新的梯度下降的概念，或者是否可以通过使用不同的标准或特定的学习速率时间表来改进。此外，除了神经网络之外，这些算法是否可以扩展到其他问题尚不清楚。我们试图通过建立比例更新的梯度下降的理论分析来回答这些问题，并用经验实例来验证这个分析。

##### URL
[http://arxiv.org/abs/1801.03137](http://arxiv.org/abs/1801.03137)

##### PDF
[http://arxiv.org/pdf/1801.03137](http://arxiv.org/pdf/1801.03137)

