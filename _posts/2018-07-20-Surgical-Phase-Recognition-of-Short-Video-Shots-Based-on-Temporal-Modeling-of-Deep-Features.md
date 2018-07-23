---
layout: post
title: "Surgical Phase Recognition of Short Video Shots Based on Temporal Modeling of Deep Features"
date: 2018-07-20 14:10:32
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation CNN Transfer_Learning RNN Classification Recognition
author: Constantinos Loukas
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing the phases of a laparoscopic surgery (LS) operation form its video constitutes a fundamental step for efficient content representation, indexing and retrieval in surgical video databases. In the literature, most techniques focus on phase segmentation of the entire LS video using hand-crafted visual features, instrument usage signals, and recently convolutional neural networks (CNNs). In this paper we address the problem of phase recognition of short video shots (10s) of the operation, without utilizing information about the preceding/forthcoming video frames, their phase labels or the instruments used. We investigate four state-of-the-art CNN architectures (Alexnet, VGG19, GoogleNet, and ResNet101), for feature extraction via transfer learning. Visual saliency was employed for selecting the most informative region of the image as input to the CNN. Video shot representation was based on two temporal pooling mechanisms. Most importantly, we investigate the role of 'elapsed time' (from the beginning of the operation), and we show that inclusion of this feature can increase performance dramatically (69% vs. 75% mean accuracy). Finally, a long short-term memory (LSTM) network was trained for video shot classification based on the fusion of CNN features with 'elapsed time', increasing the accuracy to 86%. Our results highlight the prominent role of visual saliency, long-range temporal recursion and 'elapsed time' (a feature so far ignored), for surgical phase recognition.

##### Abstract (translated by Google)
认识到腹腔镜手术（LS）手术的各个阶段，其视频构成了外科视频数据库中有效内容表示，索引和检索的基本步骤。在文献中，大多数技术使用手工制作的视觉特征，仪器使用信号和最近的卷积神经网络（CNN）来关注整个LS视频的相位分割。在本文中，我们解决了操作的短视频镜头（10s）的相位识别问题，而没有利用关于前/后视频帧，其相位标签或所使用的仪器的信息。我们研究了四种最先进的CNN架构（Alexnet，VGG19，GoogleNet和ResNet101），用于通过传输学习进行特征提取。采用视觉显着性来选择图像的最具信息性的区域作为CNN的输入。视频镜头表示基于两种时间池机制。最重要的是，我们调查“经过时间”的角色（从操作开始），我们表明包含此功能可以显着提高性能（69％对75％的平均准确度）。最后，基于CNN特征与“经过时间”的融合，对长期短期记忆（LSTM）网络进行了视频镜头分类训练，将准确度提高到86％。我们的结果突出了视觉显着性，远程时间递归和“经过时间”（迄今为止忽略的一个特征）的突出作用，用于手术相识别。

##### URL
[http://arxiv.org/abs/1807.07853](http://arxiv.org/abs/1807.07853)

##### PDF
[http://arxiv.org/pdf/1807.07853](http://arxiv.org/pdf/1807.07853)

