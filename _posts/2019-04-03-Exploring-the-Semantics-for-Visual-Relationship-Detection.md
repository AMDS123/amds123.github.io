---
layout: post
title: "Exploring the Semantics for Visual Relationship Detection"
date: 2019-04-03 16:59:49
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection Relation
author: Wentong Liao, Cuiling Lan, Wenjun Zeng, Michael Ying Yang, Bodo Rosenhahn
mathjax: true
---

* content
{:toc}

##### Abstract
Scene graph construction / visual relationship detection from an image aims to give a precise structural description of the objects (nodes) and their relationships (edges). The mutual promotion of object detection and relationship detection is important for enhancing their individual performance. In this work, we propose a new framework, called semantics guided graph relation neural network (SGRN), for effective visual relationship detection. First, to boost the object detection accuracy, we introduce a source-target class cognoscitive transformation that transforms the features of the co-occurent objects to the target object domain to refine the visual features. Similarly, source-target cognoscitive transformations are used to refine features of objects from features of relations, and vice versa. Second, to boost the relation detection accuracy, besides the visual features of the paired objects, we embed the class probability of the object and subject separately to provide high level semantic information. In addition, to reduce the search space of relationships, we design a semantics-aware relationship filter to exclude those object pairs that have no relation. We evaluate our approach on the Visual Genome dataset and it achieves the state-of-the-art performance for visual relationship detection. Additionally, Our approach also significantly improves the object detection performance (i.e. 4.2\% in mAP accuracy).

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1904.02104](https://arxiv.org/abs/1904.02104)

##### PDF
[https://arxiv.org/pdf/1904.02104](https://arxiv.org/pdf/1904.02104)

