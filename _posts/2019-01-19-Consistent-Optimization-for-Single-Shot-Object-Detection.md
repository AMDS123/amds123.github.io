---
layout: post
title: "Consistent Optimization for Single-Shot Object Detection"
date: 2019-01-19 17:57:37
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Inference Detection
author: Tao Kong, Fuchun Sun, Huaping Liu, Yuning Jiang, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We present consistent optimization for single stage object detection. Previous works of single stage object detectors usually rely on the regular, dense sampled anchors to generate hypothesis for the optimization of the model. Through an examination of the behavior of the detector, we observe that the misalignment between the optimization target and inference configurations has hindered the performance improvement. We propose to bride this gap by consistent optimization, which is an extension of the traditional single stage detector's optimization strategy. Consistent optimization focuses on matching the training hypotheses and the inference quality by utilizing of the refined anchors during training. To evaluate its effectiveness, we conduct various design choices based on the state-of-the-art RetinaNet detector. We demonstrate it is the consistent optimization, not the architecture design, that yields the performance boosts. Consistent optimization is nearly cost-free, and achieves stable performance gains independent of the model capacities or input scales. Specifically, utilizing consistent optimization improves RetinaNet from 39.1 AP to 40.1 AP on COCO dataset without any bells or whistles, which surpasses the accuracy of all existing state-of-the-art one-stage detectors when adopting ResNet-101 as backbone. The code will be made available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.06563](http://arxiv.org/abs/1901.06563)

##### PDF
[http://arxiv.org/pdf/1901.06563](http://arxiv.org/pdf/1901.06563)

