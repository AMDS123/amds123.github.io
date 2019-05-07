---
layout: post
title: "MaskLab: Instance Segmentation by Refining Object Detection with Semantic and Direction Features"
date: 2017-12-13 16:09:55
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Semantic_Segmentation Prediction Detection
author: Liang-Chieh Chen, Alexander Hermans, George Papandreou, Florian Schroff, Peng Wang, Hartwig Adam
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we tackle the problem of instance segmentation, the task of simultaneously solving object detection and semantic segmentation. Towards this goal, we present a model, called MaskLab, which produces three outputs: box detection, semantic segmentation, and direction prediction. Building on top of the Faster-RCNN object detector, the predicted boxes provide accurate localization of object instances. Within each region of interest, MaskLab performs foreground/background segmentation by combining semantic and direction prediction. Semantic segmentation assists the model in distinguishing between objects of different semantic classes including background, while the direction prediction, estimating each pixel's direction towards its corresponding center, allows separating instances of the same semantic class. Moreover, we explore the effect of incorporating recent successful methods from both segmentation and detection (i.e. atrous convolution and hypercolumn). Our proposed model is evaluated on the COCO instance segmentation benchmark and shows comparable performance with other state-of-art models.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.04837](https://arxiv.org/abs/1712.04837)

##### PDF
[https://arxiv.org/pdf/1712.04837](https://arxiv.org/pdf/1712.04837)

