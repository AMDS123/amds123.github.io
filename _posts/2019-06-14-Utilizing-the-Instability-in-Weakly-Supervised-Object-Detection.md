---
layout: post
title: "Utilizing the Instability in Weakly Supervised Object Detection"
date: 2019-06-14 05:05:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Quantitative Detection
author: Yan Gao, Boxiao Liu, Nan Guo, Xiaochun Ye, Fang Wan, Haihang You, Dongrui Fan
mathjax: true
---

* content
{:toc}

##### Abstract
Weakly supervised object detection (WSOD) focuses on training object detector with only image-level annotations, and is challenging due to the gap between the supervision and the objective. Most of existing approaches model WSOD as a multiple instance learning (MIL) problem. However, we observe that the result of MIL based detector is unstable, i.e., the most confident bounding boxes change significantly when using different initializations. We quantitatively demonstrate the instability by introducing a metric to measure it, and empirically analyze the reason of instability. Although the instability seems harmful for detection task, we argue that it can be utilized to improve the performance by fusing the results of differently initialized detectors. To implement this idea, we propose an end-to-end framework with multiple detection branches, and introduce a simple fusion strategy. We further propose an orthogonal initialization method to increase the difference between detection branches. By utilizing the instability, we achieve 52.6% and 48.0% mAP on the challenging PASCAL VOC 2007 and 2012 datasets, which are both the new state-of-the-arts.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.06023](https://arxiv.org/abs/1906.06023)

##### PDF
[https://arxiv.org/pdf/1906.06023](https://arxiv.org/pdf/1906.06023)

