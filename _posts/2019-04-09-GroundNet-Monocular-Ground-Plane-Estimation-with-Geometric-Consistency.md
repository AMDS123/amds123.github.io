---
layout: post
title: "GroundNet: Monocular Ground Plane Estimation with Geometric Consistency"
date: 2019-04-09 23:04:16
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Prediction Detection Relation
author: Yunze Man, Xinshuo Weng, Xi Li, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on the problem of estimating the 3D orientation of the ground plane from a single image (monocular vision). We formulate the problem as an inter-mingled multi-task prediction problem by jointly optimizing for pixel-wise surface normal direction, ground plane segmentation, and depth estimates. Specifically, our proposed model -- GroundNet -- first estimates the depth and surface normal in two separate streams. Then two ground plane normals can be computed deterministically from the estimated depth and surface normal. To leverage the geometric correlation between depth and normal, we propose to add a consistency loss on top of the computed ground normals. In addition, a ground segmentation stream is used to isolate the ground regions so that we can selectively back-propagate parameter updates through only the ground regions in the image. Our method achieves the top-ranked performance on the task of the ground plane normal estimation and horizon line detection on the real-world outdoor datasets of ApolloScape and KITTI, improving the previous state-of-the-art relatively by up to 17.7%.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07222](http://arxiv.org/abs/1811.07222)

##### PDF
[http://arxiv.org/pdf/1811.07222](http://arxiv.org/pdf/1811.07222)

