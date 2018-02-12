---
layout: post
title: "Batch Kalman Normalization: Towards Training Deep Neural Networks with Micro-Batches"
date: 2018-02-09 05:19:16
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification
author: Guangrun Wang, Jiefeng Peng, Ping Luo, Xinjiang Wang, Liang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
As an indispensable component, Batch Normalization (BN) has successfully improved the training of deep neural networks (DNNs) with mini-batches, by normalizing the distribution of the internal representation for each hidden layer. However, the effectiveness of BN would diminish with scenario of micro-batch (e.g., less than 10 samples in a mini-batch), since the estimated statistics in a mini-batch are not reliable with insufficient samples. In this paper, we present a novel normalization method, called Batch Kalman Normalization (BKN), for improving and accelerating the training of DNNs, particularly under the context of micro-batches. Specifically, unlike the existing solutions treating each hidden layer as an isolated system, BKN treats all the layers in a network as a whole system, and estimates the statistics of a certain layer by considering the distributions of all its preceding layers, mimicking the merits of Kalman Filtering. BKN has two appealing properties. First, it enables more stable training and faster convergence compared to previous works. Second, training DNNs using BKN performs substantially better than those using BN and its variants, especially when very small mini-batches are presented. On the image classification benchmark of ImageNet, using BKN powered networks we improve upon the best-published model-zoo results: reaching 74.0% top-1 val accuracy for InceptionV2. More importantly, using BKN achieves the comparable accuracy with extremely smaller batch size, such as 64 times smaller on CIFAR-10/100 and 8 times smaller on ImageNet.

##### Abstract (translated by Google)
批量归一化（Batch Normalization，BN）作为一个不可缺少的组成部分，通过对每个隐层的内部表示的分布进行归一化，成功地改进了小批量深度神经网络（DNNs）的训练。但是，微型批次的情况下（例如，小批量中少于10个样品），BN的有效性会降低，因为如果样品数量不足，小批量的估计统计数据不可靠。在本文中，我们提出了一种称为批量卡尔曼归一化（BKN）的新的归一化方法，用于改进和加速DNN的训练，特别是在小批量的情况下。具体而言，不同于现有解决方案将每个隐藏层视为孤立系统，BKN将网络中的所有层视为整个系统，并且通过考虑其所有前面的层的分布来估计某个层的统计，模仿卡尔曼滤波。 BKN有两个吸引人的属性。首先，与以前的作品相比，它可以实现更稳定的培训和更快的融合。其次，使用BKN进行DNN训练比使用BN及其变体的训练要好得多，特别是当出现非常小的小批量时。在ImageNet的图像分类标准中，使用BKN供电网络，我们改进了最佳发布的模型动物园结果：InceptionV2达到了74.0％的top-1 val精度。更重要的是，使用BKN可以在极小批量的情况下实现可比的精度，比如CIFAR-10/100小64倍，ImageNet小8倍。

##### URL
[http://arxiv.org/abs/1802.03133](http://arxiv.org/abs/1802.03133)

##### PDF
[http://arxiv.org/pdf/1802.03133](http://arxiv.org/pdf/1802.03133)

