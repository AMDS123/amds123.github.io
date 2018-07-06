---
layout: post
title: "Perspective-Aware CNN For Crowd Counting"
date: 2018-07-05 13:33:28
categories: arXiv_CV
tags: arXiv_CV CNN
author: Miaojing Shi, Zhaohui Yang, Chao Xu, Qijun Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Crowd counting is the task of estimating pedestrian numbers in crowd images. Modern crowd counting methods employ deep neural networks to estimate crowd counts via crowd density regressions. A major challenge of this task lies in the drastic changes of scales and perspectives in images. Representative approaches usually utilize different (large) sized filters and conduct patch-based estimations to tackle it, which is however computationally expensive. In this paper, we propose a perspective-aware convolutional neural network (PACNN) with a single backbone of small filters (e.g. 3x3). It directly predicts a perspective map in the network and encodes it as a perspective-aware weighting layer to adaptively combine the density outputs from multi-scale feature maps. The weights are learned at every pixel of the map such that the final combination is robust to perspective changes and pedestrian size variations. We conduct extensive experiments on the ShanghaiTech, WorldExpo'10 and UCF_CC_50 datasets, and demonstrate that PACNN achieves state-of-the-art results and runs as fast as the fastest.

##### Abstract (translated by Google)
人群计数是估算人群图像中行人数量的任务。现代人群计数方法采用深度神经网络通过人群密度回归来估计人群数量。这项任务的一个主要挑战在于图像尺度和视角的急剧变化。代表性方法通常利用不同（大）尺寸的滤波器并进行基于补丁的估计来解决它，但是这在计算上是昂贵的。在本文中，我们提出了一种具有单个小滤波器主干（例如3×3）的透视感知卷积神经网络（PACNN）。它直接预测网络中的透视图，并将其编码为透视感知加权层，以自适应地组合来自多尺度特征图的密度输出。在地图的每个像素处学习权重，使得最终组合对于透视变化和行人尺寸变化是稳健的。我们对ShanghaiTech，WorldExpo'10和UCF_CC_50数据集进行了大量实验，并证明PACNN可以实现最先进的结果，并以最快的速度运行。

##### URL
[http://arxiv.org/abs/1807.01989](http://arxiv.org/abs/1807.01989)

##### PDF
[http://arxiv.org/pdf/1807.01989](http://arxiv.org/pdf/1807.01989)

