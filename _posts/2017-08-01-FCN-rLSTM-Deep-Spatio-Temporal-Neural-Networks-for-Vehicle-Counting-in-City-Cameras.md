---
layout: post
title: "FCN-rLSTM: Deep Spatio-Temporal Neural Networks for Vehicle Counting in City Cameras"
date: 2017-08-01 00:33:29
categories: arXiv_CV
tags: arXiv_CV CNN RNN Prediction Memory_Networks
author: Shanghang Zhang, Guanhang Wu, João P. Costeira, José M. F. Moura
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we develop deep spatio-temporal neural networks to sequentially count vehicles from low quality videos captured by city cameras (citycams). Citycam videos have low resolution, low frame rate, high occlusion and large perspective, making most existing methods lose their efficacy. To overcome limitations of existing methods and incorporate the temporal information of traffic video, we design a novel FCN-rLSTM network to jointly estimate vehicle density and vehicle count by connecting fully convolutional neural networks (FCN) with long short term memory networks (LSTM) in a residual learning fashion. Such design leverages the strengths of FCN for pixel-level prediction and the strengths of LSTM for learning complex temporal dynamics. The residual learning connection reformulates the vehicle count regression as learning residual functions with reference to the sum of densities in each frame, which significantly accelerates the training of networks. To preserve feature map resolution, we propose a Hyper-Atrous combination to integrate atrous convolution in FCN and combine feature maps of different convolution layers. FCN-rLSTM enables refined feature representation and a novel end-to-end trainable mapping from pixels to vehicle count. We extensively evaluated the proposed method on different counting tasks with three datasets, with experimental results demonstrating their effectiveness and robustness. In particular, FCN-rLSTM reduces the mean absolute error (MAE) from 5.31 to 4.21 on TRANCOS, and reduces the MAE from 2.74 to 1.53 on WebCamT. Training process is accelerated by 5 times on average.

##### Abstract (translated by Google)
在本文中，我们开发深层时空神经网络来依次计算城市摄像机（城市摄像机）拍摄的低质量视频中的车辆。城市摄像机的视频分辨率低，帧率低，遮挡度高，视角大，使得大多数现有的方法失去效用。为了克服现有方法的局限性，并结合交通视频的时间信息，我们设计了一种新的FCN-rLSTM网络，通过将完全卷积神经网络（FCN）与长期短期记忆网络（LSTM）连接在一起来联合估计车辆密度和车辆数量一个剩余的学习时尚。这样的设计利用了FCN在像素级预测和LSTM学习复杂时间动态的优势。剩余的学习联系将车辆计数回归重新形成为参考每个帧的密度总和的学习残差函数，这显着地加速了网络的训练。为了保留特征映射的分辨率，我们提出了一种Hyper-Atrous的组合方式来融合FCN中的非均匀卷积，并结合不同卷积层的特征映射。 FCN-rLSTM支持精确的特征表示和从像素到车辆数量的新颖的端到端可训练映射。我们对三种数据集的不同计数任务进行了广泛的评估，实验结果证明了它们的有效性和鲁棒性。特别地，FCN-rLSTM将TRANCOS上的平均绝对误差（MAE）从5.31降低到4.21，并且在WebCamT上将MAE从2.74降低到1.53。培训过程平均加速5次。

##### URL
[https://arxiv.org/abs/1707.09476](https://arxiv.org/abs/1707.09476)

##### PDF
[https://arxiv.org/pdf/1707.09476](https://arxiv.org/pdf/1707.09476)

