---
layout: post
title: "Oriented Response Networks"
date: 2017-07-13 02:32:23
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Classification
author: Yanzhao Zhou, Qixiang Ye, Qiang Qiu, Jianbin Jiao
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolution Neural Networks (DCNNs) are capable of learning unprecedentedly effective image representations. However, their ability in handling significant local and global image rotations remains limited. In this paper, we propose Active Rotating Filters (ARFs) that actively rotate during convolution and produce feature maps with location and orientation explicitly encoded. An ARF acts as a virtual filter bank containing the filter itself and its multiple unmaterialised rotated versions. During back-propagation, an ARF is collectively updated using errors from all its rotated versions. DCNNs using ARFs, referred to as Oriented Response Networks (ORNs), can produce within-class rotation-invariant deep features while maintaining inter-class discrimination for classification tasks. The oriented response produced by ORNs can also be used for image and object orientation estimation tasks. Over multiple state-of-the-art DCNN architectures, such as VGG, ResNet, and STN, we consistently observe that replacing regular filters with the proposed ARFs leads to significant reduction in the number of network parameters and improvement in classification performance. We report the best results on several commonly used benchmarks.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）能够学习空前有效的图像表示。然而，他们处理重要的地方和全球形象轮换的能力仍然有限。在本文中，我们提出在卷积过程中主动旋转的主动旋转滤波器（ARF），并且产生具有明确编码的位置和方向的特征图。一个ARF作为一个虚拟的过滤器组，包含过滤器本身及其多个非物质化的旋转版本。在反向传播期间，ARF将使用所有旋转版本中的错误进行集体更新。使用ARF的DCNN被称为定向响应网络（ORN），可以产生课堂上不旋转的深度特征，同时保持课堂上对分类任务的区分。由ORN产生的定向响应也可用于图像和对象定向估计任务。在多个国家的最先进的DCNN结构，如VGG，RESNET和STN，我们一直观察与建议ARFs定期更换过滤器导致的网络参数和提高分类性能人数显著减少。我们在几个常用的基准上报告最好的结果。

##### URL
[https://arxiv.org/abs/1701.01833](https://arxiv.org/abs/1701.01833)

##### PDF
[https://arxiv.org/pdf/1701.01833](https://arxiv.org/pdf/1701.01833)

