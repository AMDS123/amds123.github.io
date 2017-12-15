---
layout: post
title: "Deep Image Homography Estimation"
date: 2016-06-13 02:46:38
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning Detection
author: Daniel DeTone, Tomasz Malisiewicz, Andrew Rabinovich
mathjax: true
---

* content
{:toc}

##### Abstract
We present a deep convolutional neural network for estimating the relative homography between a pair of images. Our feed-forward network has 10 layers, takes two stacked grayscale images as input, and produces an 8 degree of freedom homography which can be used to map the pixels from the first image to the second. We present two convolutional neural network architectures for HomographyNet: a regression network which directly estimates the real-valued homography parameters, and a classification network which produces a distribution over quantized homographies. We use a 4-point homography parameterization which maps the four corners from one image into the second image. Our networks are trained in an end-to-end fashion using warped MS-COCO images. Our approach works without the need for separate local feature detection and transformation estimation stages. Our deep models are compared to a traditional homography estimator based on ORB features and we highlight the scenarios where HomographyNet outperforms the traditional technique. We also describe a variety of applications powered by deep homography estimation, thus showcasing the flexibility of a deep learning approach.

##### Abstract (translated by Google)
我们提出了一个深卷积神经网络来估计一对图像之间的相对单应性。我们的前馈网络有10层，将两个堆叠的灰度图像作为输入，并产生8个自由度单应矩阵，可用于将像素从第一图像映射到第二图像。我们提出了HomographyNet的两个卷积神经网络架构：直接估计实值单应性参数的回归网络和产生量化单应性分布的分类网络。我们使用4点单应性参数化，将四个角从一个图像映射到第二个图像。我们的网络使用扭曲的MS-COCO图像以端到端的方式进行训练。我们的方法不需要单独的局部特征检测和变换估计阶段。我们的深层模型与基于ORB特征的传统单应性估计器相比较，并强调了HomographyNet胜过传统技术的场景。我们还描述了深度单应估算的各种应用，从而展现了深度学习方法的灵活性。

##### URL
[https://arxiv.org/abs/1606.03798](https://arxiv.org/abs/1606.03798)

##### PDF
[https://arxiv.org/pdf/1606.03798](https://arxiv.org/pdf/1606.03798)

