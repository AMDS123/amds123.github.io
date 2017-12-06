---
layout: post
title: 'Shift: A Zero FLOP, Zero Parameter Alternative to Spatial Convolutions'
date: 2017-12-03 07:07:21
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Bichen Wu, Alvin Wan, Xiangyu Yue, Peter Jin, Sicheng Zhao, Noah Golmant, Amir Gholaminejad, Joseph Gonzalez, Kurt Keutzer
---

* content
{:toc}

##### Abstract
Neural networks rely on convolutions to aggregate spatial information. However, spatial convolutions are expensive in terms of model size and computation, both of which grow quadratically with respect to kernel size. In this paper, we present a parameter-free, FLOP-free "shift" operation as an alternative to spatial convolutions. We fuse shifts and point-wise convolutions to construct end-to-end trainable shift-based modules, with a hyperparameter characterizing the tradeoff between accuracy and efficiency. To demonstrate the operation's efficacy, we replace ResNet's 3x3 convolutions with shift-based modules for improved CIFAR10 and CIFAR100 accuracy using 60% fewer parameters; we additionally demonstrate the operation's resilience to parameter reduction on ImageNet, outperforming ResNet family members. We finally show the shift operation's applicability across domains, achieving strong performance with fewer parameters on classification, face verification and style transfer.

##### Abstract (translated by Google)
神经网络依靠卷积来聚合空间信息。然而，就模型大小和计算而言，空间卷积是昂贵的，两者相对于核心大小二次增长。在本文中，我们提出了一个无参数，无FLOP的“移位”操作来替代空间卷积。我们融合了移位和逐点卷积来构建端到端的可训练的基于换档的模块，其中超参数表征了准确性和效率之间的折衷。为了演示操作的有效性，我们用基于移位的模块替换了ResNet的3x3卷积，以提高CIFAR10和CIFAR100的精度，使用的参数减少了60％我们还演示了该操作在ImageNet上减少参数的恢复能力，优于ResNet家族成员。我们最终显示了跨领域的转换操作的适用性，以较少的分类参数，面部验证和样式转换实现了强大的性能。

##### URL
[http://arxiv.org/abs/1711.08141](http://arxiv.org/abs/1711.08141)

