---
layout: post
title: "LCNN: Lookup-based Convolutional Neural Network"
date: 2017-06-13 02:43:30
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning
author: Hessam Bagherinezhad, Mohammad Rastegari, Ali Farhadi
mathjax: true
---

* content
{:toc}

##### Abstract
Porting state of the art deep learning algorithms to resource constrained compute platforms (e.g. VR, AR, wearables) is extremely challenging. We propose a fast, compact, and accurate model for convolutional neural networks that enables efficient learning and inference. We introduce LCNN, a lookup-based convolutional neural network that encodes convolutions by few lookups to a dictionary that is trained to cover the space of weights in CNNs. Training LCNN involves jointly learning a dictionary and a small set of linear combinations. The size of the dictionary naturally traces a spectrum of trade-offs between efficiency and accuracy. Our experimental results on ImageNet challenge show that LCNN can offer 3.2x speedup while achieving 55.1% top-1 accuracy using AlexNet architecture. Our fastest LCNN offers 37.6x speed up over AlexNet while maintaining 44.3% top-1 accuracy. LCNN not only offers dramatic speed ups at inference, but it also enables efficient training. In this paper, we show the benefits of LCNN in few-shot learning and few-iteration learning, two crucial aspects of on-device training of deep learning models.

##### Abstract (translated by Google)
将最先进的深度学习算法移植到资源受限的计算平台（例如VR，AR，可穿戴设备）是非常具有挑战性的。我们提出了一个快速，紧凑，精确的卷积神经网络模型，使高效的学习和推理。我们介绍LCNN，一种基于查找的卷积神经网络，通过少量查找将卷积编码成一个经过训练以覆盖CNN中权重空间的字典。培训LCNN涉及联合学习字典和一小组线性组合。字典的大小自然会在效率和准确性之间进行权衡。我们在ImageNet上的实验结果表明，LCNN可以提供3.2倍的加速，同时使用AlexNet架构实现55.1％的一级精度。我们最快的LCNN提供比AlexNet快37.6倍的速度，同时保持44.3％的最高精度。 LCNN不仅在推理上提供了惊人的速度提升，而且还提供了高效的培训。在本文中，我们展示了LCNN在少量学习和少量迭代学习中的好处，这是深度学习模型的在线培训的两个关键方面。

##### URL
[https://arxiv.org/abs/1611.06473](https://arxiv.org/abs/1611.06473)

##### PDF
[https://arxiv.org/pdf/1611.06473](https://arxiv.org/pdf/1611.06473)

