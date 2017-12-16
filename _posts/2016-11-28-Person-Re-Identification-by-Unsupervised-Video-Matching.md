---
layout: post
title: "Person Re-Identification by Unsupervised Video Matching"
date: 2016-11-28 09:20:29
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Xiaolong Ma, Xiatian Zhu, Shaogang Gong, Xudong Xie, Jianming Hu, Kin-Man Lam, Yisheng Zhong
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing person re-identification (ReID) methods rely only on the spatial appearance information from either one or multiple person images, whilst ignore the space-time cues readily available in video or image-sequence data. Moreover, they often assume the availability of exhaustively labelled cross-view pairwise data for every camera pair, making them non-scalable to ReID applications in real-world large scale camera networks. In this work, we introduce a novel video based person ReID method capable of accurately matching people across views from arbitrary unaligned image-sequences without any labelled pairwise data. Specifically, we introduce a new space-time person representation by encoding multiple granularities of spatio-temporal dynamics in form of time series. Moreover, a Time Shift Dynamic Time Warping (TS-DTW) model is derived for performing automatically alignment whilst achieving data selection and matching between inherently inaccurate and incomplete sequences in a unified way. We further extend the TS-DTW model for accommodating multiple feature-sequences of an image-sequence in order to fuse information from different descriptions. Crucially, this model does not require pairwise labelled training data (i.e. unsupervised) therefore readily scalable to large scale camera networks of arbitrary camera pairs without the need for exhaustive data annotation for every camera pair. We show the effectiveness and advantages of the proposed method by extensive comparisons with related state-of-the-art approaches using two benchmarking ReID datasets, PRID2011 and iLIDS-VID.

##### Abstract (translated by Google)
大多数现有的人重新识别（ReID）方法仅依赖于来自一个或多个人图像的空间外观信息，而忽略视频或图像序列数据中易于获得的时空提示。此外，他们经常假定每个摄像机对都有详尽标记的交叉视图成对数据，使得它们不可扩展到真实世界大型摄像机网络中的ReID应用。在这项工作中，我们引入了一种新颖的基于视频的人ReID方法，能够从任意未对齐的图像序列中精确地匹配人物，而不需要任何标记的成对数据。具体而言，我们通过时间序列的形式编码多个粒度的时空动态，从而引入一个新的时空人的表征。此外，推导了一种时移动态时间规整（TS-DTW）模型，用于实现自动对齐，同时以统一的方式实现固有不准确和不完整序列之间的数据选择和匹配。我们进一步扩展TS-DTW模型以适应图像序列的多个特征序列以融合来自不同描述的信息。重要的是，该模型不需要成对标记的训练数据（即，无监督的），因此可以容易地扩展到任意摄像机对的大规模摄像机网络，而不需要每个摄像机对的详尽的数据注释。我们通过使用两个基准的ReID数据集，PRID2011和iLIDS-VID，与相关的最先进的方法进行广泛比较来展示所提出的方法的有效性和优点。

##### URL
[https://arxiv.org/abs/1611.08512](https://arxiv.org/abs/1611.08512)

##### PDF
[https://arxiv.org/pdf/1611.08512](https://arxiv.org/pdf/1611.08512)

