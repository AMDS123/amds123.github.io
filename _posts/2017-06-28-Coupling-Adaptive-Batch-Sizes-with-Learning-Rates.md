---
layout: post
title: "Coupling Adaptive Batch Sizes with Learning Rates"
date: 2017-06-28 12:07:02
categories: arXiv_CV
tags: arXiv_CV Image_Classification Optimization Classification Gradient_Descent Relation
author: Lukas Balles, Javier Romero, Philipp Hennig
mathjax: true
---

* content
{:toc}

##### Abstract
Mini-batch stochastic gradient descent and variants thereof have become standard for large-scale empirical risk minimization like the training of neural networks. These methods are usually used with a constant batch size chosen by simple empirical inspection. The batch size significantly influences the behavior of the stochastic optimization algorithm, though, since it determines the variance of the gradient estimates. This variance also changes over the optimization process; when using a constant batch size, stability and convergence is thus often enforced by means of a (manually tuned) decreasing learning rate schedule. We propose a practical method for dynamic batch size adaptation. It estimates the variance of the stochastic gradients and adapts the batch size to decrease the variance proportionally to the value of the objective function, removing the need for the aforementioned learning rate decrease. In contrast to recent related work, our algorithm couples the batch size to the learning rate, directly reflecting the known relationship between the two. On popular image classification benchmarks, our batch size adaptation yields faster optimization convergence, while simultaneously simplifying learning rate tuning. A TensorFlow implementation is available.

##### Abstract (translated by Google)
小批量随机梯度下降及其变体已经成为像神经网络训练那样的大规模经验风险最小化的标准。这些方法通常与通过简单的经验检验选择的恒定批次大小一起使用。虽然批量大小显着影响随机优化算法的行为，因为它决定了梯度估计的方差。这种差异也在优化过程中改变;当使用恒定的批量大小时，稳定性和收敛性因此经常通过（手动调整）降低的学习速率时间表来实施。我们提出了一种动态批量适应的实用方法。它估计随机梯度的方差，并适应批量大小，以便与目标函数的值成比例地降低方差，从而消除上述学习速率下降的需要。与最近的相关工作相比，我们的算法将批量大小与学习速率相结合，直接反映了两者之间的已知关系。在流行的图像分类基准测试中，我们的批量调整产生了更快的优化收敛，同时简化了学习速率调整。 TensorFlow实现可用。

##### URL
[https://arxiv.org/abs/1612.05086](https://arxiv.org/abs/1612.05086)

##### PDF
[https://arxiv.org/pdf/1612.05086](https://arxiv.org/pdf/1612.05086)

