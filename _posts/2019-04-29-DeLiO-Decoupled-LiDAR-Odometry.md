---
layout: post
title: "DeLiO: Decoupled LiDAR Odometry"
date: 2019-04-29 12:54:22
categories: arXiv_CV
tags: arXiv_CV Face Tracking
author: Queens Maria Thomas, Oliver Wasenm&#xfc;ller, Didier Stricker
mathjax: true
---

* content
{:toc}

##### Abstract
Most LiDAR odometry algorithms estimate the transformation between two consecutive frames by estimating the rotation and translation in an intervening fashion. In this paper, we propose our Decoupled LiDAR Odometry (DeLiO), which -- for the first time -- decouples the rotation estimation completely from the translation estimation. In particular, the rotation is estimated by extracting the surface normals from the input point clouds and tracking their characteristic pattern on a unit sphere. Using this rotation the point clouds are unrotated so that the underlying transformation is pure translation, which can be easily estimated using a line cloud approach. An evaluation is performed on the KITTI dataset and the results are compared against state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.12667](http://arxiv.org/abs/1904.12667)

##### PDF
[http://arxiv.org/pdf/1904.12667](http://arxiv.org/pdf/1904.12667)

