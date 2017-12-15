---
layout: post
title: "Order-aware Convolutional Pooling for Video Based Action Recognition"
date: 2016-01-31 10:58:11
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Recognition
author: Peng Wang, Lingqiao Liu, Chunhua Shen, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Most video based action recognition approaches create the video-level representation by temporally pooling the features extracted at each frame. The pooling methods that they adopt, however, usually completely or partially neglect the dynamic information contained in the temporal domain, which may undermine the discriminative power of the resulting video representation since the video sequence order could unveil the evolution of a specific event or action. To overcome this drawback and explore the importance of incorporating the temporal order information, in this paper we propose a novel temporal pooling approach to aggregate the frame-level features. Inspired by the capacity of Convolutional Neural Networks (CNN) in making use of the internal structure of images for information abstraction, we propose to apply the temporal convolution operation to the frame-level representations to extract the dynamic information. However, directly implementing this idea on the original high-dimensional feature would inevitably result in parameter explosion. To tackle this problem, we view the temporal evolution of the feature value at each feature dimension as a 1D signal and learn a unique convolutional filter bank for each of these 1D signals. We conduct experiments on two challenging video-based action recognition datasets, HMDB51 and UCF101; and demonstrate that the proposed method is superior to the conventional pooling methods.

##### Abstract (translated by Google)
大多数基于视频的动作识别方法通过暂时合并在每帧提取的特征来创建视频级表示。然而，他们采用的汇集方法通常完全或部分地忽略了包含在时域中的动态信息，这可能会破坏由此产生的视频表示的区分能力，因为视频序列顺序可能揭示特定事件或动作的演变。为了克服这个缺点，并探讨时间顺序信息的重要性，在本文中，我们提出了一种新的时间池方法来聚合帧级特征。受到卷积神经网络（CNN）利用图像内部信息抽象的能力的启发，我们提出将时间卷积运算应用于帧级表示以提取动态信息。然而，直接在原有的高维特征上实现这个想法将不可避免地导致参数爆炸。为了解决这个问题，我们将每个特征维的特征值的时间演化看作一维信号，并且为这些一维信号中的每一个学习独特的卷积滤波器组。我们在两个具有挑战性的视频动作识别数据集HMDB51和UCF101上进行实验;并证明了所提出的方法优于传统的池化方法。

##### URL
[https://arxiv.org/abs/1602.00224](https://arxiv.org/abs/1602.00224)

##### PDF
[https://arxiv.org/pdf/1602.00224](https://arxiv.org/pdf/1602.00224)

