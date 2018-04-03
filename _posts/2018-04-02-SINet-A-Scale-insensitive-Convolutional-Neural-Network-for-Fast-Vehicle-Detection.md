---
layout: post
title: "SINet: A Scale-insensitive Convolutional Neural Network for Fast Vehicle Detection"
date: 2018-04-02 09:27:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Xiaowei Hu, Xuemiao Xu, Yongjie Xiao, Hao Chen, Shengfeng He, Jing Qin, Pheng-Ann Heng
mathjax: true
---

* content
{:toc}

##### Abstract
Vision-based vehicle detection approaches achieve incredible success in recent years with the development of deep convolutional neural network (CNN). However, existing CNN based algorithms suffer from the problem that the convolutional features are scale-sensitive in object detection task but it is common that traffic images and videos contain vehicles with a large variance of scales. In this paper, we delve into the source of scale sensitivity, and reveal two key issues: 1) existing RoI pooling destroys the structure of small scale objects, 2) the large intra-class distance for a large variance of scales exceeds the representation capability of a single network. Based on these findings, we present a scale-insensitive convolutional neural network (SINet) for fast detecting vehicles with a large variance of scales. First, we present a context-aware RoI pooling to maintain the contextual information and original structure of small scale objects. Second, we present a multi-branch decision network to minimize the intra-class distance of features. These lightweight techniques bring zero extra time complexity but prominent detection accuracy improvement. The proposed techniques can be equipped with any deep network architectures and keep them trained end-to-end. Our SINet achieves state-of-the-art performance in terms of accuracy and speed (up to 37 FPS) on the KITTI benchmark and a new highway dataset, which contains a large variance of scales and extremely small objects.

##### Abstract (translated by Google)
随着深度卷积神经网络（CNN）的发展，基于视觉的车辆检测方法近年来取得了令人难以置信的成功。然而，现有的基于CNN的算法面临的问题是卷积特征在物体检测任务中是尺度敏感的，但是通常情况下，交通图像和视频包含具有较大尺度变化的车辆。在本文中，我们深入研究了尺度敏感性的来源，揭示了两个关键问题：1）现有的漫游池破坏了小尺度物体的结构，2）大尺度方差的大类内距离超过了表示能力的单一网络。基于这些发现，我们提出了一种用于快速检测具有很大尺度变化的车辆的不敏感卷积神经网络（SINet）。首先，我们提出了一个上下文感知的RoI池来维护小规模对象的上下文信息和原始结构。其次，我们提出了一个多分支决策网络来最小化特征的类内距离。这些轻量级技术带来零时间复杂度，但突出的检测精度提高所提出的技术可以配备任何深度网络架构，并保持端到端的训练。我们的SINet在KITTI基准测试的准确性和速度（高达37 FPS）方面实现了最先进的性能表现，以及一个新的高速公路数据集，其中包含很大的尺度变化和极小的物体。

##### URL
[http://arxiv.org/abs/1804.00433](http://arxiv.org/abs/1804.00433)

##### PDF
[http://arxiv.org/pdf/1804.00433](http://arxiv.org/pdf/1804.00433)

