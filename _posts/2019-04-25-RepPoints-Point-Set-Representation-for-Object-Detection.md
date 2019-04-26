---
layout: post
title: "RepPoints: Point Set Representation for Object Detection"
date: 2019-04-25 17:59:28
categories: arXiv_CV
tags: arXiv_CV Object_Detection Prediction Detection Recognition
author: Ze Yang, Shaohui Liu, Han Hu, Liwei Wang, Stephen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Modern object detectors rely heavily on rectangular bounding boxes, such as anchors, proposals and the final predictions, to represent objects at various recognition stages. The bounding box is convenient to use but provides only a coarse localization of objects and leads to a correspondingly coarse extraction of object features. In this paper, we present \textbf{RepPoints} (representative points), a new finer representation of objects as a set of sample points useful for both localization and recognition. Given ground truth localization and recognition targets for training, RepPoints learn to automatically arrange themselves in a manner that bounds the spatial extent of an object and indicates semantically significant local areas. They furthermore do not require the use of anchors to sample a space of bounding boxes. We show that an anchor-free object detector based on RepPoints, implemented without multi-scale training and testing, can be as effective as state-of-the-art anchor-based detection methods, with 42.8 AP and 65.0 $AP_{50}$ on the COCO test-dev detection benchmark.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.11490](http://arxiv.org/abs/1904.11490)

##### PDF
[http://arxiv.org/pdf/1904.11490](http://arxiv.org/pdf/1904.11490)

