---
layout: post
title: "A Fast and Robust Matching Framework for Multimodal Remote Sensing Image Registration"
date: 2018-08-19 10:19:06
categories: arXiv_CV
tags: arXiv_CV Detection
author: Yuanxin Ye, Lorenzo Bruzzone, Jie Shan, Francesca Bovolo, Qing Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
While image registration has been studied in remote sensing community for decades, registering multimodal data [e.g., optical, light detection and ranging (LiDAR), synthetic aperture radar (SAR), and map] remains a challenging problem because of significant nonlinear intensity differences between such data. To address this problem, we present a novel fast and robust matching framework integrating local descriptors for multimodal registration. In the proposed framework, a local descriptor (such as Histogram of Oriented Gradient (HOG), Local Self-Similarity or Speeded-Up Robust Feature) is first extracted at each pixel to form a pixel-wise feature representation of an image. Then we define a similarity measure based on the feature representation in frequency domain using the Fast Fourier Transform (FFT) technique, followed by a template matching scheme to detect control points between images. We also propose a novel pixel-wise feature representation using orientated gradients of images, which is named channel features of orientated gradients (CFOG). This novel feature is an extension of the pixel-wise HOG descriptor, and outperforms that both in matching performance and computational efficiency. The major advantages of the proposed framework include (1) structural similarity representation using the pixel-wise feature description and (2) high computational efficiency due to the use of FFT. Moreover, we design an automatic registration system for very large-size multimodal images based on the proposed framework. Experimental results obtained on many different types of multimodal images show the superior matching performance of the proposed framework with respect to the state-of-the-art methods and the effectiveness of the designed system, which show very good potential large-size image registration in real applications.

##### Abstract (translated by Google)
虽然图像配准已经在遥感界进行了数十年的研究，但登记多模态数据[例如光学，光探测和测距（LiDAR），合成孔径雷达（SAR）和地图]仍然是一个具有挑战性的问题，因为它们之间存在显着的非线性强度差异。这样的数据。为了解决这个问题，我们提出了一种新颖的快速而强大的匹配框架，它集成了用于多模式注册的局部描述符。在所提出的框架中，首先在每个像素处提取局部描述符（诸如定向梯度直方图（HOG），局部自相似性或加速鲁棒特征）以形成图像的逐像素特征表示。然后，我们使用快速傅立叶变换（FFT）技术基于频域中的特征表示来定义相似性度量，接着是模板匹配方案以检测图像之间的控制点。我们还提出了一种使用定向梯度图像的新颖像素方式特征表示，其被称为定向梯度（CFOG）的通道特征。这个新颖的特征是像素方式HOG描述符的扩展，并且在匹配性能和计算效率方面都优于两者。所提出的框架的主要优点包括（1）使用逐像素特征描述的结构相似性表示和（2）由于使用FFT而具有高计算效率。此外，我们基于所提出的框架设计了用于超大尺寸多模态图像的自动配准系统。在许多不同类型的多模态图像上获得的实验结果表明，所提出的框架在最先进的方法和所设计的系统的有效性方面具有优越的匹配性能，显示出非常好的潜在大尺寸图像配准。实际应用。

##### URL
[http://arxiv.org/abs/1808.06194](http://arxiv.org/abs/1808.06194)

##### PDF
[http://arxiv.org/pdf/1808.06194](http://arxiv.org/pdf/1808.06194)

