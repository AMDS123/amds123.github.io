---
layout: post
title: "Effectiveness of Scaled Exponentially-Regularized Linear Units"
date: 2018-07-26 13:33:49
categories: arXiv_AI
tags: arXiv_AI
author: G. Zhang, H. Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, self-normalizing neural networks (SNNs) have been proposed with the intention to avoid batch or weight normalization. The key step in SNNs is to properly scale the exponential linear unit (referred to as SELU) to inherently incorporate normalization based on central limit theory. SELU is a monotonically increasing function, where it has an approximately constant negative output for large negative input. In this work, we propose a new activation function to break the monotonicity property of SELU while still preserving the self-normalizing property. Differently from SELU, the new function introduces a bump-shaped function in the region of negative input by regularizing a linear function with a scaled exponential function, which is referred to as a scaled exponentially-regularized linear unit (SERLU). The bump-shaped function has approximately zero response to large negative input while being able to push the output of SERLU towards zero mean statistically. To effectively combat over-fitting, we develop a so-called shift-dropout for SERLU, which includes standard dropout as a special case. Experimental results on MNIST, CIFAR10 and CIFAR100 show that SERLU-based neural networks provide consistently promising results in comparison to other 5 activation functions including ELU, SELU, Swish, Leakly ReLU and ReLU.

##### Abstract (translated by Google)
最近，已经提出了自我归一化神经网络（SNN），其目的是避免批量或权重归一化。 SNN中的关键步骤是适当地缩放指数线性单位（称为SELU），以固有地结合基于中心极限理论的归一化。 SELU是单调递增函数，对于大负输入，它具有近似恒定的负输出。在这项工作中，我们提出了一个新的激活函数来打破SELU的单调性，同时仍然保持自我归一化属性。与SELU不同，新函数通过使用缩放指数函数对线性函数进行正则化来在负输入区域中引入凹凸形函数，其被称为缩放指数正则化线性单位（SERLU）。凸起形函数对大负输入具有近似零响应，同时能够将SERLU的输出推向零均值统计。为了有效地防止过度拟合，我们为SERLU开发了一种所谓的移位丢失，其中包括作为特殊情况的标准丢失。在MNIST，CIFAR10和CIFAR100上的实验结果表明，与其他5种激活功能相比，基于SERLU的神经网络提供了始终有希望的结果，包括ELU，SELU，Swish，Leakly ReLU和ReLU。

##### URL
[http://arxiv.org/abs/1807.10117](http://arxiv.org/abs/1807.10117)

##### PDF
[http://arxiv.org/pdf/1807.10117](http://arxiv.org/pdf/1807.10117)

