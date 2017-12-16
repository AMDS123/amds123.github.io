---
layout: post
title: "Scale-Aware Face Detection"
date: 2017-06-29 17:40:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face CNN Detection Face_Detection
author: Zekun Hao, Yu Liu, Hongwei Qin, Junjie Yan, Xiu Li, Xiaolin Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional neural network (CNN) based face detectors are inefficient in handling faces of diverse scales. They rely on either fitting a large single model to faces across a large scale range or multi-scale testing. Both are computationally expensive. We propose Scale-aware Face Detector (SAFD) to handle scale explicitly using CNN, and achieve better performance with less computation cost. Prior to detection, an efficient CNN predicts the scale distribution histogram of the faces. Then the scale histogram guides the zoom-in and zoom-out of the image. Since the faces will be approximately in uniform scale after zoom, they can be detected accurately even with much smaller CNN. Actually, more than 99% of the faces in AFW can be covered with less than two zooms per image. Extensive experiments on FDDB, MALF and AFW show advantages of SAFD.

##### Abstract (translated by Google)
基于卷积神经网络（CNN）的人脸检测器在处理不同尺度的人脸时效率低下。他们依靠大型单一模型来适应大范围或多尺度测试。两者在计算上都很昂贵。我们提出了具有尺度感知的人脸检测器（SAFD）来明确使用CNN来处理尺度，并且以更少的计算成本实现更好的性能。在检测之前，有效的CNN预测人脸的尺度分布直方图。然后缩放直方图指导图像的放大和缩小。由于变焦后的人脸大致是均匀的，所以即使CNN小得多，也可以精确地检测到人脸。实际上，AFW中超过99％的人脸可以用每张图片少于两个的缩放来覆盖。 FDDB，MALF和AFW的大量实验表明了SAFD的优点。

##### URL
[https://arxiv.org/abs/1706.09876](https://arxiv.org/abs/1706.09876)

##### PDF
[https://arxiv.org/pdf/1706.09876](https://arxiv.org/pdf/1706.09876)

