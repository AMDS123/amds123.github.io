---
layout: post
title: "Learning Feature Pyramids for Human Pose Estimation"
date: 2017-08-03 11:26:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference
author: Wei Yang, Shuang Li, Wanli Ouyang, Hongsheng Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Articulated human pose estimation is a fundamental yet challenging task in computer vision. The difficulty is particularly pronounced in scale variations of human body parts when camera view changes or severe foreshortening happens. Although pyramid methods are widely used to handle scale changes at inference time, learning feature pyramids in deep convolutional neural networks (DCNNs) is still not well explored. In this work, we design a Pyramid Residual Module (PRMs) to enhance the invariance in scales of DCNNs. Given input features, the PRMs learn convolutional filters on various scales of input features, which are obtained with different subsampling ratios in a multi-branch network. Moreover, we observe that it is inappropriate to adopt existing methods to initialize the weights of multi-branch networks, which achieve superior performance than plain networks in many tasks recently. Therefore, we provide theoretic derivation to extend the current weight initialization scheme to multi-branch network structures. We investigate our method on two standard benchmarks for human pose estimation. Our approach obtains state-of-the-art results on both benchmarks. Code is available at this https URL

##### Abstract (translated by Google)
铰接的人体姿势估计是计算机视觉中的一个基本而又具有挑战性的任务。当摄像机视图改变或发生严重缩短时，难度在人体部位的尺度变化中特别显着。虽然金字塔方法被广泛用于处理尺度变化的推理时间，深度卷积神经网络（DCNNs）学习特征金字塔还没有很好的探索。在这项工作中，我们设计了一个金字塔残差模块（PRMs）来增强DCNN的尺度的不变性。给定输入特征，PRM学习多尺度输入特征的卷积滤波器，这是在多分支网络中利用不同子采样率获得的。此外，我们观察到采用现有的方法来初始化多分支网络的权重是不恰当的，这些分支网络在最近的许多任务中比普通网络性能更优。因此，本文提出了将当前权重初始化方案扩展到多分支网络结构的理论推导。我们调查我们的方法在两个人类姿势估计的标准基准。我们的方法在两个基准上都获得了最新的结果。代码可在此https网址获得

##### URL
[https://arxiv.org/abs/1708.01101](https://arxiv.org/abs/1708.01101)

##### PDF
[https://arxiv.org/pdf/1708.01101](https://arxiv.org/pdf/1708.01101)

