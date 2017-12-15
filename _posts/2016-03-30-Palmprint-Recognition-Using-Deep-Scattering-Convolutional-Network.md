---
layout: post
title: "Palmprint Recognition Using Deep Scattering Convolutional Network"
date: 2016-03-30 03:09:15
categories: arXiv_CV
tags: arXiv_CV Image_Caption Attention CNN Recognition
author: Shervin Minaee, Yao Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Palmprint recognition has drawn a lot of attention during the recent years. Many algorithms have been proposed for palmprint recognition in the past, majority of them being based on features extracted from the transform domain. Many of these transform domain features are not translation or rotation invariant, and therefore a great deal of preprocessing is needed to align the images. In this paper, a powerful image representation, called scattering network/transform, is used for palmprint recognition. Scattering network is a convolutional network where its architecture and filters are predefined wavelet transforms. The first layer of scattering network captures similar features to SIFT descriptors and the higher-layer features capture higher-frequency content of the signal which are lost in SIFT and other similar descriptors. After extraction of the scattering features, their dimensionality is reduced by applying principal component analysis (PCA) which reduces the computational complexity of the recognition task. Two different classifiers are used for recognition: multi-class SVM and minimum-distance classifier. The proposed scheme has been tested on a well-known palmprint database and achieved accuracy rate of 99.95% and 100% using minimum distance classifier and SVM respectively.

##### Abstract (translated by Google)
掌纹识别近年来备受关注。过去已经提出了许多用于掌纹识别的算法，其中大部分算法是基于从变换域提取的特征。许多这些变换域特征不是平移或旋转不变的，因此需要大量的预处理来对齐图像。在本文中，一个强大的图像表示，称为散射网络/变换，用于掌纹识别。散射网络是一种卷积网络，其结构和滤波器是预定义的小波变换。散射网络的第一层捕获与SIFT描述符类似的特征，并且较高层特征捕获在SIFT和其他类似描述符中丢失的信号的较高频率内容。在提取散射特征之后，通过应用主成分分析（PCA）来降低其维度，这降低了识别任务的计算复杂度。两种不同的分类器用于识别：多类SVM和最小距离分类器。该方案在已知的掌纹数据库上进行了测试，分别使用最小距离分类器和支持向量机分别实现了99.95％和100％的准确率。

##### URL
[https://arxiv.org/abs/1603.09027](https://arxiv.org/abs/1603.09027)

##### PDF
[https://arxiv.org/pdf/1603.09027](https://arxiv.org/pdf/1603.09027)

