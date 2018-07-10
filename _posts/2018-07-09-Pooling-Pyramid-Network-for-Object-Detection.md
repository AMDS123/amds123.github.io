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
我们想分享一下Single Shot Multibox Detector（SSD）系列探测器的简单调整，它可以有效地减小模型尺寸，同时保持相同的质量。我们在所有尺度上共享盒子预测器，并用最大池化替换卷之间的卷积。与vanilla SSD相比，这有两个优点：（1）它避免了各种尺度的评分错误校准; （2）共享预测器可以查看所有比例的训练数据。由于我们将预测变量的数量减少到一个，并修剪它们之间的所有卷积，因此模型大小要小得多。我们凭经验证明，与香草SSD相比，这些变化不会损害模型质量。

##### URL
[http://arxiv.org/abs/1807.03284](http://arxiv.org/abs/1807.03284)

##### PDF
[http://arxiv.org/pdf/1807.03284](http://arxiv.org/pdf/1807.03284)

