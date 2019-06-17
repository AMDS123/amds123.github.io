---
layout: post
title: "Can generalised relative pose estimation solve sparse 3D registration?"
date: 2019-06-13 18:41:27
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation
author: Siddhant Ranade, Xin Yu, Shantnu Kakkar, Pedro Miraldo, Srikumar Ramalingam
mathjax: true
---

* content
{:toc}

##### Abstract
Popular 3D scan registration projects, such as Stanford digital Michelangelo or KinectFusion, exploit the high-resolution sensor data for scan alignment. It is particularly challenging to solve the registration of sparse 3D scans in the absence of RGB components. In this case, we can not establish point correspondences since the same 3D point cannot be captured in two successive scans. In contrast to correspondence based methods, we take a different viewpoint and formulate the sparse 3D registration problem based on the constraints from the intersection of line segments from adjacent scans. We obtain the line segments by modeling every horizontal and vertical scan-line as piece-wise linear segments. We propose a new alternating projection algorithm for solving the scan alignment problem using line intersection constraints. We develop two new minimal solvers for scan alignment in the presence of plane correspondences: 1) 3 line intersections and 1 plane correspondence, and 2) 1 line intersection and 2 plane correspondences. We outperform other competing methods on Kinect and LiDAR datasets.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1906.05888](https://arxiv.org/abs/1906.05888)

##### PDF
[https://arxiv.org/pdf/1906.05888](https://arxiv.org/pdf/1906.05888)

