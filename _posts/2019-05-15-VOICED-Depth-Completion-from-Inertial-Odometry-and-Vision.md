---
layout: post
title: "VOICED: Depth Completion from Inertial Odometry and Vision"
date: 2019-05-15 03:47:18
categories: arXiv_AI
tags: arXiv_AI Sparse
author: Alex Wong, Xiaohan Fei, Stefano Soatto
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a method to infer dense depth from camera motion and sparse depth as estimated using a visual-inertial odometry system. Unlike other scenarios using point clouds from lidar or structured light sensors, we have few hundreds to few thousand points, insufficient to inform the topology of the scene. Our method first constructs a piecewise planar scaffolding of the scene, and then uses it to infer dense depth using the image along with the sparse points. We use a predictive cross-modal criterion, akin to `self-supervision,' measuring photometric consistency across time, forward-backward pose consistency, and geometric compatibility with the sparse point cloud. We also launch the first visual-inertial + depth dataset, which we hope will foster additional exploration into combining the complementary strengths of visual and inertial sensors. To compare our method to prior work, we adopt the unsupervised KITTI depth completion benchmark, and show state-of-the-art performance on it.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.08616](http://arxiv.org/abs/1905.08616)

##### PDF
[http://arxiv.org/pdf/1905.08616](http://arxiv.org/pdf/1905.08616)

