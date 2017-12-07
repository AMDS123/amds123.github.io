---
layout: post
title: "Accelerating Convolutional Neural Networks for Continuous Mobile Vision via Cache Reuse"
date: 2017-12-01 16:52:04
categories: arXiv_CV
tags: arXiv_CV Face CNN Inference Detection Face_Detection
author: Mengwei Xu, Xuanzhe Liu, Yunxin Liu, Felix Xiaozhu Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Network (CNN) is the state-of-the-art algorithm of many mobile vision fields. It is also applied in many vision tasks such as face detection and augmented reality on mobile devices. Though benefited from the high accuracy achieved via deep CNN models, nowadays commercial mobile devices are often short in processing capacity and battery to continuously carry out such CNN-driven vision applications. In this paper, we propose a transparent caching mechanism, named CNNCache, that can substantially accelerate CNN-driven mobile continuous vision tasks without any efforts from app developers. To cache and reuse the computations of the similar image regions which are consecutively captured by mobile devices, CNNCache leverages two novel techniques: an image matching algorithm that quickly identifies similar image regions between images, and a cache-aware CNN inference engine that propagates the reusable regions through varied layers and reuses the computation results at layer granularity. We implement a prototype of CNNCache to run on commodity Android devices, and evaluate it via typical CNN models. The results show that CNNCache can accelerate the execution of CNN models by 20.2% on average and up to 47.1% under certain scenarios, with no more than 3.51% accuracy loss.

##### Abstract (translated by Google)
卷积神经网络（CNN）是许多移动视觉领域中最先进的算法。它也被应用于许多视觉任务中，例如移动设备上的人脸检测和增强现实。虽然得益于通过深度CNN模型实现的高精度，但是现在商用移动设备通常在处理能力和电池方面短缺，从而不断地执行这种CNN驱动的视觉应用。在本文中，我们提出了一个名为CNNCache的透明缓存机制，可以大大加速CNN驱动的移动连续视觉任务，而无需应用程序开发人员的任何努力。为了缓存和重新使用由移动设备连续捕获的相似图像区域的计算，CNNCache利用两种新技术：快速识别图像之间的相似图像区域的图像匹配算法，以及传播可重用的缓存感知的CNN推理引擎区域通过不同的层次重复使用层次粒度的计算结果。我们实现了一个CNNCache的原型，在商品Android设备上运行，并通过典型的CNN模型进行评估。结果表明，在某些情况下，CNNCache可以使CNN模型的执行速度平均提高20.2％，达到47.1％，精确度损失不超过3.51％。

##### URL
[https://arxiv.org/abs/1712.01670](https://arxiv.org/abs/1712.01670)

##### PDF
[https://arxiv.org/pdf/1712.01670](https://arxiv.org/pdf/1712.01670)

