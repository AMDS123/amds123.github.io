---
layout: post
title: "Efficient Relative Pose Estimation for Cameras and Generalized Cameras in Case of Known Relative Rotation Angle"
date: 2019-01-31 13:52:50
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Evgeniy Martyushev, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
We propose two minimal solutions to the problem of relative pose estimation of (i) a calibrated camera from four points in two views and (ii) a calibrated generalized camera from five points in two views. In both cases, the relative rotation angle between the views is assumed to be known. In practice, such angle can be derived from the readings of a 3d gyroscope. We represent the rotation part of the motion in terms of unit quaternions in order to construct polynomial equations encoding the epipolar constraints. The Gr\"{o}bner basis technique is then used to efficiently derive the solutions. Our first solver for regular cameras significantly improves the existing state-of-the-art solution. The second solver for generalized cameras is novel. 
 The presented minimal solvers can be used in a hypothesize-and-test architecture such as RANSAC for reliable pose estimation. Experiments on synthetic and real datasets confirm that our algorithms are numerically stable, fast and robust.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.11357](http://arxiv.org/abs/1901.11357)

##### PDF
[http://arxiv.org/pdf/1901.11357](http://arxiv.org/pdf/1901.11357)

