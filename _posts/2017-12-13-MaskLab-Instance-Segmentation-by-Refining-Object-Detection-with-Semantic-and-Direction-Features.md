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
在这项工作中，我们解决了实例分割的问题，同时解决了对象检测和语义分割的任务。为了实现这个目标，我们提出了一个名为MaskLab的模型，它产生三个输出：盒子检测，语义分割和方向预测。建立在Faster-RCNN对象检测器之上，预测框提供了对象实例的精确定位。在每个感兴趣的区域内，MaskLab通过结合语义和方向预测来执行前景/背景分割。语义分割帮助模型区分包括背景在内的不同语义类别的对象，而方向预测（通过估计每个像素朝向其相应中心的方向）允许分离相同语义类别的实例。此外，我们还探讨了从分割和检测（即，卷积和超列）中最近成功的方法。我们提出的模型是在COCO实例细分基准上进行评估，并与其他最先进的模型进行比较。

##### URL
[http://arxiv.org/abs/1712.04837](http://arxiv.org/abs/1712.04837)

##### PDF
[http://arxiv.org/pdf/1712.04837](http://arxiv.org/pdf/1712.04837)

