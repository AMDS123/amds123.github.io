---
layout: post
title: "FoveaBox: Beyond Anchor-based Object Detector"
date: 2019-04-08 01:43:48
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Tao Kong, Fuchun Sun, Huaping Liu, Yuning Jiang, Jianbo Shi
mathjax: true
---

* content
{:toc}

##### Abstract
We present FoveaBox, an accurate, flexible and completely anchor-free framework for object detection. While almost all state-of-the-art object detectors utilize the predefined anchors to enumerate possible locations, scales and aspect ratios for the search of the objects, their performance and generalization ability are also limited to the design of anchors. Instead, FoveaBox directly learns the object existing possibility and the bounding box coordinates without anchor reference. This is achieved by: (a) predicting category-sensitive semantic maps for the object existing possibility, and (b) producing category-agnostic bounding box for each position that potentially contains an object. The scales of target boxes are naturally associated with feature pyramid representations for each input image. Without bells and whistles, FoveaBox achieves state-of-the-art single model performance of 42.1 AP on the standard COCO detection benchmark. Specially for the objects with arbitrary aspect ratios, FoveaBox brings in significant improvement compared to the anchor-based detectors. More surprisingly, when it is challenged by the stretched testing images, FoveaBox shows great robustness and generalization ability to the changed distribution of bounding box shapes. The code will be made publicly available.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03797](http://arxiv.org/abs/1904.03797)

##### PDF
[http://arxiv.org/pdf/1904.03797](http://arxiv.org/pdf/1904.03797)

