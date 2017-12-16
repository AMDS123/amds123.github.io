---
layout: post
title: "Deep Spatial Regression Model for Image Crowd Counting"
date: 2017-10-26 15:28:41
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Haiyan Yao, Kang Han, Wanggen Wan, Li Hou
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision techniques have been used to produce accurate and generic crowd count estimators in recent years. Due to severe occlusions, appearance variations, perspective distortions and illumination conditions, crowd counting is a very challenging task. To this end, we propose a deep spatial regression model(DSRM) for counting the number of individuals present in a still image with arbitrary perspective and arbitrary resolution. Our proposed model is based on Convolutional Neural Network (CNN) and long short term memory (LSTM). First, we put the images into a pretrained CNN to extract a set of high-level features. Then the features in adjacent regions are used to regress the local counts with a LSTM structure which takes the spatial information into consideration. The final global count is obtained by a sum of the local patches. We apply our framework on several challenging crowd counting datasets, and the experiment results illustrate that our method on the crowd counting and density estimation problem outperforms state-of-the-art methods in terms of reliability and effectiveness.

##### Abstract (translated by Google)
近年来，计算机视觉技术已被用于生产准确和通用的人数估算器。由于严重的遮挡，外观变化，透视失真和光照条件，人群统计是一项非常具有挑战性的任务。为此，我们提出了一个深度空间回归模型（DSRM），用于以任意的视角和任意的分辨率来统计存在于静止图像中的个体的数量。我们提出的模型是基于卷积神经网络（CNN）和长期短期记忆（LSTM）。首先，我们将这些图像放入一个预先训练的CNN中，以提​​取一组高级特征。然后利用相邻区域的特征，以考虑空间信息的LSTM结构来回归局部计数。最终的全局计数是通过本地补丁的总和获得的。我们将这个框架应用于几个具有挑战性的人群统计数据集，实验结果表明我们的人群统计和密度估计方法在可靠性和有效性方面优于最先进的方法。

##### URL
[https://arxiv.org/abs/1710.09757](https://arxiv.org/abs/1710.09757)

##### PDF
[https://arxiv.org/pdf/1710.09757](https://arxiv.org/pdf/1710.09757)

