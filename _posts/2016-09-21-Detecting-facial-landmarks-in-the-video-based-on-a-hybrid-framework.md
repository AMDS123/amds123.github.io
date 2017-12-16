---
layout: post
title: "Detecting facial landmarks in the video based on a hybrid framework"
date: 2016-09-21 07:29:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Face Tracking CNN Detection Face_Detection
author: Nian Cai, Zhineng Lin, Fu Zhang, Guandong Cen, Han Wang
mathjax: true
---

* content
{:toc}

##### Abstract
To dynamically detect the facial landmarks in the video, we propose a novel hybrid framework termed as detection-tracking-detection (DTD). First, the face bounding box is achieved from the first frame of the video sequence based on a traditional face detection method. Then, a landmark detector detects the facial landmarks, which is based on a cascaded deep convolution neural network (DCNN). Next, the face bounding box in the current frame is estimated and validated after the facial landmarks in the previous frame are tracked based on the median flow. Finally, the facial landmarks in the current frame are exactly detected from the validated face bounding box via the landmark detector. Experimental results indicate that the proposed framework can detect the facial landmarks in the video sequence more effectively and with lower consuming time compared to the frame-by-frame method via the DCNN.

##### Abstract (translated by Google)
为了动态检测视频中的面部标志，我们提出了一种称为检测跟踪检测（DTD）的新型混合框架。首先，基于传统的人脸检测方法，从视频序列的第一帧开始实现人脸边界框。然后，地标检测器检测基于级联深度卷积神经网络（DCNN）的面部标志。接下来，基于中间流量来跟踪前一帧中的面部标志之后，估计并验证当前帧中的面部边界框。最后，通过地标检测器从验证的人脸边界框精确地检测当前帧中的人脸地标。实验结果表明，所提出的框架能够更有效地检测视频序列中的面部标志，并且与通过DCNN的逐帧方法相比具有更低的耗时。

##### URL
[https://arxiv.org/abs/1609.06441](https://arxiv.org/abs/1609.06441)

##### PDF
[https://arxiv.org/pdf/1609.06441](https://arxiv.org/pdf/1609.06441)

