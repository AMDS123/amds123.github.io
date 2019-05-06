---
layout: post
title: "ME R-CNN: Multi-Expert R-CNN for Object Detection"
date: 2017-12-01 15:13:19
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Hyungtae Lee, Sungmin Eum, Heesung Kwon
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce Multi-Expert Region-based CNN (ME R-CNN) which is equipped with multiple experts and built on top of the R-CNN framework known to be one of the state-of-the-art object detection methods. ME R-CNN focuses in better capturing the appearance variations caused by different shapes, poses, and viewing angles. The proposed approach consists of three experts each responsible for objects with particular shapes: horizontally elongated, square-like, and vertically elongated. On top of using selective search which provides a compact, yet effective set of region of interests (RoIs) for object detection, we augmented the set by also employing the exhaustive search for training only. Incorporating the exhaustive search can provide complementary advantages: i) it captures the multitude of neighboring RoIs missed by the selective search, and thus ii) provide significantly larger amount of training examples. We show that the ME R-CNN architecture provides considerable performance increase over the baselines on PASCAL VOC 07, 12, and MS COCO datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1704.01069](https://arxiv.org/abs/1704.01069)

##### PDF
[https://arxiv.org/pdf/1704.01069](https://arxiv.org/pdf/1704.01069)

