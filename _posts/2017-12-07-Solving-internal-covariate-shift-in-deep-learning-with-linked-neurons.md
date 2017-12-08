---
layout: post
title: "Solving internal covariate shift in deep learning with linked neurons"
date: 2017-12-07 13:26:26
categories: arXiv_CV
tags: arXiv_CV Deep_Learning
author: Carles Roger Riera Molina, Oriol Pujol Vila
mathjax: true
---

* content
{:toc}

##### Abstract
This work proposes a novel solution to the problem of internal covariate shift and dying neurons using the concept of linked neurons. We define the neuron linkage in terms of two constraints: first, all neuron activations in the linkage must have the same operating point. That is to say, all of them share input weights. Secondly, a set of neurons is linked if and only if there is at least one member of the linkage that has a non-zero gradient in regard to the input of the activation function. This means that for any input in the activation function, there is at least one member of the linkage that operates in a non-flat and non-zero area. This simple change has profound implications in the network learning dynamics. In this article we explore the consequences of this proposal and show that by using this kind of units, internal covariate shift is implicitly solved. As a result of this, the use of linked neurons allows to train arbitrarily large networks without any architectural or algorithmic trick, effectively removing the need of using re-normalization schemes such as Batch Normalization, which leads to halving the required training time. It also solves the problem of the need for standarized input data. Results show that the units using the linkage not only do effectively solve the aforementioned problems, but are also a competitive alternative with respect to state-of-the-art with very promising results.

##### Abstract (translated by Google)
这项工作提出了一个新的解决方案的内部协变量和死亡神经元使用链接的神经元的概念。我们根据两个约束来定义神经元连接：首先，连接中的所有神经元激活必须具有相同的操作点。也就是说，他们都分享投入权重。其次，当且仅当关于激活函数的输入具有非零梯度的联系的至少一个成员时，联结一组神经元。这意味着对于激活功能中的任何输入，至少有一个连接的成员在非平坦和非零区域中操作。这个简单的变化对网络学习动态有着深远的影响。在这篇文章中，我们探讨了这个提议的后果，并且表明通过使用这种单位，内在协变化是隐含地解决的。因此，链接神经元的使用允许训练任意大的网络而没有任何架构或算法技巧，有效地消除了使用诸如批量标准化（Batch Normalization）之类的重新标准化方案的需要，这导致所需训练时间减半。它也解决了对标准输入数据的需求的问题。结果表明，采用联动机制的单位不仅有效地解决了上述问题，而且对于最新的研究成果也是一个有竞争力的替代方案。

##### URL
[http://arxiv.org/abs/1712.02609](http://arxiv.org/abs/1712.02609)

##### PDF
[http://arxiv.org/pdf/1712.02609](http://arxiv.org/pdf/1712.02609)

