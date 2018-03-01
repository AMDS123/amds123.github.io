---
layout: post
title: "Convolutional Neural Networks with Alternately Updated Clique"
date: 2018-02-28 14:04:38
categories: arXiv_CV
tags: arXiv_CV Attention CNN Recognition
author: Yibo Yang, Zhisheng Zhong, Tiancheng Shen, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Improving information flow in deep networks helps to ease the training difficulties and utilize parameters more efficiently. Here we propose a new convolutional neural network architecture with alternately updated clique (CliqueNet). In contrast to prior networks, there are both forward and backward connections between any two layers in the same block. The layers are constructed as a loop and are updated alternately. The CliqueNet has some unique properties. For each layer, it is both the input and output of any other layer in the same block, so that the information flow among layers is maximized. During propagation, the newly updated layers are concatenated to re-update previously updated layer, and parameters are reused for multiple times. This recurrent feedback structure is able to bring higher level visual information back to refine low-level filters and achieve spatial attention. We analyze the features generated at different stages and observe that using refined features leads to a better result. We adopt a multi-scale feature strategy that effectively avoids the progressive growth of parameters. Experiments on image recognition datasets including CIFAR-10, CIFAR-100, SVHN and ImageNet show that our proposed models achieve the state-of-the-art performance with fewer parameters.

##### Abstract (translated by Google)
改善深层网络中的信息流有助于缓解训练难度并更有效地利用参数。在这里，我们提出了一个新的卷积神经网络架构与交替更新的集团（CliqueNet）。与以前的网络相比，同一块中的任何两层之间都有前向和后向连接。这些图层被构造为一个循环并交替更新。 CliqueNet有一些独特的属性。对于每一层来说，它既是同一块中任何其他层的输入和输出，也是层间信息流的最大化。在传播过程中，将新更新的图层连接起来，以重新更新先前更新的图层，并且参数可以重复使用多次。这种经常性的反馈结构能够将更高层次的视觉信息带回来完善低级滤波器并实现空间关注。我们分析不同阶段生成的特征，并观察使用精化特征可以获得更好的结果。我们采用多尺度特征策略，有效避免了参数的逐步增长。对包括CIFAR-10，CIFAR-100，SVHN和ImageNet的图像识别数据集进行的实验表明，我们提出的模型通过较少的参数实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1802.10419](http://arxiv.org/abs/1802.10419)

##### PDF
[http://arxiv.org/pdf/1802.10419](http://arxiv.org/pdf/1802.10419)

