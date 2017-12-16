---
layout: post
title: "Fast Recurrent Fully Convolutional Networks for Direct Perception in Autonomous Driving"
date: 2017-11-20 03:06:42
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Classification
author: Yiqi Hou, Sascha Hornauer, Karl Zipser
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional neural networks (CNNs) have been shown to perform extremely well at a variety of tasks including subtasks of autonomous driving such as image segmentation and object classification. However, networks designed for these tasks typically require vast quantities of training data and long training periods to converge. We investigate the design rationale behind end-to-end driving network designs by proposing and comparing three small and computationally inexpensive deep end-to-end neural network models that generate driving control signals directly from input images. In contrast to prior work that segments the autonomous driving task, our models take on a novel approach to the autonomous driving problem by utilizing deep and thin Fully Convolutional Nets (FCNs) with recurrent neural nets and low parameter counts to tackle a complex end-to-end regression task predicting both steering and acceleration commands. In addition, we include layers optimized for classification to allow the networks to implicitly learn image semantics. We show that the resulting networks use 3x fewer parameters than the most recent comparable end-to-end driving network and 500x fewer parameters than the AlexNet variations and converge both faster and to lower losses while maintaining robustness against overfitting.

##### Abstract (translated by Google)
深卷积神经网络（CNNs）在包括图像分割和对象分类等自主驾驶子任务在内的各种任务中表现出色。但是，为这些任务设计的网络通常需要大量的训练数据和长的训练时间才能收敛。我们通过提出并比较三个小而计算便宜的深度端到端神经网络模型，直接从输入图像生成驱动控制信号，来研究端到端驱动网络设计背后的设计原理。与先前的分割自主驾驶任务的工作相比，我们的模型通过利用具有递归神经网络和低参数计数的深而薄的全卷积网络（FCN）来处理复杂的端到端 - 回归任务预测转向和加速命令。另外，我们还包含了针对分类进行优化的层，以允许网络隐式学习图像语义。我们表明，由此产生的网络使用的参数比最近比较的端到端驱动网络少3倍，比AlexNet变量少500倍的参数，并且在保持针对过拟合的鲁棒性的同时，更快地收敛并降低损失。

##### URL
[https://arxiv.org/abs/1711.06459](https://arxiv.org/abs/1711.06459)

##### PDF
[https://arxiv.org/pdf/1711.06459](https://arxiv.org/pdf/1711.06459)

