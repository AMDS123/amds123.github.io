---
layout: post
title: "Single Image Super-Resolution based on Wiener Filter in Similarity Domain"
date: 2017-11-29 14:08:09
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Cristóvão Cruz, Rakesh Mehta, Vladimir Katkovnik, Karen Egiazarian
mathjax: true
---

* content
{:toc}

##### Abstract
Single image super resolution (SISR) is an ill-posed problem aiming at estimating a plausible high resolution (HR) image from a single low resolution (LR) image. Current state-of-the-art SISR methods are patch-based. They use either external data or internal self-similarity to learn a prior for a HR image. External data based methods utilize large number of patches from the training data, while self-similarity based approaches leverage one or more similar patches from the input image. In this paper we propose a self-similarity based approach that is able to use large groups of similar patches extracted from the input image to solve the SISR problem. We introduce a novel prior leading to collaborative filtering of patch groups in 1D similarity domain and couple it with an iterative back-projection framework. The performance of the proposed algorithm is evaluated on a number of SISR benchmark datasets. Without using any external data, the proposed approach outperforms the current non-CNN based methods on the tested datasets for various scaling factors. On certain datasets, the gain is over 1 dB, when compared to the recent method A+. For high sampling rate (x4) the proposed method performs similarly to very recent state-of-the-art deep convolutional network based approaches.

##### Abstract (translated by Google)
单幅图像超分辨率（SISR）是一个不适合的问题，旨在从单个低分辨率（LR）图像估计合理的高分辨率（HR）图像。目前的最先进的SISR方法是基于补丁的。他们使用外部数据或内部自相似性来学习HR图像的先验知识。基于外部数据的方法利用来自训练数据的大量补丁，而基于自相似性的方法利用来自输入图像的一个或多个类似补丁。在本文中，我们提出了一种基于自相似性的方法，它能够使用从输入图像中提取的大量类似的块来解决SISR问题。我们引入了一种新颖的先验技术，导致了一维相似域中的贴片组的协同过滤，并将其与迭代反投影框架耦合。所提出的算法的性能在许多SISR基准数据集上进行评估。在不使用任何外部数据的情况下，针对各种缩放因子，所提出的方法优于目前基于非CNN的测试数据集上的方法。在某些数据集上，与最近的方法A +相比，增益超过1 dB。对于高采样率（x4），所提出的方法执行类似于最新的现有技术的基于深度卷积网络的方法。

##### URL
[https://arxiv.org/abs/1704.04126](https://arxiv.org/abs/1704.04126)

##### PDF
[https://arxiv.org/pdf/1704.04126](https://arxiv.org/pdf/1704.04126)

