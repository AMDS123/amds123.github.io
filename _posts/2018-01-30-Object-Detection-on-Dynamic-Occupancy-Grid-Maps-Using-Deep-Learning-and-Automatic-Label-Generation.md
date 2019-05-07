---
layout: post
title: "Object Detection on Dynamic Occupancy Grid Maps Using Deep Learning and Automatic Label Generation"
date: 2018-01-30 08:18:31
categories: arXiv_CV
tags: arXiv_CV Object_Detection Pose_Estimation CNN Deep_Learning Detection
author: Stefan Hoermann, Philipp Henzler, Martin Bach, Klaus Dietmayer
mathjax: true
---

* content
{:toc}

##### Abstract
We tackle the problem of object detection and pose estimation in a shared space downtown environment. For perception multiple laser scanners with 360° coverage were fused in a dynamic occupancy grid map (DOGMa). A single-stage deep convolutional neural network is trained to provide object hypotheses comprising of shape, position, orientation and an existence score from a single input DOGMa. Furthermore, an algorithm for offline object extraction was developed to automatically label several hours of training data. The algorithm is based on a two-pass trajectory extraction, forward and backward in time. Typical for engineered algorithms, the automatic label generation suffers from misdetections, which makes hard negative mining impractical. Therefore, we propose a loss function counteracting the high imbalance between mostly static background and extremely rare dynamic grid cells. Experiments indicate, that the trained network has good generalization capabilities since it detects objects occasionally lost by the label algorithm. Evaluation reaches an average precision (AP) of 75.9%

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1802.02202](https://arxiv.org/abs/1802.02202)

##### PDF
[https://arxiv.org/pdf/1802.02202](https://arxiv.org/pdf/1802.02202)

