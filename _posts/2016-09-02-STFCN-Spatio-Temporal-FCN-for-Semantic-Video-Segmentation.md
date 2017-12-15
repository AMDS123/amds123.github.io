---
layout: post
title: "STFCN: Spatio-Temporal FCN for Semantic Video Segmentation"
date: 2016-09-02 15:51:49
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation RNN Prediction
author: Mohsen Fayyaz, Mohammad Hajizadeh Saffar, Mohammad Sabokrou, Mahmood Fathy, Reinhard Klette, Fay Huang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel method to involve both spatial and temporal features for semantic video segmentation. Current work on convolutional neural networks(CNNs) has shown that CNNs provide advanced spatial features supporting a very good performance of solutions for both image and video analysis, especially for the semantic segmentation task. We investigate how involving temporal features also has a good effect on segmenting video data. We propose a module based on a long short-term memory (LSTM) architecture of a recurrent neural network for interpreting the temporal characteristics of video frames over time. Our system takes as input frames of a video and produces a correspondingly-sized output; for segmenting the video our method combines the use of three components: First, the regional spatial features of frames are extracted using a CNN; then, using LSTM the temporal features are added; finally, by deconvolving the spatio-temporal features we produce pixel-wise predictions. Our key insight is to build spatio-temporal convolutional networks (spatio-temporal CNNs) that have an end-to-end architecture for semantic video segmentation. We adapted fully some known convolutional network architectures (such as FCN-AlexNet and FCN-VGG16), and dilated convolution into our spatio-temporal CNNs. Our spatio-temporal CNNs achieve state-of-the-art semantic segmentation, as demonstrated for the Camvid and NYUDv2 datasets.

##### Abstract (translated by Google)
本文提出了一种涉及语义视频分割的空间和时间特征的新方法。目前卷积神经网络（CNNs）的研究表明，CNN提供了先进的空间特征，为图像和视频分析提供了非常好的解决方案，特别是语义分割任务。我们调查如何涉及时间特征也对分段视频数据有很好的影响。我们提出了一个基于长期短期记忆（LSTM）架构的循环神经网络模块来解释视频帧的时间特性随着时间的推移。我们的系统作为一个视频的输入帧，并产生一个相应的大小输出;为了分割视频，我们的方法结合使用三个组件：首先，使用CNN提取帧的区域空间特征;然后，使用LSTM添加时间特征;最后，通过对时空特征进行去卷积，我们产生了像素级的预测。我们的主要观点是建立具有用于语义视频分割的端到端体系结构的时空卷积网络（时空CNN）。我们充分调整了一些已知的卷积网络架构（如FCN-AlexNet和FCN-VGG16），并将卷积扩展到我们的时空CNN中。我们的时空CNN实现了最先进的语义分割，如Camvid和NYUDv2数据集所示。

##### URL
[https://arxiv.org/abs/1608.05971](https://arxiv.org/abs/1608.05971)

##### PDF
[https://arxiv.org/pdf/1608.05971](https://arxiv.org/pdf/1608.05971)

