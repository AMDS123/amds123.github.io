---
layout: post
title: "Pooling the Convolutional Layers in Deep ConvNets for Action Recognition"
date: 2015-11-06 15:51:07
categories: arXiv_CV
tags: arXiv_CV Action_Recognition CNN Image_Classification Classification Recognition
author: Shichao Zhao, Yanbin Liu, Yahong Han, Richang Hong
mathjax: true
---

* content
{:toc}

##### Abstract
Deep ConvNets have shown its good performance in image classification tasks. However it still remains as a problem in deep video representation for action recognition. The problem comes from two aspects: on one hand, current video ConvNets are relatively shallow compared with image ConvNets, which limits its capability of capturing the complex video action information; on the other hand, temporal information of videos is not properly utilized to pool and encode the video sequences. Towards these issues, in this paper, we utilize two state-of-the-art ConvNets, i.e., the very deep spatial net (VGGNet) and the temporal net from Two-Stream ConvNets, for action representation. The convolutional layers and the proposed new layer, called frame-diff layer, are extracted and pooled with two temporal pooling strategy: Trajectory pooling and line pooling. The pooled local descriptors are then encoded with VLAD to form the video representations. In order to verify the effectiveness of the proposed framework, we conduct experiments on UCF101 and HMDB51 datasets. It achieves the accuracy of 93.78\% on UCF101 which is the state-of-the-art and the accuracy of 65.62\% on HMDB51 which is comparable to the state-of-the-art.

##### Abstract (translated by Google)
Deep ConvNets在图像分类任务中表现出色。然而，对于动作识别的深度视频表示仍然是一个问题。问题来自于两方面：一方面，目前的视频通信网络与图像通信网络相比较浅，限制了其捕获复杂的视频动作信息的能力;另一方面，视频的时间信息没有被适当地用于对视频序列进行汇聚和编码。针对这些问题，在本文中，我们利用两个最先进的通信网络，即深度空间网络（VGGNet）和来自双流网络的时间网络来进行行动表示。卷积层和提出的新层，称为帧差异层，提取和汇集了两个时间合并策略：轨迹池和线池。然后用VLAD编码合并的本地描述符以形成视频表示。为了验证所提出框架的有效性，我们对UCF101和HMDB51数据集进行了实验。在UCF101上达到了93.78％的精度，这是目前最先进的技术，HMDB51的精确度达到了65.62％，与当前技术水平相当。

##### URL
[https://arxiv.org/abs/1511.02126](https://arxiv.org/abs/1511.02126)

##### PDF
[https://arxiv.org/pdf/1511.02126](https://arxiv.org/pdf/1511.02126)

