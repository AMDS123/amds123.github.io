---
layout: post
title: "Detecting 11K Classes: Large Scale Object Detection without Fine-Grained Bounding Boxes"
date: 2019-08-14 16:42:15
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Deep_Learning Detection Relation
author: Hao Yang, Hao Wu, Hao Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in deep learning greatly boost the performance of object detection. State-of-the-art methods such as Faster-RCNN, FPN and R-FCN have achieved high accuracy in challenging benchmark datasets. However, these methods require fully annotated object bounding boxes for training, which are incredibly hard to scale up due to the high annotation cost. Weakly-supervised methods, on the other hand, only require image-level labels for training, but the performance is far below their fully-supervised counterparts. In this paper, we propose a semi-supervised large scale fine-grained detection method, which only needs bounding box annotations of a smaller number of coarse-grained classes and image-level labels of large scale fine-grained classes, and can detect all classes at nearly fully-supervised accuracy. We achieve this by utilizing the correlations between coarse-grained and fine-grained classes with shared backbone, soft-attention based proposal re-ranking, and a dual-level memory module. Experiment results show that our methods can achieve close accuracy on object detection to state-of-the-art fully-supervised methods on two large scale datasets, ImageNet and OpenImages, with only a small fraction of fully annotated classes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05217](http://arxiv.org/abs/1908.05217)

##### PDF
[http://arxiv.org/pdf/1908.05217](http://arxiv.org/pdf/1908.05217)

