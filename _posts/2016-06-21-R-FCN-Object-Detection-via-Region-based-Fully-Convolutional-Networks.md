---
layout: post
title: "R-FCN: Object Detection via Region-based Fully Convolutional Networks"
date: 2016-06-21 15:28:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Jifeng Dai, Yi Li, Kaiming He, Jian Sun
mathjax: true
---

* content
{:toc}

##### Abstract
We present region-based, fully convolutional networks for accurate and efficient object detection. In contrast to previous region-based detectors such as Fast/Faster R-CNN that apply a costly per-region subnetwork hundreds of times, our region-based detector is fully convolutional with almost all computation shared on the entire image. To achieve this goal, we propose position-sensitive score maps to address a dilemma between translation-invariance in image classification and translation-variance in object detection. Our method can thus naturally adopt fully convolutional image classifier backbones, such as the latest Residual Networks (ResNets), for object detection. We show competitive results on the PASCAL VOC datasets (e.g., 83.6% mAP on the 2007 set) with the 101-layer ResNet. Meanwhile, our result is achieved at a test-time speed of 170ms per image, 2.5-20x faster than the Faster R-CNN counterpart. Code is made publicly available at: this https URL

##### Abstract (translated by Google)
我们提出了基于区域的完全卷积网络，以实现准确和高效的目标检测。与先前的基于区域的检测器（例如快速/更快的R-CNN）相比，这种检测器应用昂贵的每区域子网络数百次，我们的基于区域的检测器完全是卷积的，几乎所有的计算都在整个图像上共享。为了实现这一目标，我们提出了位置敏感分数图来解决图像分类中的平移不变性与对象检测中的平移变化之间的两难境地。因此，我们的方法自然可以采用完全的卷积图像分类器骨架，如最新的残余网络（ResNets）来进行物体检测。我们使用101层ResNet在PASCAL VOC数据集（例如，2007年的83.6％mAP）上展示竞争结果。同时，我们的测试结果是以每张图像170毫秒的测试速度实现的，比R-CNN的速度快2.5-20倍。代码可在以下网址公开获得：https：

##### URL
[https://arxiv.org/abs/1605.06409](https://arxiv.org/abs/1605.06409)

