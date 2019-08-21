---
layout: post
title: "Consistent Scale Normalization for Object Recognition"
date: 2019-08-20 13:12:33
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Pose_Estimation CNN Detection Recognition
author: Zewen He, He Huang, Yudong Wu, Guan Huang, Wensheng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Scale variation remains a challenge problem for object detection. Common paradigms usually adopt multi-scale training &amp; testing (image pyramid) or FPN (feature pyramid network) to process objects in wide scale range. However, multi-scale methods aggravate more variation of scale that even deep convolution neural networks with FPN cannot handle well. In this work, we propose an innovative paradigm called Consistent Scale Normalization (CSN) to resolve above problem. CSN compresses the scale space of objects into a consistent range (CSN range), in both training and testing phase. This reassures problem of scale variation fundamentally, and reduces the difficulty for network learning. Experiments show that CSN surpasses multi-scale counterpart significantly for object detection, instance segmentation and multi-task human pose estimation, on several architectures. On COCO test-dev, our single model based on CSN achieves 46.5 mAP with a ResNet-101 backbone, which is among the state-of-the-art (SOTA) candidates for object detection.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.07323](http://arxiv.org/abs/1908.07323)

##### PDF
[http://arxiv.org/pdf/1908.07323](http://arxiv.org/pdf/1908.07323)

