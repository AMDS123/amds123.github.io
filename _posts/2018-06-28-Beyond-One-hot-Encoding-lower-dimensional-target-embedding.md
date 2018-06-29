---
layout: post
title: "Beyond One-hot Encoding: lower dimensional target embedding"
date: 2018-06-28 07:34:14
categories: arXiv_AI
tags: arXiv_AI Embedding CNN Relation
author: Pau Rodr&#xed;guez, Miguel A. Bautista, Jordi Gonz&#xe0;lez, Sergio Escalera
mathjax: true
---

* content
{:toc}

##### Abstract
Target encoding plays a central role when learning Convolutional Neural Networks. In this realm, One-hot encoding is the most prevalent strategy due to its simplicity. However, this so widespread encoding schema assumes a flat label space, thus ignoring rich relationships existing among labels that can be exploited during training. In large-scale datasets, data does not span the full label space, but instead lies in a low-dimensional output manifold. Following this observation, we embed the targets into a low-dimensional space, drastically improving convergence speed while preserving accuracy. Our contribution is two fold: (i) We show that random projections of the label space are a valid tool to find such lower dimensional embeddings, boosting dramatically convergence rates at zero computational cost; and (ii) we propose a normalized eigenrepresentation of the class manifold that encodes the targets with minimal information loss, improving the accuracy of random projections encoding while enjoying the same convergence rates. Experiments on CIFAR-100, CUB200-2011, Imagenet, and MIT Places demonstrate that the proposed approach drastically improves convergence speed while reaching very competitive accuracy rates.

##### Abstract (translated by Google)
目标编码在学习卷积神经网络时起着核心作用。在这个领域，由于其简单性，单热编码是最流行的策略。然而，这种如此广泛的编码模式假设了一个平坦的标签空间，因此忽略了可以在培训期间被利用的标签之间存在的丰富关系。在大规模数据集中，数据不能跨越整个标签空间，而是位于低维输出流形中。在观察之后，我们将目标嵌入低维空间，在保持准确性的同时大大提高了收敛速度。我们的贡献有两个：（i）我们表明标签空间的随机投影是找到这种较低维嵌入的有效工具，以零计算代价提高收敛速度; （ii）我们提出了一类归一化的类流形，它以最小的信息损失对目标进行编码，提高了随机投影编码的准确性，同时获得了相同的收敛速度。在CIFAR-100，CUB200-2011，Imagenet和MIT Places上的实验表明，所提出的方法极大地提高了收敛速度，同时达到了极具竞争力的准确率。

##### URL
[http://arxiv.org/abs/1806.10805](http://arxiv.org/abs/1806.10805)

##### PDF
[http://arxiv.org/pdf/1806.10805](http://arxiv.org/pdf/1806.10805)

