---
layout: post
title: "Bounding Box Regression with Uncertainty for Accurate Object Detection"
date: 2019-03-25 19:49:26
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Yihui He, Chenchen Zhu, Jianren Wang, Marios Savvides, Xiangyu Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Large-scale object detection datasets (e.g., MS-COCO) try to define the ground truth bounding boxes as clear as possible. However, we observe that ambiguities are still introduced when labeling the bounding boxes. In this paper, we propose a novel bounding box regression loss for learning bounding box transformation and localization variance together. Our loss greatly improves the localization accuracies of various architectures with nearly no additional computation. The learned localization variance allows us to merge neighboring bounding boxes during non-maximum suppression (NMS), which further improves the localization performance. On MS-COCO, we boost the Average Precision (AP) of VGG-16 Faster R-CNN from 23.6% to 29.1%. More importantly, for ResNet-50-FPN Mask R-CNN, our method improves the AP and AP90 by 1.8% and 6.2% respectively, which significantly outperforms previous state-of-the-art bounding box refinement methods. Our code and models are available at: github.com/yihui-he/KL-Loss

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1809.08545](http://arxiv.org/abs/1809.08545)

##### PDF
[http://arxiv.org/pdf/1809.08545](http://arxiv.org/pdf/1809.08545)

