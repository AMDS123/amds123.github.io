---
layout: post
title: "SfMLearner++: Learning Monocular Depth & Ego-Motion using Meaningful Geometric Constraints"
date: 2018-12-20 06:17:37
categories: arXiv_RO
tags: arXiv_RO Sparse Pose_Estimation
author: Vignesh Prasad, Brojeshwar Bhowmick
mathjax: true
---

* content
{:toc}

##### Abstract
Most geometric approaches to monocular Visual Odometry (VO) provide robust pose estimates, but sparse or semi-dense depth estimates. Off late, deep methods have shown good performance in generating dense depths and VO from monocular images by optimizing the photometric consistency between images. Despite being intuitive, a naive photometric loss does not ensure proper pixel correspondences between two views, which is the key factor for accurate depth and relative pose estimations. It is a well known fact that simply minimizing such an error is prone to failures. 
 We propose a method using Epipolar constraints to make the learning more geometrically sound. We use the Essential matrix, obtained using Nister's Five Point Algorithm, for enforcing meaningful geometric constraints on the loss, rather than using it as labels for training. Our method, although simplistic but more geometrically meaningful, using lesser number of parameters, gives a comparable performance to state-of-the-art methods which use complex losses and large networks showing the effectiveness of using epipolar constraints. Such a geometrically constrained learning method performs successfully even in cases where simply minimizing the photometric error would fail.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.08370](http://arxiv.org/abs/1812.08370)

##### PDF
[http://arxiv.org/pdf/1812.08370](http://arxiv.org/pdf/1812.08370)

