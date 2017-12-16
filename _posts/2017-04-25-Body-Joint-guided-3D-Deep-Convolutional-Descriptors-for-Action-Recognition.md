---
layout: post
title: "Body Joint guided 3D Deep Convolutional Descriptors for Action Recognition"
date: 2017-04-25 15:08:05
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Detection Recognition
author: Congqi Cao, Yifan Zhang, Chunjie Zhang, Hanqing Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Three dimensional convolutional neural networks (3D CNNs) have been established as a powerful tool to simultaneously learn features from both spatial and temporal dimensions, which is suitable to be applied to video-based action recognition. In this work, we propose not to directly use the activations of fully-connected layers of a 3D CNN as the video feature, but to use selective convolutional layer activations to form a discriminative descriptor for video. It pools the feature on the convolutional layers under the guidance of body joint positions. Two schemes of mapping body joints into convolutional feature maps for pooling are discussed. The body joint positions can be obtained from any off-the-shelf skeleton estimation algorithm. The helpfulness of the body joint guided feature pooling with inaccurate skeleton estimation is systematically evaluated. To make it end-to-end and do not rely on any sophisticated body joint detection algorithm, we further propose a two-stream bilinear model which can learn the guidance from the body joints and capture the spatio-temporal features simultaneously. In this model, the body joint guided feature pooling is conveniently formulated as a bilinear product operation. Experimental results on three real-world datasets demonstrate the effectiveness of body joint guided pooling which achieves promising performance.

##### Abstract (translated by Google)
三维卷积神经网络（3D CNNs）已经成为同时学习空间和时间特征的有力工具，适用于视频动作识别。在这项工作中，我们建议不要直接使用3D CNN的完全连接层的激活作为视频特征，而是使用选择性卷积层激活来形成视频的判别描述符。它在身体关节位置的引导下将特征集中在卷积层上。讨论了将身体关节映射为卷积特征映射的两种方案。身体关节位置可以从任何现成的骨架估计算法获得。系统地评估了身体联合引导特征集中不准确的骨架估计的有用性。为了达到端到端，不依赖任何复杂的身体联合检测算法，我们进一步提出了一个双流双线性模型，可以从身体关节学习指导，同时捕获时空特征。在这个模型中，身体关节引导特征池被方便地制定为双线性产品操作。三个真实世界的数据集上的实验结果证明了身体联合导航池的有效性，并取得了良好的性能。

##### URL
[https://arxiv.org/abs/1704.07160](https://arxiv.org/abs/1704.07160)

##### PDF
[https://arxiv.org/pdf/1704.07160](https://arxiv.org/pdf/1704.07160)

