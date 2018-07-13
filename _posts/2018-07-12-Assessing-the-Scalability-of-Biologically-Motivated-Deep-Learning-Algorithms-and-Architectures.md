---
layout: post
title: "Assessing the Scalability of Biologically-Motivated Deep Learning Algorithms and Architectures"
date: 2018-07-12 12:53:50
categories: arXiv_AI
tags: arXiv_AI Deep_Learning
author: Sergey Bartunov, Adam Santoro, Blake A. Richards, Geoffrey E. Hinton, Timothy Lillicrap
mathjax: true
---

* content
{:toc}

##### Abstract
The backpropagation of error algorithm (BP) is often said to be impossible to implement in a real brain. The recent success of deep networks in machine learning and AI, however, has inspired proposals for understanding how the brain might learn across multiple layers, and hence how it might implement or approximate BP. As of yet, none of these proposals have been rigorously evaluated on tasks where BP-guided deep learning has proved critical, or in architectures more structured than simple fully-connected networks. Here we present the first results on scaling up biologically motivated models of deep learning on datasets which need deep networks with appropriate architectures to achieve good performance. We present results on the MNIST, CIFAR-10, and ImageNet datasets and explore variants of target-propagation (TP) and feedback alignment (FA) algorithms, and explore performance in both fully- and locally-connected architectures. We also introduce weight-transport-free variants of difference target propagation (DTP) modified to remove backpropagation from the penultimate layer. Many of these algorithms perform well for MNIST, but for CIFAR and ImageNet we find that TP and FA variants perform significantly worse than BP, especially for networks composed of locally connected units, opening questions about whether new architectures and algorithms are required to scale these approaches. Our results and implementation details help establish baselines for biologically motivated deep learning schemes going forward.

##### Abstract (translated by Google)
错误算法（BP）的反向传播通常被认为不可能在真实的大脑中实现。然而，最近机器学习和人工智能中的深度网络的成功启发了理解大脑如何跨多层学习，以及它如何实现或近似BP的建议。到目前为止，这些提案都没有在BP指导的深度学习被证明是关键的任务中得到严格评估，或者在结构比简单的全连接网络更加结构化。在这里，我们提出了在数据集上扩展生物学动机的深度学习模型的第一批结果，这些数据集需要具有适当架构的深度网络以实现良好的性能。我们在MNIST，CIFAR-10和ImageNet数据集上展示结果，探索目标传播（TP）和反馈对齐（FA）算法的变体，并探索全连接和本地连接架构的性能。我们还引入了不受重量传递的差异目标传播变体（DTP），其被修改以从倒数第二层去除反向传播。其中许多算法对MNIST表现良好，但对于CIFAR和ImageNet，我们发现TP和FA变体的性能明显差于BP，尤其是对于由本地连接单元组成的网络，这就打开了关于是否需要新架构和算法来扩展这些方法的问题。我们的结果和实施细节有助于为未来的生物学动机深度学习计划建立基线。

##### URL
[http://arxiv.org/abs/1807.04587](http://arxiv.org/abs/1807.04587)

##### PDF
[http://arxiv.org/pdf/1807.04587](http://arxiv.org/pdf/1807.04587)

