---
layout: post
title: "Optimizing Video Object Detection via a Scale-Time Lattice"
date: 2018-04-16 01:52:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse CNN Detection Relation
author: Kai Chen, Jiaqi Wang, Shuo Yang, Xingcheng Zhang, Yuanjun Xiong, Chen Change Loy, Dahua Lin
mathjax: true
---

* content
{:toc}

##### Abstract
High-performance object detection relies on expensive convolutional networks to compute features, often leading to significant challenges in applications, e.g. those that require detecting objects from video streams in real time. The key to this problem is to trade accuracy for efficiency in an effective way, i.e. reducing the computing cost while maintaining competitive performance. To seek a good balance, previous efforts usually focus on optimizing the model architectures. This paper explores an alternative approach, that is, to reallocate the computation over a scale-time space. The basic idea is to perform expensive detection sparsely and propagate the results across both scales and time with substantially cheaper networks, by exploiting the strong correlations among them. Specifically, we present a unified framework that integrates detection, temporal propagation, and across-scale refinement on a Scale-Time Lattice. On this framework, one can explore various strategies to balance performance and cost. Taking advantage of this flexibility, we further develop an adaptive scheme with the detector invoked on demand and thus obtain improved tradeoff. On ImageNet VID dataset, the proposed method can achieve a competitive mAP 79.6% at 20 fps, or 79.0% at 62 fps as a performance/speed tradeoff.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1804.05472](https://arxiv.org/abs/1804.05472)

##### PDF
[https://arxiv.org/pdf/1804.05472](https://arxiv.org/pdf/1804.05472)

