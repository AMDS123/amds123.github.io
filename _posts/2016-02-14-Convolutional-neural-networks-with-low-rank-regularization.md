---
layout: post
title: "Convolutional neural networks with low-rank regularization"
date: 2016-02-14 03:46:09
categories: arXiv_CV
tags: arXiv_CV Regularization CNN
author: Cheng Tai, Tong Xiao, Yi Zhang, Xiaogang Wang, Weinan E
mathjax: true
---

* content
{:toc}

##### Abstract
Large CNNs have delivered impressive performance in various computer vision applications. But the storage and computation requirements make it problematic for deploying these models on mobile devices. Recently, tensor decompositions have been used for speeding up CNNs. In this paper, we further develop the tensor decomposition technique. We propose a new algorithm for computing the low-rank tensor decomposition for removing the redundancy in the convolution kernels. The algorithm finds the exact global optimizer of the decomposition and is more effective than iterative methods. Based on the decomposition, we further propose a new method for training low-rank constrained CNNs from scratch. Interestingly, while achieving a significant speedup, sometimes the low-rank constrained CNNs delivers significantly better performance than their non-constrained counterparts. On the CIFAR-10 dataset, the proposed low-rank NIN model achieves $91.31\%$ accuracy (without data augmentation), which also improves upon state-of-the-art result. We evaluated the proposed method on CIFAR-10 and ILSVRC12 datasets for a variety of modern CNNs, including AlexNet, NIN, VGG and GoogleNet with success. For example, the forward time of VGG-16 is reduced by half while the performance is still comparable. Empirical success suggests that low-rank tensor decompositions can be a very useful tool for speeding up large CNNs.

##### Abstract (translated by Google)
大型CNN在各种计算机视觉应用中已经取得了令人印象深刻的性能但是存储和计算要求使得在移动设备上部署这些模型成为问题。最近，张量分解被用来加速CNNs。在本文中，我们进一步发展了张量分解技术。我们提出了一种计算卷积核中冗余度的低秩张量分解算法。该算法找到分解的确切的全局优化器，并且比迭代方法更有效。在此基础上，进一步提出了一种从头开始训练低秩约束CNNs的新方法。有趣的是，虽然实现了显着的加速，但有时候低级别受限的CNN比非受限的对手有更好的性能。在CIFAR-10数据集中，所提出的低阶NIN模型达到$ 91.31 \％$的准确性（没有数据增加），这也改进了最新的结果。我们评估了在CIFAR-10和ILSVRC12数据集上针对各种现代CNN（包括AlexNet，NIN，VGG和GoogleNet）成功建立的方法。例如，VGG-16的转发时间减半，而性能仍然可比。经验的成功表明，低秩张量分解可能是加速大型CNN非常有用的工具。

##### URL
[https://arxiv.org/abs/1511.06067](https://arxiv.org/abs/1511.06067)

##### PDF
[https://arxiv.org/pdf/1511.06067](https://arxiv.org/pdf/1511.06067)

