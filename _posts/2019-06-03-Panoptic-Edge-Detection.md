---
layout: post
title: "Panoptic Edge Detection"
date: 2019-06-03 06:18:30
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection
author: Yuan Hu, Yingtian Zou, Jiashi Feng
mathjax: true
---

* content
{:toc}

##### Abstract
Pursuing more complete and coherent scene understanding towards realistic vision applications drives edge detection from category-agnostic to category-aware semantic level. However, finer delineation of instance-level boundaries still remains unexcavated. In this work, we address a new finer-grained task, termed panoptic edge detection (PED), which aims at predicting semantic-level boundaries for stuff categories and instance-level boundaries for instance categories, in order to provide more comprehensive and unified scene understanding from the perspective of edges.We then propose a versatile framework, Panoptic Edge Network (PEN), which aggregates different tasks of object detection, semantic and instance edge detection into a single holistic network with multiple branches. Based on the same feature representation, the semantic edge branch produces semantic-level boundaries for all categories and the object detection branch generates instance proposals. Conditioned on the prior information from these two branches, the instance edge branch aims at instantiating edge predictions for instance categories. Besides, we also devise a Panoptic Dual F-measure (F2) metric for the new PED task to uniformly measure edge prediction quality for both stuff and instances. By joint end-to-end training, the proposed PEN framework outperforms all competitive baselines on Cityscapes and ADE20K datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.00590](http://arxiv.org/abs/1906.00590)

##### PDF
[http://arxiv.org/pdf/1906.00590](http://arxiv.org/pdf/1906.00590)

