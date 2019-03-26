---
layout: post
title: "BshapeNet: Object Detection and Instance Segmentation with Bounding Shape Masks"
date: 2019-03-22 19:04:05
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation Detection
author: Ba Rom Kang, Ha Young Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Recent object detectors use four-coordinate bounding box (bbox) regression to predict object locations. Providing additional information indicating the object positions and coordinates will improve detection performance. Thus, we propose two types of masks: a bbox mask and a bounding shape (bshape) mask, to represent the object's bbox and boundary shape, respectively. For each of these types, we consider two variants: the Thick model and the Scored model, both of which have the same morphology but differ in ways to make their boundaries thicker. To evaluate the proposed masks, we design extended frameworks by adding a bshape mask (or a bbox mask) branch to a Faster R-CNN framework, and call this BshapeNet (or BboxNet). Further, we propose BshapeNet+, a network that combines a bshape mask branch with a Mask R-CNN to improve instance segmentation as well as detection. Among our proposed models, BshapeNet+ demonstrates the best performance in both tasks and achieves highly competitive results with state of the art (SOTA) models. Particularly, it improves the detection results over Faster R-CNN+RoIAlign (37.3% and 28.9%) with a detection AP of 42.4% and 32.3% on MS COCO test-dev and Cityscapes val, respectively. Furthermore, for small objects, it achieves 24.9% AP on COCO test-dev, a significant improvement over previous SOTA models. For instance segmentation, it is substantially superior to Mask R-CNN on both test datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.10327](http://arxiv.org/abs/1810.10327)

##### PDF
[http://arxiv.org/pdf/1810.10327](http://arxiv.org/pdf/1810.10327)

