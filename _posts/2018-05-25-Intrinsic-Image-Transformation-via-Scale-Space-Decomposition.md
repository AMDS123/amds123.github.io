---
layout: post
title: "Intrinsic Image Transformation via Scale Space Decomposition"
date: 2018-05-25 17:11:23
categories: arXiv_CV
tags: arXiv_CV CNN Quantitative
author: Lechao Cheng, Chengyi Zhang, Zicheng Liao
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a new network structure for decomposing an image into its intrinsic albedo and shading. We treat this as an image-to-image transformation problem and explore the scale space of the input and output. By expanding the output images (albedo and shading) into their Laplacian pyramid components, we develop a multi-channel network structure that learns the image-to-image transformation function in successive frequency bands in parallel, within each channel is a fully convolutional neural network with skip connections. This network structure is general and extensible, and has demonstrated excellent performance on the intrinsic image decomposition problem. We evaluate the network on two benchmark datasets: the MPI-Sintel dataset and the MIT Intrinsic Images dataset. Both quantitative and qualitative results show our model delivers a clear progression over state-of-the-art.

##### Abstract (translated by Google)
我们引入了一种新的网络结构，用于将图像分解为其固有的反照率和阴影。我们将其视为一个图像到图像的转换问题，并探讨输入和输出的尺度空间。通过将输出图像（反照率和阴影）扩展到它们的拉普拉斯金字塔分量，我们开发了一个多通道网络结构，可以在并行的连续频带中学习图像到图像的变换函数，每个通道内都是完全卷积神经网络与跳过连接。该网络结构是通用的和可扩展的，并且已经在内在图像分解问题上表现出优异的性能。我们在两个基准数据集上评估网络：MPI-Sintel数据集和MIT Intrinsic Images数据集。定量和定性结果都表明，我们的模型能够在最先进的状态下提供明确的进展。

##### URL
[http://arxiv.org/abs/1805.10253](http://arxiv.org/abs/1805.10253)

##### PDF
[http://arxiv.org/pdf/1805.10253](http://arxiv.org/pdf/1805.10253)

