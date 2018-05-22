---
layout: post
title: "Meta-learning with differentiable closed-form solvers"
date: 2018-05-21 15:44:51
categories: arXiv_CV
tags: arXiv_CV Gradient_Descent
author: Luca Bertinetto, João F. Henriques, Philip H.S. Torr, Andrea Vedaldi
mathjax: true
---

* content
{:toc}

##### Abstract
Adapting deep networks to new concepts from few examples is extremely challenging, due to the high computational and data requirements of standard fine-tuning procedures. Most works on meta-learning and few-shot learning have thus focused on simple learning techniques for adaptation, such as nearest neighbors or gradient descent. Nonetheless, the machine learning literature contains a wealth of methods that learn non-deep models very efficiently. In this work we propose to use these fast convergent methods as the main adaptation mechanism for few-shot learning. The main idea is to teach a deep network to use standard machine learning tools, such as logistic regression, as part of its own internal model, enabling it to quickly adapt to novel tasks. This requires back-propagating errors through the solver steps. While normally the matrix operations involved would be costly, the small number of examples works to our advantage, by making use of the Woodbury identity. We propose both iterative and closed-form solvers, based on logistic regression and ridge regression components. Our methods achieve excellent performance on three few-shot learning benchmarks, showing competitive performance on Omniglot and surpassing all state-of-the-art alternatives on miniImageNet and CIFAR-100.

##### Abstract (translated by Google)
由于标准微调程序对计算和数据的高度要求，因此将深度网络从少数示例中适应新概念是非常具有挑战性的。因此，大多数关于元学习和少数学习的作品都侧重于简单的适应性学习技术，如最近邻居或梯度下降。尽管如此，机器学习文献包含了很多非常有效地学习非深度模型的方法。在这项工作中，我们建议使用这些快速收敛方法作为少量学习的主要适应机制。主要想法是教一个深层网络使用标准机器学习工具，如逻辑回归作为其内部模型的一部分，使其能够快速适应新的任务。这需要通过解算器步骤反向传播错误。虽然通常所涉及的矩阵运算成本很高，但通过使用伍德伯里身份，少量例子对我们有利。基于逻辑回归和岭回归组件，我们提出了迭代和封闭形式的求解器。我们的方法在三项少量学习基准测试中表现出色，在Omniglot上展现出极具竞争力的表现，并超越miniImageNet和CIFAR-100上所有最先进的替代品。

##### URL
[https://arxiv.org/abs/1805.08136](https://arxiv.org/abs/1805.08136)

##### PDF
[https://arxiv.org/pdf/1805.08136](https://arxiv.org/pdf/1805.08136)

