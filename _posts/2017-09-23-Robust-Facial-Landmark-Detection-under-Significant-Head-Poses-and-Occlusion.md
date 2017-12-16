---
layout: post
title: "Robust Facial Landmark Detection under Significant Head Poses and Occlusion"
date: 2017-09-23 23:34:53
categories: arXiv_CV
tags: arXiv_CV Face Prediction Detection
author: Yue Wu, Qiang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
There have been tremendous improvements for facial landmark detection on general "in-the-wild" images. However, it is still challenging to detect the facial landmarks on images with severe occlusion and images with large head poses (e.g. profile face). In fact, the existing algorithms usually can only handle one of them. In this work, we propose a unified robust cascade regression framework that can handle both images with severe occlusion and images with large head poses. Specifically, the method iteratively predicts the landmark occlusions and the landmark locations. For occlusion estimation, instead of directly predicting the binary occlusion vectors, we introduce a supervised regression method that gradually updates the landmark visibility probabilities in each iteration to achieve robustness. In addition, we explicitly add occlusion pattern as a constraint to improve the performance of occlusion prediction. For landmark detection, we combine the landmark visibility probabilities, the local appearances, and the local shapes to iteratively update their positions. The experimental results show that the proposed method is significantly better than state-of-the-art works on images with severe occlusion and images with large head poses. It is also comparable to other methods on general "in-the-wild" images.

##### Abstract (translated by Google)
一般“野外”图像中的面部标志检测已经有了巨大的改进。然而，在严重遮挡的图像和具有大的头部姿势的图像（例如，轮廓面）上检测面部标志仍然是具有挑战性的。实际上，现有的算法通常只能处理其中的一个。在这项工作中，我们提出了一个统一的强大的级联回归框架，可以处理严重遮挡的图像和大头部姿势的图像。具体来说，该方法迭代地预测地标遮挡和地标位置。为了进行遮挡估计，我们不是直接预测二值遮挡矢量，而是引入一个监督回归方法，逐渐更新每次迭代中的界标可见性概率以实现鲁棒性。此外，我们明确添加遮挡模式作为约束来提高遮挡预测的性能。对于标志性检测，我们结合标志性可见性概率，局部外观和局部形状来迭代更新其位置。实验结果表明，该方法明显优于严重遮挡的图像和具有较大头部姿势的图像。它也可以与一般的“野外”图像的其他方法相媲美。

##### URL
[https://arxiv.org/abs/1709.08127](https://arxiv.org/abs/1709.08127)

##### PDF
[https://arxiv.org/pdf/1709.08127](https://arxiv.org/pdf/1709.08127)

