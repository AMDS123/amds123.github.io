---
layout: post
title: "Learning Spatio-Temporal Representation with Pseudo-3D Residual Networks"
date: 2017-11-28 14:24:18
categories: arXiv_CV
tags: arXiv_CV CNN Video_Classification Classification Recognition
author: Zhaofan Qiu, Ting Yao, Tao Mei
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNN) have been regarded as a powerful class of models for image recognition problems. Nevertheless, it is not trivial when utilizing a CNN for learning spatio-temporal video representation. A few studies have shown that performing 3D convolutions is a rewarding approach to capture both spatial and temporal dimensions in videos. However, the development of a very deep 3D CNN from scratch results in expensive computational cost and memory demand. A valid question is why not recycle off-the-shelf 2D networks for a 3D CNN. In this paper, we devise multiple variants of bottleneck building blocks in a residual learning framework by simulating $3\times3\times3$ convolutions with $1\times3\times3$ convolutional filters on spatial domain (equivalent to 2D CNN) plus $3\times1\times1$ convolutions to construct temporal connections on adjacent feature maps in time. Furthermore, we propose a new architecture, named Pseudo-3D Residual Net (P3D ResNet), that exploits all the variants of blocks but composes each in different placement of ResNet, following the philosophy that enhancing structural diversity with going deep could improve the power of neural networks. Our P3D ResNet achieves clear improvements on Sports-1M video classification dataset against 3D CNN and frame-based 2D CNN by 5.3% and 1.8%, respectively. We further examine the generalization performance of video representation produced by our pre-trained P3D ResNet on five different benchmarks and three different tasks, demonstrating superior performances over several state-of-the-art techniques.

##### Abstract (translated by Google)
卷积神经网络（CNN）被认为是图像识别问题的一个强大的模型。尽管如此，利用CNN学习时空视频表示并不是微不足道的。一些研究表明，执行三维卷积是一个有价值的方法来捕捉视频中的空间和时间维度。然而，从头开始研制非常深的3D CNN会导致昂贵的计算成本和内存需求。一个有效的问题是为什么不回收3D CNN的现成2D网络。在本文中，我们通过在空间领域（相当于2D CNN）加上$ 3 \ times1 \ times1来模拟$ 3 \ times3 \ times3 $卷积与$ 1 \ times3 \ times3 $卷积滤波器，在残差学习框架中设计多个瓶颈构建块$卷积在时间上在相邻的特征地图上构建时间连接。此外，我们提出了一种新的架构，称为伪三维残差网络（P3D ResNet），它利用所有块的变体，但在ResNet的不同位置组成每个变体，遵循通过深入来增强结构多样性可以提高神经网络。我们的P3D ResNet在Sports-1M视频分类数据集中，对3D CNN和基于帧的2D CNN分别进行了5.3％和1.8％的明显改进。我们进一步研究了由我们的预先培训的P3D ResNet在五个不同的基准和三个不同的任务中产生的视频表示的泛化性能，展示了几种最先进技术的优越性能。

##### URL
[https://arxiv.org/abs/1711.10305](https://arxiv.org/abs/1711.10305)

##### PDF
[https://arxiv.org/pdf/1711.10305](https://arxiv.org/pdf/1711.10305)

