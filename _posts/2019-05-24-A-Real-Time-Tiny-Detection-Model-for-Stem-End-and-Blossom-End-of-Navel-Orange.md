---
layout: post
title: "A Real-Time Tiny Detection Model for Stem End and Blossom End of Navel Orange"
date: 2019-05-24 01:44:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Xiaoye Sun, Shaoyun Xu, Gongyan Li
mathjax: true
---

* content
{:toc}

##### Abstract
To distinguish the stem end and blossom end of navel orange from its black spot, we propose a real-time tiny detection model (RTTD) with low computational cost, compact architecture and high detection accuracy. In particular, based on the characteristics of the data, we apply pure dense connectivity to limit and simplify the design of the model architecture and use k-means clustering to set the size and aspect ratios of the default boxes. The architecture of model is based on deeply supervised object detectors (DSOD), and which reduces some components like dense block and prediction layers for efficient and adds some auxiliary structure like Squeeze-and-Excitation layer and Swish for accuracy. And we create a dataset in Pascal VOC format annotated the three types of detection targets stem end, blossom end and black spot. Experimental results on our orange data set confirm that RTTD has competitive results to the state-of-the-art one stage detectors like SSD, DSOD, YOLOv2, YOLOv3, RFB and FSSD, and it achieves 87.479%mAP at 131 FPS with only 5.812M parameters.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09994](http://arxiv.org/abs/1905.09994)

##### PDF
[http://arxiv.org/pdf/1905.09994](http://arxiv.org/pdf/1905.09994)

