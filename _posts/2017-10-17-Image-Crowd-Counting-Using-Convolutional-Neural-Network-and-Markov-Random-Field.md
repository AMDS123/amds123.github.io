---
layout: post
title: "Image Crowd Counting Using Convolutional Neural Network and Markov Random Field"
date: 2017-10-17 02:24:34
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Kang Han, Wanggen Wan, Haiyan Yao, Li Hou
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method called Convolutional Neural Network-Markov Random Field (CNN-MRF) to estimate the crowd count in a still image. We first divide the dense crowd visible image into overlapping patches and then use a deep convolutional neural network to extract features from each patch image, followed by a fully connected neural network to regress the local patch crowd count. Since the local patches have overlapping portions, the crowd count of the adjacent patches has a high correlation. We use this correlation and the Markov random field to smooth the counting results of the local patches. Experiments show that our approach significantly outperforms the state-of-the-art methods on UCF and Shanghaitech crowd counting datasets.

##### Abstract (translated by Google)
在本文中，我们提出了一种称为卷积神经网络马尔可夫随机场（CNN-MRF）的方法来估计静止图像中的人数。我们首先将稠密人群的可见光图像划分为重叠斑块，然后使用深度卷积神经网络从每个斑块图像中提取特征，然后使用完全连接的神经网络来回归局部斑块群。由于局部斑块具有重叠部分，所以相邻斑块的人数相关性高。我们使用这个相关性和马尔可夫随机场平滑本地补丁的计数结果。实验表明，我们的方法明显优于UCF和Shanghaitech人群计数数据集上的最新方法。

##### URL
[https://arxiv.org/abs/1706.03686](https://arxiv.org/abs/1706.03686)

##### PDF
[https://arxiv.org/pdf/1706.03686](https://arxiv.org/pdf/1706.03686)

