---
layout: post
title: "MVDepthNet: Real-time Multiview Depth Estimation Neural Network"
date: 2018-07-23 12:37:13
categories: arXiv_CV
tags: arXiv_CV CNN
author: Kaixuan Wang, Shaojie Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Although deep neural networks have been widely applied to computer vision problems, extending them into multiview depth estimation is non-trivial. In this paper, we present MVDepthNet, a convolutional network to solve the depth estimation problem given several image-pose pairs from a localized monocular camera in neighbor viewpoints. Multiview observations are encoded in a cost volume and then combined with the reference image to estimate the depth map using an encoder-decoder network. By encoding the information from multiview observations into the cost volume, our method achieves real-time performance and the flexibility of traditional methods that can be applied regardless of the camera intrinsic parameters and the number of images. Geometric data augmentation is used to train MVDepthNet. We further apply MVDepthNet in a monocular dense mapping system that continuously estimates depth maps using a single localized moving camera. Experiments show that our method can generate depth maps efficiently and precisely.

##### Abstract (translated by Google)
虽然深度神经网络已被广泛应用于计算机视觉问题，但将它们扩展到多视图深度估计并非易事。在本文中，我们提出了MVDepthNet，一个卷积网络，用于解决深度估计问题，在相邻视点中给出了来自局部单眼相机的几个图像 - 姿态对。多视图观察以成本体积编码，然后与参考图像组合以使用编码器 - 解码器网络估计深度图。通过将来自多视图观察的信息编码到成本量中，我们的方法实现了实时性能和传统方法的灵活性，无论相机内部参数和图像数量如何，都可以应用这些方法。几何数据增强用于训练MVDepthNet。我们进一步将MVDepthNet应用于单眼密集测绘系统，该系统使用单个局部移动摄像机连续估算深度图。实验表明，我们的方法可以高效，精确地生成深度图。

##### URL
[http://arxiv.org/abs/1807.08563](http://arxiv.org/abs/1807.08563)

##### PDF
[http://arxiv.org/pdf/1807.08563](http://arxiv.org/pdf/1807.08563)

