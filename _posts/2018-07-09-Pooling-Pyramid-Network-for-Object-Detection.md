---
layout: post
title: "Pooling Pyramid Network for Object Detection"
date: 2018-07-09 17:40:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Pengchong Jin, Vivek Rathod, Xiangxin Zhu
mathjax: true
---

* content
{:toc}

##### Abstract
We'd like to share a simple tweak of Single Shot Multibox Detector (SSD) family of detectors, which is effective in reducing model size while maintaining the same quality. We share box predictors across all scales, and replace convolution between scales with max pooling. This has two advantages over vanilla SSD: (1) it avoids score miscalibration across scales; (2) the shared predictor sees the training data over all scales. Since we reduce the number of predictors to one, and trim all convolutions between them, model size is significantly smaller. We empirically show that these changes do not hurt model quality compared to vanilla SSD.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.03284](https://arxiv.org/abs/1807.03284)

##### PDF
[https://arxiv.org/pdf/1807.03284](https://arxiv.org/pdf/1807.03284)

