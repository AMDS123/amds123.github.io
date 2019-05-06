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


##### URL
[https://arxiv.org/abs/1704.04224](https://arxiv.org/abs/1704.04224)

##### PDF
[https://arxiv.org/pdf/1704.04224](https://arxiv.org/pdf/1704.04224)

