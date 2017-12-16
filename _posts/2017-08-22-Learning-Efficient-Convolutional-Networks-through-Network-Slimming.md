---
layout: post
title: "Learning Efficient Convolutional Networks through Network Slimming"
date: 2017-08-22 07:35:26
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Zhuang Liu, Jianguo Li, Zhiqiang Shen, Gao Huang, Shoumeng Yan, Changshui Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
The deployment of deep convolutional neural networks (CNNs) in many real world applications is largely hindered by their high computational cost. In this paper, we propose a novel learning scheme for CNNs to simultaneously 1) reduce the model size; 2) decrease the run-time memory footprint; and 3) lower the number of computing operations, without compromising accuracy. This is achieved by enforcing channel-level sparsity in the network in a simple but effective way. Different from many existing approaches, the proposed method directly applies to modern CNN architectures, introduces minimum overhead to the training process, and requires no special software/hardware accelerators for the resulting models. We call our approach network slimming, which takes wide and large networks as input models, but during training insignificant channels are automatically identified and pruned afterwards, yielding thin and compact models with comparable accuracy. We empirically demonstrate the effectiveness of our approach with several state-of-the-art CNN models, including VGGNet, ResNet and DenseNet, on various image classification datasets. For VGGNet, a multi-pass version of network slimming gives a 20x reduction in model size and a 5x reduction in computing operations.

##### Abstract (translated by Google)
深度卷积神经网络（CNN）在许多现实应用中的部署在很大程度上受其计算成本高的阻碍。在本文中，我们提出了一种新颖的CNN学习方案，以同时1）减少模型的大小; 2）减少运行时内存占用;和3）减少计算操作的数量，而不会影响准确性。这是通过在网络中以简单而有效的方式实施通道级别的稀疏来实现的。与许多现有的方法不同，所提出的方法直接应用于现代CNN架构，向训练过程引入最小开销，并且不需要特定的软件/硬件加速器用于所得到的模型。我们称之为网络减肥方法，它将大型和大型网络作为输入模型，但是在训练过程中，不重要的通道会被自动识别和修剪，从而产生具有相当精确度的薄而紧凑的模型。我们用各种图像分类数据集上的几种最先进的CNN模型（包括VGGNet，ResNet和DenseNet）来验证我们方法的有效性。对于VGGNet来说，网络瘦身的多通道版本使得模型尺寸减小了20倍，计算操作减少了5倍。

##### URL
[https://arxiv.org/abs/1708.06519](https://arxiv.org/abs/1708.06519)

##### PDF
[https://arxiv.org/pdf/1708.06519](https://arxiv.org/pdf/1708.06519)

