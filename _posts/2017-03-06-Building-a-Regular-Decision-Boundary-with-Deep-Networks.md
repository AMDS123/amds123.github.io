---
layout: post
title: "Building a Regular Decision Boundary with Deep Networks"
date: 2017-03-06 09:21:35
categories: arXiv_CV
tags: arXiv_CV CNN
author: Edouard Oyallon
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we build a generic architecture of Convolutional Neural Networks to discover empirical properties of neural networks. Our first contribution is to introduce a state-of-the-art framework that depends upon few hyper parameters and to study the network when we vary them. It has no max pooling, no biases, only 13 layers, is purely convolutional and yields up to 95.4% and 79.6% accuracy respectively on CIFAR10 and CIFAR100. We show that the nonlinearity of a deep network does not need to be continuous, non expansive or point-wise, to achieve good performance. We show that increasing the width of our network permits being competitive with very deep networks. Our second contribution is an analysis of the contraction and separation properties of this network. Indeed, a 1-nearest neighbor classifier applied on deep features progressively improves with depth, which indicates that the representation is progressively more regular. Besides, we defined and analyzed local support vectors that separate classes locally. All our experiments are reproducible and code is available online, based on TensorFlow.

##### Abstract (translated by Google)
在这项工作中，我们建立了一个通用的卷积神经网络体系结构来发现神经网络的经验性质。我们的第一个贡献是引入一个依赖少量超参数的最先进的框架，并且在我们改变它们的时候研究网络。在CIFAR10和CIFAR100上，它没有最大汇集，没有偏差，只有13层，纯粹是卷积的，分别产生95.4％和79.6％的精度。我们表明，深度网络的非线性不需要是连续的，不扩张的或点明智的，以实现良好的性能。我们表明，增加我们的网络的宽度允许与非常深的网络竞争。我们的第二个贡献是分析这个网络的收缩和分离特性。事实上，应用于深度特征的1最近邻分类器随着深度逐渐提高，这表明该表示是逐渐更规则的。此外，我们定义和分析本地分类的本地支持向量。我们所有的实验都是可重现的，并且基于TensorFlow在线提供代码。

##### URL
[https://arxiv.org/abs/1703.01775](https://arxiv.org/abs/1703.01775)

##### PDF
[https://arxiv.org/pdf/1703.01775](https://arxiv.org/pdf/1703.01775)

