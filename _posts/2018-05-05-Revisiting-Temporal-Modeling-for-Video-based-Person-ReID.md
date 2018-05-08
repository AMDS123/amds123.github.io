---
layout: post
title: "Revisiting Temporal Modeling for Video-based Person ReID"
date: 2018-05-05 18:56:38
categories: arXiv_CV
tags: arXiv_CV Attention RNN
author: Jiyang Gao, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Video-based person reID is an important task, which has received much attention in recent years due to the increasing demand in surveillance and camera networks. A typical video-based person reID system consists of three parts: an image-level feature extractor ( e.g. CNN), a temporal modeling method to aggregate temporal features and a loss function. Although many methods on temporal modeling have been proposed, it is still hard for us to find an apple-to-apple comparison among these methods, because the choice of base network architecture and loss function also have a large impact on the final performance. Thus, we comprehensively study and compare four different temporal modeling methods (temporal pooling, temporal attention, RNN and 3D convnets) for video-based person reID. We also propose a new attention generation network which adopts temporal convolution to extract temporal information among frames. The evaluation is done on the MARS dataset, and our methods outperform state-of-the-art methods by a large margin. Our source codes are released at https://github.com/jiyanggao/Video-Person-ReID.

##### Abstract (translated by Google)
基于视频的人员reID是一项重要的任务，近年来，由于监控和摄像机网络需求的增加，这种重要任务受到了很多关注。典型的基于视频的人类reID系统由三部分组成：图像级特征提取器（例如CNN），聚合时间特征的时间建模方法和损失函数。虽然已经提出了很多时间建模方法，但我们仍然很难找到这些方法之间的苹果对苹果比较，因为基本网络架构和丢失函数的选择对最终性能也有很大影响。因此，我们全面研究并比较了基于视频的人员reID的四种不同的时间建模方法（时间池，时间关注，RNN和3D小点）。我们还提出了一种新的注意力生成网络，它采用时间卷积来提取帧间的时间信息。评估是在MARS数据集上完成的，我们的方法大大超过了最先进的方法。我们的源代码在https://github.com/jiyanggao/Video-Person-ReID发布。

##### URL
[http://arxiv.org/abs/1805.02104](http://arxiv.org/abs/1805.02104)

##### PDF
[http://arxiv.org/pdf/1805.02104](http://arxiv.org/pdf/1805.02104)

