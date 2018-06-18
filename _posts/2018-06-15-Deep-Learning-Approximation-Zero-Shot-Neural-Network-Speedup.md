---
layout: post
title: "Deep Learning Approximation: Zero-Shot Neural Network Speedup"
date: 2018-06-15 01:25:47
categories: arXiv_CV
tags: arXiv_CV Optimization Deep_Learning
author: Michele Pratusevich
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks offer high-accuracy solutions to a range of problems, but are costly to run in production systems because of computational and memory requirements during a forward pass. Given a trained network, we propose a techique called Deep Learning Approximation to build a faster network in a tiny fraction of the time required for training by only manipulating the network structure and coefficients without requiring re-training or access to the training data. Speedup is achieved by by applying a sequential series of independent optimizations that reduce the floating-point operations (FLOPs) required to perform a forward pass. First, lossless optimizations are applied, followed by lossy approximations using singular value decomposition (SVD) and low-rank matrix decomposition. The optimal approximation is chosen by weighing the relative accuracy loss and FLOP reduction according to a single parameter specified by the user. On PASCAL VOC 2007 with the YOLO network, we show an end-to-end 2x speedup in a network forward pass with a 5% drop in mAP that can be re-gained by finetuning.

##### Abstract (translated by Google)
神经网络为各种问题提供高精度解决方案，但由于正向通过期间的计算和存储需求，在生产系统中运行成本高昂。鉴于训练有素的网络，我们提出了一种名为“深度学习逼近”的技术，只需操纵网络结构和系数而不需要重新培训或获取训练数据，就可以在很短的时间内建立一个更快的网络。加速是通过应用连续的一系列独立优化来实现的，这些优化降低了执行正向传递所需的浮点运算（FLOP）。首先，应用无损优化，接下来是使用奇异值分解（SVD）和低秩矩阵分解的有损近似。通过根据用户指定的单个参数对相对精度损失和FLOP降低进行加权来选择最佳逼近。在使用YOLO网络的PASCAL VOC 2007中，我们在网络正向传递中显示端到端2x加速，并且可以通过微调重新获得mAP下降5％。

##### URL
[http://arxiv.org/abs/1806.05779](http://arxiv.org/abs/1806.05779)

##### PDF
[http://arxiv.org/pdf/1806.05779](http://arxiv.org/pdf/1806.05779)

