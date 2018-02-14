---
layout: post
title: "signSGD: compressed optimisation for non-convex problems"
date: 2018-02-13 02:14:35
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Jeremy Bernstein, Yu-Xiang Wang, Kamyar Azizzadenesheli, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Training large neural networks requires distributing learning across multiple workers, where the cost of communicating gradients can be a significant bottleneck. signSGD alleviates this problem by transmitting just the sign of each minibatch stochastic gradient. We prove that it can get the best of both worlds: compressed gradients and SGD-level convergence rate. signSGD can exploit mismatches between L1 and L2 geometry: when noise and curvature are much sparser than the gradients, signSGD is expected to converge at the same rate or faster than full-precision SGD. Measurements of the L1 versus L2 geometry of real networks support our theoretical claims, and we find that the momentum counterpart of signSGD is able to match the accuracy and convergence speed of Adam on deep Imagenet models. We extend our theory to the distributed setting, where the parameter server uses majority vote to aggregate gradient signs from each worker enabling 1-bit compression of worker-server communication in both directions. Using a theorem by Gauss, we prove that the non-convex convergence rate of majority vote matches that of distributed SGD. Thus, there is great promise for sign-based optimisation schemes to achieve both communication efficiency and high accuracy.

##### Abstract (translated by Google)
培训大型神经网络需要在多个工作人员之间分配学习，沟通梯度的成本可能是一个重大瓶颈。 signSGD通过传输每个小批次随机梯度的符号来缓解此问题。我们证明它可以得到两全其美的效果：压缩梯度和SGD级收敛速度。 signSGD可以利用L1和L2几何体之间的不匹配：当噪声和曲率比梯度稀疏的多时，signSGD预计会以相同的速率收敛或比全精度SGD更快。对真实网络的L1和L2几何结构的测量支持我们的理论主张，并且我们发现signSGD的动量对应物能够匹配Adam在深度Imagenet模型上的精度和收敛速度。我们将理论扩展到分布式设置，其中参数服务器使用多数投票来聚合来自每个工作者的梯度符号，从而实现双向工作者 - 服务器通信的1位压缩。使用高斯定理，我们证明了多数投票的非凸收敛率与分布式SGD的非凸收敛率相匹配。因此，基于符号的优化方案在实现通信效率和高精度方面具有很大的潜力。

##### URL
[http://arxiv.org/abs/1802.04434](http://arxiv.org/abs/1802.04434)

##### PDF
[http://arxiv.org/pdf/1802.04434](http://arxiv.org/pdf/1802.04434)

