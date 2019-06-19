---
layout: post
title: "The Alignment of the Spheres: Globally-Optimal Spherical Mixture Alignment for Camera Pose Estimation"
date: 2019-06-18 09:05:54
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Optimization
author: Dylan Campbell, Lars Petersson, Laurent Kneip, Hongdong Li, Stephen Gould
mathjax: true
---

* content
{:toc}

##### Abstract
Determining the position and orientation of a calibrated camera from a single image with respect to a 3D model is an essential task for many applications. When 2D-3D correspondences can be obtained reliably, perspective-n-point solvers can be used to recover the camera pose. However, without the pose it is non-trivial to find cross-modality correspondences between 2D images and 3D models, particularly when the latter only contains geometric information. Consequently, the problem becomes one of estimating pose and correspondences jointly. Since outliers and local optima are so prevalent, robust objective functions and global search strategies are desirable. Hence, we cast the problem as a 2D-3D mixture model alignment task and propose the first globally-optimal solution to this formulation under the robust $L_2$ distance between mixture distributions. We search the 6D camera pose space using branch-and-bound, which requires novel bounds, to obviate the need for a pose estimate and guarantee global optimality. To accelerate convergence, we integrate local optimization, implement GPU bound computations, and provide an intuitive way to incorporate side information such as semantic labels. The algorithm is evaluated on challenging synthetic and real datasets, outperforming existing approaches and reliably converging to the global optimum.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01232](http://arxiv.org/abs/1812.01232)

##### PDF
[http://arxiv.org/pdf/1812.01232](http://arxiv.org/pdf/1812.01232)

