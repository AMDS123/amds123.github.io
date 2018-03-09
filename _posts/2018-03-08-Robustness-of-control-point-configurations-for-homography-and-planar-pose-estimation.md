---
layout: post
title: "Robustness of control point configurations for homography and planar pose estimation"
date: 2018-03-08 10:14:41
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Raul Acuna, Volker Willert
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we investigate the influence of the spatial configuration of a number of $n \geq 4$ control points on the accuracy and robustness of space resection methods, e.g. used by a fiducial marker for pose estimation. We find robust configurations of control points by minimizing the first order perturbed solution of the DLT algorithm which is equivalent to minimizing the condition number of the data matrix. An empirical statistical evaluation is presented verifying that these optimized control point configurations not only increase the performance of the DLT homography estimation but also improve the performance of planar pose estimation methods like IPPE and EPnP, including the iterative minimization of the reprojection error which is the most accurate algorithm. We provide the characteristics of stable control point configurations for real-world noisy camera data that are practically independent on the camera pose and form certain symmetric patterns dependent on the number of points. Finally, we present a comparison of optimized configuration versus the number of control points.

##### Abstract (translated by Google)
在本文中，我们研究了许多$ n \ geq 4 $控制点的空间配置对空间切除方法的准确性和鲁棒性的影响，例如，由基准标记用于姿态估计。我们通过最小化DLT算法的一阶扰动解而找到控制点的鲁棒配置，这相当于使数据矩阵的条件数最小化。验证了这些优化的控制点配置不仅提高了DLT单应矩阵估计的性能，而且提高了IPPE和EPnP等平面位姿估计方法的性能，包括迭代最小化重投影误差准确的算法。我们为实际噪声摄像机数据提供稳定控制点配置的特性，这些数据实际上独立于摄像机姿态，并根据点数形成某些对称图形。最后，我们介绍一下优化配置与控制点数量的比较。

##### URL
[http://arxiv.org/abs/1803.03025](http://arxiv.org/abs/1803.03025)

##### PDF
[http://arxiv.org/pdf/1803.03025](http://arxiv.org/pdf/1803.03025)

