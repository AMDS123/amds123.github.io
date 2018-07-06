---
layout: post
title: "Restructuring Batch Normalization to Accelerate CNN Training"
date: 2018-07-04 02:00:19
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Daejin Jung, Wonkyung Jung, and Byeongho Kim, Sunjung Lee, Wonjong Rhee, Jung Ho Ahn
mathjax: true
---

* content
{:toc}

##### Abstract
Because CNN models are compute-intensive, where billions of operations can be required just for an inference over a single input image, a variety of CNN accelerators have been proposed and developed. For the early CNN models, the research mostly focused on convolutional and fully-connected layers because the two layers consumed most of the computation cycles. For more recent CNN models, however, non-convolutional layers have become comparably important because of the popular use of newly designed non-convolutional layers and because of the reduction in the number and size of convolutional filters. Non-convolutional layers, including batch normalization (BN), typically have relatively lower computational intensity compared to the convolutional or fully-connected layers, and hence are often constrained by main-memory bandwidth. In this paper, we focus on accelerating the BN layers among the non-convolutional layers, as BN has become a core design block of modern CNNs. A typical modern CNN has a large number of BN layers. BN requires mean and variance calculations over each mini-batch during training. Therefore, the existing memory-access reduction techniques, such as fusing multiple CONV layers, are not effective for accelerating BN due to their inability to optimize mini-batch related calculations. To address this increasingly important problem, we propose to restructure BN layers by first splitting it into two sub-layers and then combining the first sub-layer with its preceding convolutional layer and the second sub-layer with the following activation and convolutional layers. The proposed solution can significantly reduce main-memory accesses while training the latest CNN models, and the experiments on a chip multiprocessor with our modified Caffe implementation show that the proposed BN restructuring can improve the performance of DenseNet with 121 convolutional layers by 28.4%.

##### Abstract (translated by Google)
由于CNN模型是计算密集型的，只需要对单个输入图像进行推理就需要数十亿次操作，因此已经提出并开发了各种CNN加速器。对于早期的CNN模型，研究主要集中在卷积和完全连接的层，因为这两个层消耗了大部分计算周期。然而，对于更近期的CNN模型，非卷积层已经变得相当重要，因为新设计的非卷积层的普遍使用以及卷积滤波器的数量和尺寸的减少。与卷积或完全连接的层相比，非卷积层（包括批量归一化（BN））通常具有相对较低的计算强度，因此通常受主存储器带宽的约束。在本文中，我们专注于加速非卷积层中的BN层，因为BN已成为现代CNN的核心设计块。典型的现代CNN具有大量BN层。 BN要求在训练期间对每个小批量进行均值和方差计算。因此，现有的存储器访问减少技术，例如融合多个CONV层，由于无法优化与小批量相关的计算而对加速BN无效。为了解决这个日益重要的问题，我们建议重构BN层，首先将其分成两个子层，然后将第一个子层与其先前的卷积层和第二个子层与下面的激活和卷积层组合。所提出的解决方案可以在训练最新的CNN模型时显着减少主存储器访问，并且在我们修改的Caffe实现的芯片多处理器上的实验表明，所提出的BN重构可以将具有121个卷积层的DenseNet的性能提高28.4％。

##### URL
[http://arxiv.org/abs/1807.01702](http://arxiv.org/abs/1807.01702)

##### PDF
[http://arxiv.org/pdf/1807.01702](http://arxiv.org/pdf/1807.01702)

