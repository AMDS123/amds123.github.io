---
layout: post
title: "NOTE-RCNN: NOise Tolerant Ensemble RCNN for Semi-Supervised Object Detection"
date: 2018-12-01 02:14:57
categories: arXiv_CV
tags: arXiv_CV Object_Detection Weakly_Supervised Classification Detection
author: JIyang Gao, Jiang Wang, Shengyang Dai, Li-Jia Li, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
The labeling cost of large number of bounding boxes is one of the main challenges for training modern object detectors. To reduce the dependence on expensive bounding box annotations, we propose a new semi-supervised object detection formulation, in which a few seed box level annotations and a large scale of image level annotations are used to train the detector. We adopt a training-mining framework, which is widely used in weakly supervised object detection tasks. However, the mining process inherently introduces various kinds of labelling noises: false negatives, false positives and inaccurate boundaries, which can be harmful for training the standard object detectors (e.g. Faster RCNN). We propose a novel NOise Tolerant Ensemble RCNN (NOTE-RCNN) object detector to handle such noisy labels. Comparing to standard Faster RCNN, it contains three highlights: an ensemble of two classification heads and a distillation head to avoid overfitting on noisy labels and improve the mining precision, masking the negative sample loss in box predictor to avoid the harm of false negative labels, and training box regression head only on seed annotations to eliminate the harm from inaccurate boundaries of mined bounding boxes. We evaluate the methods on ILSVRC 2013 and MSCOCO 2017 dataset; we observe that the detection accuracy consistently improves as we iterate between mining and training steps, and state-of-the-art performance is achieved.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.00124](http://arxiv.org/abs/1812.00124)

##### PDF
[http://arxiv.org/pdf/1812.00124](http://arxiv.org/pdf/1812.00124)

