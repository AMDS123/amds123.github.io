---
layout: post
title: "TensorMask: A Foundation for Dense Object Segmentation"
date: 2019-03-28 17:59:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Prediction Detection
author: Xinlei Chen, Ross Girshick, Kaiming He, Piotr Doll&#xe1;r
mathjax: true
---

* content
{:toc}

##### Abstract
Sliding-window object detectors that generate bounding-box object predictions over a dense, regular grid have advanced rapidly and proven popular. In contrast, modern instance segmentation approaches are dominated by methods that first detect object bounding boxes, and then crop and segment these regions, as popularized by Mask R-CNN. In this work, we investigate the paradigm of dense sliding-window instance segmentation, which is surprisingly under-explored. Our core observation is that this task is fundamentally different than other dense prediction tasks such as semantic segmentation or bounding-box object detection, as the output at every spatial location is itself a geometric structure with its own spatial dimensions. To formalize this, we treat dense instance segmentation as a prediction task over 4D tensors and present a general framework called TensorMask that explicitly captures this geometry and enables novel operators on 4D tensors. We demonstrate that the tensor view leads to large gains over baselines that ignore this structure, and leads to results comparable to Mask R-CNN. These promising results suggest that TensorMask can serve as a foundation for novel advances in dense mask prediction and a more complete understanding of the task. Code will be made available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.12174](http://arxiv.org/abs/1903.12174)

##### PDF
[http://arxiv.org/pdf/1903.12174](http://arxiv.org/pdf/1903.12174)

