---
layout: post
title: "Data-dependent Initializations of Convolutional Neural Networks"
date: 2016-09-22 22:14:17
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Image_Classification Classification Detection
author: Philipp Krähenbühl, Carl Doersch, Jeff Donahue, Trevor Darrell
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks spread through computer vision like a wildfire, impacting almost all visual tasks imaginable. Despite this, few researchers dare to train their models from scratch. Most work builds on one of a handful of ImageNet pre-trained models, and fine-tunes or adapts these for specific tasks. This is in large part due to the difficulty of properly initializing these networks from scratch. A small miscalibration of the initial weights leads to vanishing or exploding gradients, as well as poor convergence properties. In this work we present a fast and simple data-dependent initialization procedure, that sets the weights of a network such that all units in the network train at roughly the same rate, avoiding vanishing or exploding gradients. Our initialization matches the current state-of-the-art unsupervised or self-supervised pre-training methods on standard computer vision tasks, such as image classification and object detection, while being roughly three orders of magnitude faster. When combined with pre-training methods, our initialization significantly outperforms prior work, narrowing the gap between supervised and unsupervised pre-training.

##### Abstract (translated by Google)
卷积神经网络像野火一样通过计算机视觉传播，几乎影响了所有可以想象的视觉任务。尽管如此，很少有研究者敢于从零开始训练模型。大部分工作都是基于少数ImageNet预先训练的模型之一构建的，并针对特定任务进行微调或调整。这在很大程度上是由于从零开始正确初始化这些网络的困难。初始权重的小误差导致消失或爆炸的梯度，以及收敛性能差。在这项工作中，我们提出了一个快速和简单的数据相关的初始化过程，设置网络的权重，使网络中的所有单位大致相同的速度训练，避免消失或爆炸梯度。我们的初始化与标准计算机视觉任务（例如图像分类和目标检测）的当前最先进的无监督或自监督的预训练方法相匹配，同时快大约三个数量级。当与预训练方法相结合时，我们的初始化显着优于先前的训练，缩小了有监督和无监督预训练之间的差距。

##### URL
[https://arxiv.org/abs/1511.06856](https://arxiv.org/abs/1511.06856)

##### PDF
[https://arxiv.org/pdf/1511.06856](https://arxiv.org/pdf/1511.06856)

