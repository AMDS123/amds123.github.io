---
layout: post
title: "Incremental Network Quantization: Towards Lossless CNNs with Low-Precision Weights"
date: 2017-08-25 13:21:18
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Aojun Zhou, Anbang Yao, Yiwen Guo, Lin Xu, Yurong Chen
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents incremental network quantization (INQ), a novel method, targeting to efficiently convert any pre-trained full-precision convolutional neural network (CNN) model into a low-precision version whose weights are constrained to be either powers of two or zero. Unlike existing methods which are struggled in noticeable accuracy loss, our INQ has the potential to resolve this issue, as benefiting from two innovations. On one hand, we introduce three interdependent operations, namely weight partition, group-wise quantization and re-training. A well-proven measure is employed to divide the weights in each layer of a pre-trained CNN model into two disjoint groups. The weights in the first group are responsible to form a low-precision base, thus they are quantized by a variable-length encoding method. The weights in the other group are responsible to compensate for the accuracy loss from the quantization, thus they are the ones to be re-trained. On the other hand, these three operations are repeated on the latest re-trained group in an iterative manner until all the weights are converted into low-precision ones, acting as an incremental network quantization and accuracy enhancement procedure. Extensive experiments on the ImageNet classification task using almost all known deep CNN architectures including AlexNet, VGG-16, GoogleNet and ResNets well testify the efficacy of the proposed method. Specifically, at 5-bit quantization, our models have improved accuracy than the 32-bit floating-point references. Taking ResNet-18 as an example, we further show that our quantized models with 4-bit, 3-bit and 2-bit ternary weights have improved or very similar accuracy against its 32-bit floating-point baseline. Besides, impressive results with the combination of network pruning and INQ are also reported. The code is available at this https URL

##### Abstract (translated by Google)
本文提出的增量网络量化（INQ）是一种新颖的方法，其目标是将任何预先训练的全精度卷积神经网络（CNN）模型有效地转换为一个低精度版本，其权重被限制为二或零的幂。不像现有的精确度损失显着的方法，我们的INQ有可能解决这个问题，因为有两个创新。一方面，我们引入三个相互依赖的操作，即权重划分，分组量化和重新训练。采用成熟的测量方法将预先训练的CNN模型的每一层的权重分成两个不相交的组。第一组中的权重负责形成低精度基础，因此它们通过可变长度编码方法来量化。另一组中的权重负责补偿量化的精度损失，因此它们是要重新训练的权重。另一方面，这三个操作在最近一次重复训练组中以迭代的方式重复，直到所有权重被转换成低精度的权重，作为增量网络量化和精度增强过程。使用几乎所有已知的深度CNN架构（包括AlexNet，VGG-16，GoogleNet和ResNet）对ImageNet分类任务进行了大量实验，证明了所提出的方法的有效性。具体来说，在5位量化时，我们的模型比32位浮点基准具有更高的精度。以ResNet-18为例，我们进一步表明，我们的具有4位，3位和2位三态权重的量化模型相对于其32位浮点基线具有改进的或非常相似的精度。此外，网络修剪和INQ结合的结果也有报道。该代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1702.03044](https://arxiv.org/abs/1702.03044)

##### PDF
[https://arxiv.org/pdf/1702.03044](https://arxiv.org/pdf/1702.03044)

