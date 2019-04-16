---
layout: post
title: "Visual-Inertial Object Detection and Mapping"
date: 2018-10-23 21:43:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Sparse Detection
author: Xiaohan Fei, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method to populate an unknown environment with models of previously seen objects, placed in a Euclidean reference frame that is inferred causally and on-line using monocular video along with inertial sensors. The system we implement returns a sparse point cloud for the regions of the scene that are visible but not recognized as a previously seen object, and a detailed object model and its pose in the Euclidean frame otherwise. The system includes bottom-up and top-down components, whereby deep networks trained for detection provide likelihood scores for object hypotheses provided by a nonlinear filter, whose state serves as memory. Additional networks provide likelihood scores for edges, which complements detection networks trained to be invariant to small deformations. We test our algorithm on existing datasets, and also introduce the VISMA dataset, that provides ground truth pose, point-cloud map, and object models, along with time-stamped inertial measurements.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1806.08498](https://arxiv.org/abs/1806.08498)

##### PDF
[https://arxiv.org/pdf/1806.08498](https://arxiv.org/pdf/1806.08498)

