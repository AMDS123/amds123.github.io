---
layout: post
title: "Disentangling Motion, Foreground and Background Features in Videos"
date: 2017-07-17 13:50:01
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Xunyu Lin, Victor Campos, Xavier Giro-i-Nieto, Jordi Torres, Cristian Canton Ferrer
mathjax: true
---

* content
{:toc}

##### Abstract
This paper introduces an unsupervised framework to extract semantically rich features for video representation. Inspired by how the human visual system groups objects based on motion cues, we propose a deep convolutional neural network that disentangles motion, foreground and background information. The proposed architecture consists of a 3D convolutional feature encoder for blocks of 16 frames, which is trained for reconstruction tasks over the first and last frames of the sequence. A preliminary supervised experiment was conducted to verify the feasibility of proposed method by training the model with a fraction of videos from the UCF-101 dataset taking as ground truth the bounding boxes around the activity regions. Qualitative results indicate that the network can successfully segment foreground and background in videos as well as update the foreground appearance based on disentangled motion features. The benefits of these learned features are shown in a discriminative classification task, where initializing the network with the proposed pretraining method outperforms both random initialization and autoencoder pretraining. Our model and source code are publicly available at this https URL .

##### Abstract (translated by Google)
本文介绍了一个无监督的框架来提取语义丰富的视频表示功能。受人类视觉系统如何根据运动线索对物体进行分组的启发，我们提出了一个深层卷积神经网络来解开运动，前景和背景信息。所提出的体系结构由用于16帧的块的三维卷积特征编码器组成，其被训练用于序列的第一帧和最后一帧的重构任务。通过对UCF-101数据集中一小部分视频的模型进行训练，作为地面实况，对活动区域周围的边界框进行初步监督实验，验证所提方法的可行性。定性结果表明，网络可以成功地在视频中分割前景和背景，并且根据解开的运动特征来更新前景外观。这些学习功能的好处显示在一个有区别的分类任务，初始化网络与提出的预训练方法胜过随机初始化和自动编码器预训练。我们的模型和源代码可在此https URL上公开获得。

##### URL
[https://arxiv.org/abs/1707.04092](https://arxiv.org/abs/1707.04092)

##### PDF
[https://arxiv.org/pdf/1707.04092](https://arxiv.org/pdf/1707.04092)

