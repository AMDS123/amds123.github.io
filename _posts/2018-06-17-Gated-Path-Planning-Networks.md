---
layout: post
title: "Gated Path Planning Networks"
date: 2018-06-17 16:32:52
categories: arXiv_AI
tags: arXiv_AI CNN Optimization
author: Lisa Lee, Emilio Parisotto, Devendra Singh Chaplot, Eric Xing, Ruslan Salakhutdinov
mathjax: true
---

* content
{:toc}

##### Abstract
Value Iteration Networks (VINs) are effective differentiable path planning modules that can be used by agents to perform navigation while still maintaining end-to-end differentiability of the entire architecture. Despite their effectiveness, they suffer from several disadvantages including training instability, random seed sensitivity, and other optimization problems. In this work, we reframe VINs as recurrent-convolutional networks which demonstrates that VINs couple recurrent convolutions with an unconventional max-pooling activation. From this perspective, we argue that standard gated recurrent update equations could potentially alleviate the optimization issues plaguing VIN. The resulting architecture, which we call the Gated Path Planning Network, is shown to empirically outperform VIN on a variety of metrics such as learning speed, hyperparameter sensitivity, iteration count, and even generalization. Furthermore, we show that this performance gap is consistent across different maze transition types, maze sizes and even show success on a challenging 3D environment, where the planner is only provided with first-person RGB images.

##### Abstract (translated by Google)
价值迭代网络（VIN）是有效的可区分路径规划模块，代理可以使用这些模块执行导航，同时仍保持整个架构的端到端可区分性。尽管它们有效，但它们还是存在一些缺点，包括训练不稳定性，种子敏感性随机性和其他优化问题。在这项工作中，我们将VINs重新定义为递归卷积网络，它证明VINs与非常规的最大池激活相结合来反复卷积。从这个角度来看，我们认为标准的门控循环更新方程可能会缓解困扰VIN的优化问题。由此产生的架构，我们称之为门控路径规划网络，在学习速度，超参数敏感度，迭代次数甚至泛化等各种指标上，都显示出经验性地优于VIN。此外，我们发现这种性能差距在不同的迷宫过渡类型，迷宫尺寸中是一致的，甚至在具有挑战性的3D环境中显示成功，其中规划者只提供第一人称RGB图像。

##### URL
[http://arxiv.org/abs/1806.06408](http://arxiv.org/abs/1806.06408)

##### PDF
[http://arxiv.org/pdf/1806.06408](http://arxiv.org/pdf/1806.06408)

