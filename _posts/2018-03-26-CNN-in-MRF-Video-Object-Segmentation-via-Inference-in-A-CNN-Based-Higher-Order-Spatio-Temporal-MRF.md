---
layout: post
title: "CNN in MRF: Video Object Segmentation via Inference in A CNN-Based Higher-Order Spatio-Temporal MRF"
date: 2018-03-26 07:56:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Inference Detection
author: Linchao Bao, Baoyuan Wu, Wei Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of video object segmentation, where the initial object mask is given in the first frame of an input video. We propose a novel spatio-temporal Markov Random Field (MRF) model defined over pixels to handle this problem. Unlike conventional MRF models, the spatial dependencies among pixels in our model are encoded by a Convolutional Neural Network (CNN). Specifically, for a given object, the probability of a labeling to a set of spatially neighboring pixels can be predicted by a CNN trained for this specific object. As a result, higher-order, richer dependencies among pixels in the set can be implicitly modeled by the CNN. With temporal dependencies established by optical flow, the resulting MRF model combines both spatial and temporal cues for tackling video object segmentation. However, performing inference in the MRF model is very difficult due to the very high-order dependencies. To this end, we propose a novel CNN-embedded algorithm to perform approximate inference in the MRF. This algorithm proceeds by alternating between a temporal fusion step and a feed-forward CNN step. When initialized with an appearance-based one-shot segmentation CNN, our model outperforms the winning entries of the DAVIS 2017 Challenge, without resorting to model ensembling or any dedicated detectors.

##### Abstract (translated by Google)
本文讨论了视频对象分割的问题，其中在输入视频的第一帧中给出了初始对象遮罩。我们提出了一个新的时空马尔可夫随机场（MRF）模型定义在像素来处理这个问题。与传统的MRF模型不同，我们模型中像素之间的空间相关性由卷积神经网络（CNN）编码。具体而言，对于给定的对象，可以通过针对该特定对象训练的CNN来预测对一组空间相邻像素进行标记的概率。因此，集合中像素之间的更高阶的更丰富的依赖性可以由CNN隐式建模。通过光流建立的时间依赖性，所得到的MRF模型结合了用于解决视频对象分割的空间和时间线索。然而，由于非常高阶的依赖关系，在MRF模型中执行推理非常困难。为此，我们提出了一种新颖的CNN嵌入算法来执行MRF中的近似推理。该算法通过在时间融合步骤和前馈CNN步骤之间交替进行。当使用基于外观的一次分割CNN进行初始化时，我们的模型胜过DAVIS 2017挑战赛的获奖作品，而无需借助模型集成或任何专用检测器。

##### URL
[https://arxiv.org/abs/1803.09453](https://arxiv.org/abs/1803.09453)

##### PDF
[https://arxiv.org/pdf/1803.09453](https://arxiv.org/pdf/1803.09453)

