---
layout: post
title: "SeFM: A Sequential Feature Point Matching Algorithm for Object 3D Reconstruction"
date: 2018-12-07 06:13:07
categories: arXiv_CV
tags: arXiv_CV
author: Zhihao Fang, Xutao Guo, Xuemin Zhu, Ruixin Zhou, He Ma
mathjax: true
---

* content
{:toc}

##### Abstract
3D reconstruction is a fundamental issue in many applications and the feature point matching problem is a key step while reconstructing target objects. Conventional algorithms can only find a small number of feature points from two images which is quite insufficient for reconstruction. To overcome this problem, we propose SeFM a sequential feature point matching algorithm. We first utilize the epipolar geometry to find the epipole of each image. Rotating along the epipole, we generate a set of the epipolar lines and reserve those intersecting with the input image. Next, a rough matching phase, followed by a dense matching phase, is applied to find the matching dot-pairs using dynamic programming. Furthermore, we also remove wrong matching dot-pairs by calculating the validity. Experimental results illustrate that SeFM can achieve around 1,000 to 10,000 times matching dot-pairs, depending on individual image, compared to conventional algorithms and the object reconstruction with only two images is semantically visible. Moreover, it outperforms conventional algorithms, such as SIFT and SURF, regarding precision and recall.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.02925](http://arxiv.org/abs/1812.02925)

##### PDF
[http://arxiv.org/pdf/1812.02925](http://arxiv.org/pdf/1812.02925)

