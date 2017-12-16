---
layout: post
title: "Image-based Localization using Hourglass Networks"
date: 2017-08-24 06:10:26
categories: arXiv_CV
tags: arXiv_CV CNN Transfer_Learning Classification
author: Iaroslav Melekhov, Juha Ylioinas, Juho Kannala, Esa Rahtu
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose an encoder-decoder convolutional neural network (CNN) architecture for estimating camera pose (orientation and location) from a single RGB-image. The architecture has a hourglass shape consisting of a chain of convolution and up-convolution layers followed by a regression part. The up-convolution layers are introduced to preserve the fine-grained information of the input image. Following the common practice, we train our model in end-to-end manner utilizing transfer learning from large scale classification data. The experiments demonstrate the performance of the approach on data exhibiting different lighting conditions, reflections, and motion blur. The results indicate a clear improvement over the previous state-of-the-art even when compared to methods that utilize sequence of test frames instead of a single frame.

##### Abstract (translated by Google)
在本文中，我们提出了一种编码器 - 解码器卷积神经网络（CNN）架构，用于从单个RGB图像估计相机姿态（方向和位置）。该体系结构具有沙漏形状，由一系列卷积和上卷积层组成，之后是回归部分。引入上卷积层以保留输入图像的细粒度信息。按照惯例，我们使用大规模分类数据的转移学习，以端到端的方式来训练我们的模型。实验证明了该方法在数据展现不同照明条件，反射和运动模糊方面的性能。即使与利用测试帧序列而不是单个帧的方法相比，结果也显示出比先前技术水平有明显的改进。

##### URL
[https://arxiv.org/abs/1703.07971](https://arxiv.org/abs/1703.07971)

##### PDF
[https://arxiv.org/pdf/1703.07971](https://arxiv.org/pdf/1703.07971)

