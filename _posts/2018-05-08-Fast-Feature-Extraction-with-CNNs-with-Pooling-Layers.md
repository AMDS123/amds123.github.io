---
layout: post
title: "Fast Feature Extraction with CNNs with Pooling Layers"
date: 2018-05-08 15:14:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection Recognition
author: Christian Bailer, Tewodros Habtegebrial, Kiran varanasi, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, many publications showed that convolutional neural network based features can have a superior performance to engineered features. However, not much effort was taken so far to extract local features efficiently for a whole image. In this paper, we present an approach to compute patch-based local feature descriptors efficiently in presence of pooling and striding layers for whole images at once. Our approach is generic and can be applied to nearly all existing network architectures. This includes networks for all local feature extraction tasks like camera calibration, Patchmatching, optical flow estimation and stereo matching. In addition, our approach can be applied to other patch-based approaches like sliding window object detection and recognition. We complete our paper with a speed benchmark of popular CNN based feature extraction approaches applied on a whole image, with and without our speedup, and example code (for Torch) that shows how an arbitrary CNN architecture can be easily converted by our approach.

##### Abstract (translated by Google)
近年来，许多出版物显示，基于卷积神经网络的特征可以具有优越的工程特征性能。然而，迄今为止没有花费太多精力为整个图像有效地提取局部特征。在本文中，我们提出了一种方法来计算基于补丁的局部特征描述符，以便一次存在整个图像的合并和跨步图层。我们的方法是通用的，可以应用于几乎所有现有的网络体系结构。这包括所有局部特征提取任务的网络，如相机校准，Patchmatching，光流估计和立体匹配。另外，我们的方法可以应用于其他基于补丁的方法，如滑动窗口对象检测和识别。我们用速度基准来完成我们的论文，该速度基准是基于流行的基于CNN的特征提取方法应用于整个图像，无论我们加速还是没有加速，以及示例代码（用于火炬），显示了我们的方法如何轻松转换任意CNN架构。

##### URL
[https://arxiv.org/abs/1805.03096](https://arxiv.org/abs/1805.03096)

##### PDF
[https://arxiv.org/pdf/1805.03096](https://arxiv.org/pdf/1805.03096)

