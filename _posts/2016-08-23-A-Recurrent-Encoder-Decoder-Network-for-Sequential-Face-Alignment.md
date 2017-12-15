---
layout: post
title: "A Recurrent Encoder-Decoder Network for Sequential Face Alignment"
date: 2016-08-23 01:23:48
categories: arXiv_CV
tags: arXiv_CV Face
author: Xi Peng, Rogerio S. Feris, Xiaoyu Wang, Dimitris N. Metaxas
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel recurrent encoder-decoder network model for real-time video-based face alignment. Our proposed model predicts 2D facial point maps regularized by a regression loss, while uniquely exploiting recurrent learning at both spatial and temporal dimensions. At the spatial level, we add a feedback loop connection between the combined output response map and the input, in order to enable iterative coarse-to-fine face alignment using a single network model. At the temporal level, we first decouple the features in the bottleneck of the network into temporal-variant factors, such as pose and expression, and temporal-invariant factors, such as identity information. Temporal recurrent learning is then applied to the decoupled temporal-variant features, yielding better generalization and significantly more accurate results at test time. We perform a comprehensive experimental analysis, showing the importance of each component of our proposed model, as well as superior results over the state-of-the-art in standard datasets.

##### Abstract (translated by Google)
我们提出了一个新颖的循环编码器 - 解码器网络模型，用于基于视频的实时人脸对齐。我们提出的模型预测2D回归损失规则化的面部点图，同时在空间和时间维度上独特地利用回归学习。在空间层面，我们在组合的输出响应图和输入之间添加反馈环路连接，以便使用单个网络模型实现迭代的从粗到精的面对准。在时间层面上，我们首先将网络瓶颈中的特征分解为姿态和表达等时变因素以及身份信息等时态不变因素。然后将时间递归学习应用于解耦的时变特征，在测试时产生更好的泛化和更精确的结果。我们进行了全面的实验分析，显示了我们提出的模型的每个组成部分的重要性，以及优于标准数据集中最先进的结果。

##### URL
[https://arxiv.org/abs/1608.05477](https://arxiv.org/abs/1608.05477)

##### PDF
[https://arxiv.org/pdf/1608.05477](https://arxiv.org/pdf/1608.05477)

