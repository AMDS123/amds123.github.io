---
layout: post
title: "Deep Roots: Improving CNN Efficiency with Hierarchical Filter Groups"
date: 2016-11-30 15:32:03
categories: arXiv_CV
tags: arXiv_CV Sparse CNN
author: Yani Ioannou, Duncan Robertson, Roberto Cipolla, Antonio Criminisi
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a new method for creating computationally efficient and compact convolutional neural networks (CNNs) using a novel sparse connection structure that resembles a tree root. This allows a significant reduction in computational cost and number of parameters compared to state-of-the-art deep CNNs, without compromising accuracy, by exploiting the sparsity of inter-layer filter dependencies. We validate our approach by using it to train more efficient variants of state-of-the-art CNN architectures, evaluated on the CIFAR10 and ILSVRC datasets. Our results show similar or higher accuracy than the baseline architectures with much less computation, as measured by CPU and GPU timings. For example, for ResNet 50, our model has 40% fewer parameters, 45% fewer floating point operations, and is 31% (12%) faster on a CPU (GPU). For the deeper ResNet 200 our model has 25% fewer floating point operations and 44% fewer parameters, while maintaining state-of-the-art accuracy. For GoogLeNet, our model has 7% fewer parameters and is 21% (16%) faster on a CPU (GPU).

##### Abstract (translated by Google)
我们提出了一种使用类似于树根的新颖稀疏连接结构来创建计算高效和紧凑的卷积神经网络（CNN）的新方法。与最先进的深度CNN相比，这可以显着降低计算成本和参数数量，同时不会降低准确性，因为它利用了层间滤波器相关性的稀疏性。我们验证了我们的方法，使用它来训练最先进的CNN体​​系结构的更高效的变体，并在CIFAR10和ILSVRC数据集上进行评估。我们的结果显示与基准架构相比相似或更高的精确度，计算量更少，由CPU和GPU计时衡量。例如，对于ResNet 50，我们的模型参数少40％，浮点运算少45％，CPU（GPU）速度快31％（12％）。对于更深的ResNet 200，我们的模型的浮点运算少了25％，参数少了44％，同时保持了最新的精度。对于GoogLeNet，我们的模型参数少7％，CPU（GPU）速度快21％（16％）。

##### URL
[https://arxiv.org/abs/1605.06489](https://arxiv.org/abs/1605.06489)

##### PDF
[https://arxiv.org/pdf/1605.06489](https://arxiv.org/pdf/1605.06489)

