---
layout: post
title: "Dynamic texture and scene classification by transferring deep image features"
date: 2015-02-01 20:22:00
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Image_Classification Classification
author: Xianbiao Qi, Chun-Guang Li, Guoying Zhao, Xiaopeng Hong, Matti Pietikäinen
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic texture and scene classification are two fundamental problems in understanding natural video content. Extracting robust and effective features is a crucial step towards solving these problems. However the existing approaches suffer from the sensitivity to either varying illumination, or viewpoint changing, or even camera motion, and/or the lack of spatial information. Inspired by the success of deep structures in image classification, we attempt to leverage a deep structure to extract feature for dynamic texture and scene classification. To tackle with the challenges in training a deep structure, we propose to transfer some prior knowledge from image domain to video domain. To be specific, we propose to apply a well-trained Convolutional Neural Network (ConvNet) as a mid-level feature extractor to extract features from each frame, and then form a representation of a video by concatenating the first and the second order statistics over the mid-level features. We term this two-level feature extraction scheme as a Transferred ConvNet Feature (TCoF). Moreover we explore two different implementations of the TCoF scheme, i.e., the \textit{spatial} TCoF and the \textit{temporal} TCoF, in which the mean-removed frames and the difference between two adjacent frames are used as the inputs of the ConvNet, respectively. We evaluate systematically the proposed spatial TCoF and the temporal TCoF schemes on three benchmark data sets, including DynTex, YUPENN, and Maryland, and demonstrate that the proposed approach yields superior performance.

##### Abstract (translated by Google)
动态纹理和场景分类是理解自然视频内容的两个基本问题。提取强大而有效的功能是解决这些问题的关键一步。然而，现有的方法受到对变化的照明或视点变化甚至相机移动的敏感性和/或缺乏空间信息。受到图像分类中深层结构成功的启发，我们试图利用深层结构来提取动态纹理和场景分类的特征。为了解决训练深层结构中的挑战，我们提出将一些先验知识从图像域转移到视频域。具体来说，我们建议应用一个训练有素的卷积神经网络（ConvNet）作为一个中等水平的特征提取器来从每一帧中提取特征，然后通过连接一阶和二阶统计数据来形成一个视频的表示中级功能。我们将这个两层特征提取方案称为传输ConvNet特征（TCoF）。此外，我们探索了TCoF方案的两种不同的实现方式，即\ textit {spatial} TCoF和\ textit {temporal} TCoF，其中平均去除帧和两个相邻帧之间的差值被用作ConvNet分别。我们系统地评估了三个基准数据集（包括DynTex，YUPENN和马里兰州）提出的空间TCoF和时间TCoF方案，并且证明了所提出的方法产生优越的性能。

##### URL
[https://arxiv.org/abs/1502.00303](https://arxiv.org/abs/1502.00303)

##### PDF
[https://arxiv.org/pdf/1502.00303](https://arxiv.org/pdf/1502.00303)

