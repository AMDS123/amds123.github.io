---
layout: post
title: "signSGD: Compressed Optimisation for Non-Convex Problems"
date: 2018-06-23 18:01:27
categories: arXiv_AI
tags: arXiv_AI
author: Jeremy Bernstein, Yu-Xiang Wang, Kamyar Azizzadenesheli, Anima Anandkumar
mathjax: true
---

* content
{:toc}

##### Abstract
Training large neural networks requires distributing learning across multiple workers, where the cost of communicating gradients can be a significant bottleneck. signSGD alleviates this problem by transmitting just the sign of each minibatch stochastic gradient. We prove that it can get the best of both worlds: compressed gradients and SGD-level convergence rate. The relative $\ell_1/\ell_2$ geometry of gradients, noise and curvature informs whether signSGD or SGD is theoretically better suited to a particular problem. On the practical side we find that the momentum counterpart of signSGD is able to match the accuracy and convergence speed of Adam on deep Imagenet models. We extend our theory to the distributed setting, where the parameter server uses majority vote to aggregate gradient signs from each worker enabling 1-bit compression of worker-server communication in both directions. Using a theorem by Gauss we prove that majority vote can achieve the same reduction in variance as full precision distributed SGD. Thus, there is great promise for sign-based optimisation schemes to achieve fast communication and fast convergence. Code to reproduce experiments is to be found at https://github.com/jxbz/signSGD.

##### Abstract (translated by Google)
培训大型神经网络需要在多个工作人员之间分配学习，沟通梯度的成本可能是一个重大瓶颈。 signSGD通过传输每个小批次随机梯度的符号来缓解此问题。我们证明它可以得到两全其美的效果：压缩梯度和SGD级收敛速度。渐变，噪声和曲率的相对$ \ ell_1 / \ ell_2 $几何信息通知signSGD或SGD在理论上是否更适合特定问题。在实践方面，我们发现signSGD的动量对应能够匹配Adam在深度Imagenet模型上的准确性和收敛速度。我们将理论扩展到分布式设置，其中参数服务器使用多数投票来聚合来自每个工作者的梯度符号，从而实现双向工作者 - 服务器通信的1位压缩。使用高斯定理，我们证明大多数投票可以实现与全精度分布式SGD相同的方差减少。因此，基于符号的优化方案实现快速通信和快速收敛具有很大的前景。重现实验的代码可以在https://github.com/jxbz/signSGD找到。

##### URL
[http://arxiv.org/abs/1802.04434](http://arxiv.org/abs/1802.04434)

##### PDF
[http://arxiv.org/pdf/1802.04434](http://arxiv.org/pdf/1802.04434)

