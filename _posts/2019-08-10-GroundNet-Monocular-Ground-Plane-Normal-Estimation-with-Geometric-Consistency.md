---
layout: post
title: "GroundNet: Monocular Ground Plane Normal Estimation with Geometric Consistency"
date: 2019-08-10 01:59:14
categories: arXiv_CV
tags: arXiv_CV Segmentation Face Prediction Detection Relation
author: Yunze Man, Xinshuo Weng, Xi Li, Kris Kitani
mathjax: true
---

* content
{:toc}

##### Abstract
We focus on estimating the 3D orientation of the ground plane from a single image. We formulate the problem as an inter-mingled multi-task prediction problem by jointly optimizing for pixel-wise surface normal direction, ground plane segmentation, and depth estimates. Specifically, our proposed model, GroundNet, first estimates the depth and surface normal in two separate streams, from which two ground plane normals are then computed deterministically. To leverage the geometric correlation between depth and normal, we propose to add a consistency loss on top of the computed ground plane normals. In addition, a ground segmentation stream is used to isolate the ground regions so that we can selectively back-propagate parameter updates through only the ground regions in the image. Our method achieves the top-ranked performance on ground plane normal estimation and horizon line detection on the real-world outdoor datasets of ApolloScape and KITTI, improving the performance of previous art by up to 17.7% relatively.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.07222](http://arxiv.org/abs/1811.07222)

##### PDF
[http://arxiv.org/pdf/1811.07222](http://arxiv.org/pdf/1811.07222)

