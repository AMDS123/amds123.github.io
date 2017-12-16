---
layout: post
title: "A Correlation Based Feature Representation for First-Person Activity Recognition"
date: 2017-11-15 12:26:42
categories: arXiv_CV
tags: arXiv_CV CNN Relation Recognition
author: Reza Kahani, Alireza Talebpour, Ahmad Mahmoudi-Aznaveh
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, a simple yet efficient feature encoding for first-person video is introduced. The proposed method is appropriate for representation of high-dimensional features such as those extracted from convolutional neural networks (CNNs). The per-frame extracted features are considered as a set of time series, and inter and intra-time series relations are employed to represent the video descriptors. To find the inter-time relations, the series are grouped and the linear correlation between each pair of groups is calculated. The relations between them can represent the scene dynamics and local motions. The introduced grouping strategy helps to considerably reduce the computational cost. Furthermore, we split the series in temporal direction in order to better focus on each local time window. In order to extract the cyclic motion patterns, which can be considered as primary components of various activities, intra-time series correlations are exploited. The representation method results in highly discriminative features which can be simply classified by a linear SVM. The experiments show that our method outperforms the previous encoding methods, such as bag of visual word (BoVW), improved Fisher vector (IFV), Fourier temporal pyramid (FTP), and recently proposed pooled time series (PoT) on three public first-person datasets. The experimental results also confirm that the proposed method has a superior performance over the state-of-the-art methods on recognizing first-person activities

##### Abstract (translated by Google)
在本文中，介绍了一个简单而高效的第一人称视频编码功能。所提出的方法适合于表示高维特征，例如从卷积神经网络（CNN）提取的特征。将每帧提取的特征视为一组时间序列，并采用帧间和时间内的序列关系来表示视频描述符。为了找到时间间隔关系，将序列分组并且计算每对组之间的线性相关性。它们之间的关系可以代表现场动态和局部运动。引入的分组策略有助于大大降低计算成本。此外，我们在时间方向上分割序列，以便更好地关注每个本地时间窗口。为了提取可以被认为是各种活动的主要组成部分的循环运动模式，开发了时间序列相关性。该表示方法产生高度区分的特征，可以通过线性SVM简单地分类。实验结果表明，本文提出的方法优于以往的编码方法，如视频词袋（BoVW），改进的Fisher矢量（IFV），傅立叶时间金字塔（FTP）和最近提出的三种公开一阶时间序列（PoT）个人数据集。实验结果也证实，所提出的方法具有优于最先进的识别第一人称活动的方法的性能

##### URL
[https://arxiv.org/abs/1711.05523](https://arxiv.org/abs/1711.05523)

##### PDF
[https://arxiv.org/pdf/1711.05523](https://arxiv.org/pdf/1711.05523)

