---
layout: post
title: "Softer-NMS: Rethinking Bounding Box Regression for Accurate Object Detection"
date: 2018-09-23 07:07:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Classification Detection
author: Yihui He, Xiangyu Zhang, Marios Savvides, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
Non-maximum suppression (NMS) is essential for state-of-the-art object detectors to localize object from a set of candidate locations. However, accurate candidate location sometimes is not associated with a high classification score, which leads to object localization failure during NMS. In this paper, we introduce a novel bounding box regression loss for learning bounding box transformation and localization variance together. The resulting localization variance exhibits a strong connection to localization accuracy, which is then utilized in our new non-maximum suppression method to improve localization accuracy for object detection. On MS-COCO, we boost the AP of VGG-16 faster R-CNN from 23.6% to 29.1% with a single model and nearly no additional computational overhead. More importantly, our method is able to improve the AP of ResNet-50 FPN fast R-CNN from 36.8% to 37.8%, which achieves state-of-the-art bounding box refinement result.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1809.08545](https://arxiv.org/abs/1809.08545)

##### PDF
[https://arxiv.org/pdf/1809.08545](https://arxiv.org/pdf/1809.08545)

