---
layout: post
title: "WNGrad: Learn the Learning Rate in Gradient Descent"
date: 2018-03-07 20:30:35
categories: arXiv_AI
tags: arXiv_AI Deep_Learning Gradient_Descent Relation
author: Xiaoxia Wu, Rachel Ward, L&#xe9;on Bottou
mathjax: true
---

* content
{:toc}

##### Abstract
Adjusting the learning rate schedule in stochastic gradient methods is an important unresolved problem which requires tuning in practice. If certain parameters of the loss function such as smoothness or strong convexity constants are known, theoretical learning rate schedules can be applied. However, in practice, such parameters are not known, and the loss function of interest is not convex in any case. The recently proposed batch normalization reparametrization is widely adopted in most neural network architectures today because, among other advantages, it is robust to the choice of Lipschitz constant of the gradient in loss function, allowing one to set a large learning rate without worry. Inspired by batch normalization, we propose a general nonlinear update rule for the learning rate in batch and stochastic gradient descent so that the learning rate can be initialized at a high value, and is subsequently decreased according to gradient observations along the way. The proposed method is shown to achieve robustness to the relationship between the learning rate and the Lipschitz constant, and near-optimal convergence rates in both the batch and stochastic settings ($O(1/T)$ for smooth loss in the batch setting, and $O(1/\sqrt{T})$ for convex loss in the stochastic setting). We also show through numerical evidence that such robustness of the proposed method extends to highly nonconvex and possibly non-smooth loss function in deep learning problems.Our analysis establishes some first theoretical understanding into the observed robustness for batch normalization and weight normalization.

##### Abstract (translated by Google)
在随机梯度法中调整学习速率时间表是一个重要的尚未解决的问题，需要在实践中进行调整。如果损失函数的某些参数如平滑度或强凸性常数已知，则可应用理论学习速率时间表。然而，在实践中，这些参数是未知的，并且感兴趣的损失函数在任何情况下都不是凸的。最近提出的批量归一化重新参数化在当今大多数神经网络体系结构中被广泛采用，因为除了其他优点之外，它对损失函数中梯度的Lipschitz常数的选择是鲁棒的，允许人们设置大的学习速率而不用担心。受到批量归一化的启发，我们提出了批量和随机梯度下降的学习率的一般非线性更新规则，以便学习率可以初始化为高值，随后根据沿途的梯度观测降低。所示出的方法实现了对学习速率和Lipschitz常数之间的关系的鲁棒性以及在批量设置和随机设置（批量设置中的平滑损失的$ O（1 / T）$）下的近似最优收敛速率，和$ O（1 / \ sqrt {T}）$在随机设置中的凸损失）。我们还通过数值证据表明，所提出的方法的这种鲁棒性在深度学习问题中扩展到高度非凸和可能非光滑损失函数。我们的分析建立了对批量归一化和权重归一化所观察到的鲁棒性的一些理论上的第一理解。

##### URL
[http://arxiv.org/abs/1803.02865](http://arxiv.org/abs/1803.02865)

##### PDF
[http://arxiv.org/pdf/1803.02865](http://arxiv.org/pdf/1803.02865)

