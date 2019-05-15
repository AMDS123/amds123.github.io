---
layout: post
title: "LiDAR-Camera Calibration under Arbitrary Configurations: Observability and Methods"
date: 2019-05-14 03:02:25
categories: arXiv_RO
tags: arXiv_RO Optimization
author: Bo Fu, Yue Wang, Xiaqing Ding, Yanmei Jiao, Li Tang, Rong Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
LiDAR-camera calibration is a precondition for many heterogeneous systems that fuse data from LiDAR and camera. However, the constraint from common field of view and the requirement for strict time synchronization make the calibration a challenging problem. In this paper, we propose a novel LiDAR-camera calibration method aiming to eliminate these two constraints. Specifically, we capture a scan of 3D LiDAR when both the environment and the sensors are stationary, then move the camera to reconstruct the 3D environment using the sequentially obtained images. Finally, we align 3D visual points to the laser scan based on tightly couple graph optimization method to calculate the extrinsic parameters between LiDAR and camera. Under this design, the configuration of these two sensors are free from the common field of view constraint owing to the extended view from the moving camera. And we also eliminate the requirement for strict time synchronization as we only use the single scan of laser data when the sensors are stationary. We theoretically derive the conditions of minimal observability for our method and prove that the accuracy of calibration is improved by collecting more observations from multiple scattered calibration targets. We validate our method on both simulation platform and real-world datasets. Experiments show that our method achieves higher accuracy than other comparable methods, which is in accordance with our theoretical analysis. In addition, the proposed method is beneficial to not only plane measurement error based chessboard, but also other point measurement error based calibration targets, such as boxes and polygonal boards.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.06141](http://arxiv.org/abs/1903.06141)

##### PDF
[http://arxiv.org/pdf/1903.06141](http://arxiv.org/pdf/1903.06141)

