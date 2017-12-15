---
layout: post
title: "Exploring Context with Deep Structured models for Semantic Segmentation"
date: 2017-05-02 08:06:42
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation Inference Relation
author: Guosheng Lin, Chunhua Shen, Anton van den Hengel, Ian Reid
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art semantic image segmentation methods are mostly based on training deep convolutional neural networks (CNNs). In this work, we proffer to improve semantic segmentation with the use of contextual information. In particular, we explore `patch-patch' context and `patch-background' context in deep CNNs. We formulate deep structured models by combining CNNs and Conditional Random Fields (CRFs) for learning the patch-patch context between image regions. Specifically, we formulate CNN-based pairwise potential functions to capture semantic correlations between neighboring patches. Efficient piecewise training of the proposed deep structured model is then applied in order to avoid repeated expensive CRF inference during the course of back propagation. For capturing the patch-background context, we show that a network design with traditional multi-scale image inputs and sliding pyramid pooling is very effective for improving performance. We perform comprehensive evaluation of the proposed method. We achieve new state-of-the-art performance on a number of challenging semantic segmentation datasets including $NYUDv2$, $PASCAL$-$VOC2012$, $Cityscapes$, $PASCAL$-$Context$, $SUN$-$RGBD$, $SIFT$-$flow$, and $KITTI$ datasets. Particularly, we report an intersection-over-union score of $77.8$ on the $PASCAL$-$VOC2012$ dataset.

##### Abstract (translated by Google)
最先进的语义图像分割方法主要基于训练深度卷积神经网络（CNN）。在这项工作中，我们致力于通过使用上下文信息来改善语义分割。特别是，我们在深度CNN中探索“patch-patch”上下文和“patch-background”上下文。我们通过结合CNN和条件随机场（CRF）来构造深层次的结构化模型，以学习图像区域之间的斑块补丁上下文。具体而言，我们制定了基于CNN的成对潜在函数来捕获相邻小块之间的语义相关性。然后应用所提出的深层结构化模型的有效分段训练，以避免在反向传播过程中反复昂贵的CRF推断。为了捕捉补丁背景的情况，我们表明，具有传统的多尺度图像输入和滑动金字塔池的网络设计对于提高性能非常有效。我们对所提出的方法进行综合评估。我们在许多具有挑战性的语义分割数据集上实现了最新的最新性能，包括$ NYUDv2 $，$ PASCAL $  -  $ VOC2012 $，$ Cityscapes $，$ PASCAL $  -  $ Context $，$ SUN $  -  $ RGBD $，$ SIFT $  -  $ flow $和$ KITTI $ datasets。特别是，我们在$ PASCAL $  -  $ VOC2012 $数据集上报告了77.8 $的交汇分数。

##### URL
[https://arxiv.org/abs/1603.03183](https://arxiv.org/abs/1603.03183)

##### PDF
[https://arxiv.org/pdf/1603.03183](https://arxiv.org/pdf/1603.03183)

