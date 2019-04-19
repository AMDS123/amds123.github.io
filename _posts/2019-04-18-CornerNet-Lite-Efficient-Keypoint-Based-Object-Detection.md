---
layout: post
title: "CornerNet-Lite: Efficient Keypoint Based Object Detection"
date: 2019-04-18 17:21:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Detection
author: Hei Law, Yun Teng, Olga Russakovsky, Jia Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Keypoint-based methods are a relatively new paradigm in object detection, eliminating the need for anchor boxes and offering a simplified detection framework. Keypoint-based CornerNet achieves state of the art accuracy among single-stage detectors. However, this accuracy comes at high processing cost. In this work, we tackle the problem of efficient keypoint-based object detection and introduce CornerNet-Lite. CornerNet-Lite is a combination of two efficient variants of CornerNet: CornerNet-Saccade, which uses an attention mechanism to eliminate the need for exhaustively processing all pixels of the image, and CornerNet-Squeeze, which introduces a new compact backbone architecture. Together these two variants address the two critical use cases in efficient object detection: improving efficiency without sacrificing accuracy, and improving accuracy at real-time efficiency. CornerNet-Saccade is suitable for offline processing, improving the efficiency of CornerNet by 6.0x and the AP by 1.0% on COCO. CornerNet-Squeeze is suitable for real-time detection, improving both the efficiency and accuracy of the popular real-time detector YOLOv3 (34.4% AP at 34ms for CornerNet-Squeeze compared to 33.0% AP at 39ms for YOLOv3 on COCO). Together these contributions for the first time reveal the potential of keypoint-based detection to be useful for applications requiring processing efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.08900](http://arxiv.org/abs/1904.08900)

##### PDF
[http://arxiv.org/pdf/1904.08900](http://arxiv.org/pdf/1904.08900)

