---
layout: post
title: "Adversarial Examples Detection in Deep Networks with Convolutional Filter Statistics"
date: 2017-10-26 18:42:57
categories: arXiv_CV
tags: arXiv_CV Adversarial CNN Classification Deep_Learning Detection Recognition
author: Xin Li, Fuxin Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning has greatly improved visual recognition in recent years. However, recent research has shown that there exist many adversarial examples that can negatively impact the performance of such an architecture. This paper focuses on detecting those adversarial examples by analyzing whether they come from the same distribution as the normal examples. Instead of directly training a deep neural network to detect adversarials, a much simpler approach was proposed based on statistics on outputs from convolutional layers. A cascade classifier was designed to efficiently detect adversarials. Furthermore, trained from one particular adversarial generating mechanism, the resulting classifier can successfully detect adversarials from a completely different mechanism as well. The resulting classifier is non-subdifferentiable, hence creates a difficulty for adversaries to attack by using the gradient of the classifier. After detecting adversarial examples, we show that many of them can be recovered by simply performing a small average filter on the image. Those findings should lead to more insights about the classification mechanisms in deep convolutional neural networks.

##### Abstract (translated by Google)
深度学习近年来大大提高了视觉识别能力。然而，最近的研究表明，存在许多可能对这种架构的性能产生负面影响的对抗性例子。本文着重于通过分析它们是否来自与正常范例相同的分布来检测这些对抗性例子。不是直接训练深度神经网络来检测对抗，而是根据卷积层输出的统计数据提出了一种更为简单的方法。级联分类器旨在有效检测对手。而且，通过一个特定的对抗生成机制进行训练，所得到的分类器也可以成功地从完全不同的机制中检测敌对对象。由此产生的分类器是不可微分的，因此通过使用分类器的梯度为攻击者造成困难。在检测到敌对的例子之后，我们展示了它们中的许多可以通过简单地对图像执行小的平均过滤器来恢复。这些发现将导致深度卷积神经网络分类机制的更多见解。

##### URL
[https://arxiv.org/abs/1612.07767](https://arxiv.org/abs/1612.07767)

##### PDF
[https://arxiv.org/pdf/1612.07767](https://arxiv.org/pdf/1612.07767)

