---
layout: post
title: "Semi-Semantic Line-Cluster Assisted Monocular SLAM for Indoor Environments"
date: 2018-11-05 10:31:40
categories: arXiv_CV
tags: arXiv_CV Knowledge SLAM
author: Ting Sun, Dezhen Song, Dit-Yan Yeung, Ming Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel method to reduce the scale drift for indoor monocular simultaneous localization and mapping (SLAM). We leverage the prior knowledge that in the indoor environment, the line segments form tight clusters, e.g. many door frames in a straight corridor are of the same shape, size and orientation, so the same edges of these door frames form a tight line segment cluster. We implement our method in the popular ORB-SLAM2, which also serves as our baseline. In the front end we detect the line segments in each frame and incrementally cluster them in the 3D space. In the back end, we optimize the map imposing the constraint that the line segments of the same cluster should be the same. Experimental results show that our proposed method successfully reduces the scale drift for indoor monocular SLAM.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.01592](http://arxiv.org/abs/1811.01592)

##### PDF
[http://arxiv.org/pdf/1811.01592](http://arxiv.org/pdf/1811.01592)

