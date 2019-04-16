---
layout: post
title: "Acquisition of Localization Confidence for Accurate Object Detection"
date: 2018-07-30 21:36:20
categories: arXiv_CV
tags: arXiv_CV Object_Detection Optimization Classification Detection
author: Borui Jiang, Ruixuan Luo, Jiayuan Mao, Tete Xiao, Yuning Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
Modern CNN-based object detectors rely on bounding box regression and non-maximum suppression to localize objects. While the probabilities for class labels naturally reflect classification confidence, localization confidence is absent. This makes properly localized bounding boxes degenerate during iterative regression or even suppressed during NMS. In the paper we propose IoU-Net learning to predict the IoU between each detected bounding box and the matched ground-truth. The network acquires this confidence of localization, which improves the NMS procedure by preserving accurately localized bounding boxes. Furthermore, an optimization-based bounding box refinement method is proposed, where the predicted IoU is formulated as the objective. Extensive experiments on the MS-COCO dataset show the effectiveness of IoU-Net, as well as its compatibility with and adaptivity to several state-of-the-art object detectors.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1807.11590](https://arxiv.org/abs/1807.11590)

##### PDF
[https://arxiv.org/pdf/1807.11590](https://arxiv.org/pdf/1807.11590)

