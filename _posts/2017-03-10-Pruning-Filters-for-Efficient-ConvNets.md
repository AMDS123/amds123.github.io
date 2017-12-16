---
layout: post
title: "Pruning Filters for Efficient ConvNets"
date: 2017-03-10 17:57:56
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference
author: Hao Li, Asim Kadav, Igor Durdanovic, Hanan Samet, Hans Peter Graf
mathjax: true
---

* content
{:toc}

##### Abstract
The success of CNNs in various applications is accompanied by a significant increase in the computation and parameter storage costs. Recent efforts toward reducing these overheads involve pruning and compressing the weights of various layers without hurting original accuracy. However, magnitude-based pruning of weights reduces a significant number of parameters from the fully connected layers and may not adequately reduce the computation costs in the convolutional layers due to irregular sparsity in the pruned networks. We present an acceleration method for CNNs, where we prune filters from CNNs that are identified as having a small effect on the output accuracy. By removing whole filters in the network together with their connecting feature maps, the computation costs are reduced significantly. In contrast to pruning weights, this approach does not result in sparse connectivity patterns. Hence, it does not need the support of sparse convolution libraries and can work with existing efficient BLAS libraries for dense matrix multiplications. We show that even simple filter pruning techniques can reduce inference costs for VGG-16 by up to 34% and ResNet-110 by up to 38% on CIFAR10 while regaining close to the original accuracy by retraining the networks.

##### Abstract (translated by Google)
CNN在各种应用中的成功伴随着计算和参数存储成本的显着增加。最近减少这些开销的努力涉及修剪和压缩各层的权重而不损害原始精度。然而，基于量值的权值修剪会减少来自完全连接层的大量参数，并且由于修剪网络中的不规则稀疏性而不能充分降低卷积层中的计算成本。我们提出了一种CNN的加速方法，我们从CNN中剪除被认为对输出精度影响很小的滤波器。通过将网络中的整个过滤器连同其连接特征图一起移除，计算成本显着降低。与修剪权重不同，这种方法不会导致稀疏的连接模式。因此，它不需要稀疏卷积库的支持，并且可以与现有的高效BLAS库一起用于密集矩阵乘法。我们发现即使是简单的滤波器修剪技术，在CIFAR10上，VGG-16的推理成本可以降低高达34％，ResNet-110可以降低高达38％，同时通过重新训练网络来恢复原始精度。

##### URL
[https://arxiv.org/abs/1608.08710](https://arxiv.org/abs/1608.08710)

##### PDF
[https://arxiv.org/pdf/1608.08710](https://arxiv.org/pdf/1608.08710)

