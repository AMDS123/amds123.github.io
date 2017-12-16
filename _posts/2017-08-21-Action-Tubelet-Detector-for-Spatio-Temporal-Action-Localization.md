---
layout: post
title: "Action Tubelet Detector for Spatio-Temporal Action Localization"
date: 2017-08-21 13:54:34
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Detection
author: Vicky Kalogeiton, Philippe Weinzaepfel, Vittorio Ferrari, Cordelia Schmid
mathjax: true
---

* content
{:toc}

##### Abstract
Current state-of-the-art approaches for spatio-temporal action localization rely on detections at the frame level that are then linked or tracked across time. In this paper, we leverage the temporal continuity of videos instead of operating at the frame level. We propose the ACtion Tubelet detector (ACT-detector) that takes as input a sequence of frames and outputs tubelets, i.e., sequences of bounding boxes with associated scores. The same way state-of-the-art object detectors rely on anchor boxes, our ACT-detector is based on anchor cuboids. We build upon the SSD framework. Convolutional features are extracted for each frame, while scores and regressions are based on the temporal stacking of these features, thus exploiting information from a sequence. Our experimental results show that leveraging sequences of frames significantly improves detection performance over using individual frames. The gain of our tubelet detector can be explained by both more accurate scores and more precise localization. Our ACT-detector outperforms the state-of-the-art methods for frame-mAP and video-mAP on the J-HMDB and UCF-101 datasets, in particular at high overlap thresholds.

##### Abstract (translated by Google)
当前用于时空动作定位的最先进方法依赖于帧级的检测，然后在时间上进行链接或跟踪。在本文中，我们利用视频的时间连续性而不是在帧级操作。我们提出ACtion小管检测器（ACT-检测器），其输入一系列帧并输出管小节，即具有相关分数的边界框的序列。同样的方式最先进的物体探测器依靠锚箱，我们的ACT探测器是基于锚定长方体。我们建立在SSD框架之上。每帧提取卷积特征，而分数和回归则基于这些特征的时间叠加，从而利用序列中的信息。我们的实验结果表明，利用帧序列显着提高了检测性能超过使用个别帧。我们的小管检测器的增益可以通过更准确的分数和更精确的定位来解释。我们的ACT检测器优于J-HMDB和UCF-101数据集上最先进的frame-mAP和video-mAP方法，特别是在高重叠阈值下。

##### URL
[https://arxiv.org/abs/1705.01861](https://arxiv.org/abs/1705.01861)

##### PDF
[https://arxiv.org/pdf/1705.01861](https://arxiv.org/pdf/1705.01861)

