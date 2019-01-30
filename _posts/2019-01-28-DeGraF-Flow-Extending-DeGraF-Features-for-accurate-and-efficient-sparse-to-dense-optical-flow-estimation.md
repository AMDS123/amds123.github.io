---
layout: post
title: "DeGraF-Flow: Extending DeGraF Features for accurate and efficient sparse-to-dense optical flow estimation"
date: 2019-01-28 19:55:40
categories: arXiv_AI
tags: arXiv_AI Salient Object_Detection Sparse Tracking Detection
author: Felix Stephenson, Toby Breckon, Ioannis Katramados
mathjax: true
---

* content
{:toc}

##### Abstract
Modern optical flow methods make use of salient scene feature points detected and matched within the scene as a basis for sparse-to-dense optical flow estimation. Current feature detectors however either give sparse, non uniform point clouds (resulting in flow inaccuracies) or lack the efficiency for frame-rate real-time applications. In this work we use the novel Dense Gradient Based Features (DeGraF) as the input to a sparse-to-dense optical flow scheme. This consists of three stages: 1) efficient detection of uniformly distributed Dense Gradient Based Features (DeGraF); 2) feature tracking via robust local optical flow; and 3) edge preserving flow interpolation to recover overall dense optical flow. The tunable density and uniformity of DeGraF features yield superior dense optical flow estimation compared to other popular feature detectors within this three stage pipeline. Furthermore, the comparable speed of feature detection also lends itself well to the aim of real-time optical flow recovery. Evaluation on established real-world benchmark datasets show test performance in an autonomous vehicle setting where DeGraF-Flow shows promising results in terms of accuracy with competitive computational efficiency among non-GPU based methods, including a marked increase in speed over the conceptually similar EpicFlow approach.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.09971](http://arxiv.org/abs/1901.09971)

##### PDF
[http://arxiv.org/pdf/1901.09971](http://arxiv.org/pdf/1901.09971)

