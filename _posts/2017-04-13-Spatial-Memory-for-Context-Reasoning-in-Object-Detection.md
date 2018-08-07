---
layout: post
title: "Spatial Memory for Context Reasoning in Object Detection"
date: 2017-04-13 17:47:03
categories: arXiv_CV
tags: arXiv_CV Object_Detection Caption Detection Relation
author: Xinlei Chen, Abhinav Gupta
mathjax: true
---

* content
{:toc}

##### Abstract
Modeling instance-level context and object-object relationships is extremely challenging. It requires reasoning about bounding boxes of different classes, locations \etc. Above all, instance-level spatial reasoning inherently requires modeling conditional distributions on previous detections. Unfortunately, our current object detection systems do not have any {\bf memory} to remember what to condition on! The state-of-the-art object detectors still detect all object in parallel followed by non-maximal suppression (NMS). While memory has been used for tasks such as captioning, they mostly use image-level memory cells without capturing the spatial layout. On the other hand, modeling object-object relationships requires {\bf spatial} reasoning -- not only do we need a memory to store the spatial layout, but also a effective reasoning module to extract spatial patterns. This paper presents a conceptually simple yet powerful solution -- Spatial Memory Network (SMN), to model the instance-level context efficiently and effectively. Our spatial memory essentially assembles object instances back into a pseudo "image" representation that is easy to be fed into another ConvNet for object-object context reasoning. This leads to a new sequential reasoning architecture where image and memory are processed in parallel to obtain detections which update the memory again. We show our SMN direction is promising as it provides 2.2\% improvement over baseline Faster RCNN on the COCO dataset so far.

##### Abstract (translated by Google)
对实例级上下文和对象 - 对象关系建模极具挑战性。它需要推理关于不同类，位置\等的边界框。最重要的是，实例级空间推理固有地需要在先前的检测上建模条件分布。不幸的是，我们当前的对象检测系统没有任何{\ bf memory}来记住要处理的内容！现有技术的物体探测器仍然并行检测所有物体，然后是非最大抑制（NMS）。虽然存储器已用于诸如字幕之类的任务，但它们大多使用图像级存储器单元而不捕获空间布局。另一方面，建模对象 - 对象关系需要{\ bf spatial}推理 - 我们不仅需要内存来存储空间布局，还需要一个有效的推理模块来提取空间模式。本文介绍了一种概念上简单但功能强大的解决方案 - 空间内存网络（SMN），可以高效且有效地对实例级上下文进行建模。我们的空间存储器实质上将对象实例组装回伪“图像”表示，该表示很容易被送入另一个ConvNet以进行对象 - 对象上下文推理。这导致新的顺序推理架构，其中图像和存储器被并行处理以获得再次更新存储器的检测。我们展示了我们的SMN方向是有希望的，因为它提供了比基线更快的RCNN在COCO数据集上的2.2％的改进。

##### URL
[https://arxiv.org/abs/1704.04224](https://arxiv.org/abs/1704.04224)

##### PDF
[https://arxiv.org/pdf/1704.04224](https://arxiv.org/pdf/1704.04224)

