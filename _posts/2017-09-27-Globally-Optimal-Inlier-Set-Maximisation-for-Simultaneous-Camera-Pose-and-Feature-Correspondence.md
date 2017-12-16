---
layout: post
title: "Globally-Optimal Inlier Set Maximisation for Simultaneous Camera Pose and Feature Correspondence"
date: 2017-09-27 08:36:07
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Dylan Campbell, Lars Petersson, Laurent Kneip, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Estimating the 6-DoF pose of a camera from a single image relative to a pre-computed 3D point-set is an important task for many computer vision applications. Perspective-n-Point (PnP) solvers are routinely used for camera pose estimation, provided that a good quality set of 2D-3D feature correspondences are known beforehand. However, finding optimal correspondences between 2D key-points and a 3D point-set is non-trivial, especially when only geometric (position) information is known. Existing approaches to the simultaneous pose and correspondence problem use local optimisation, and are therefore unlikely to find the optimal solution without a good pose initialisation, or introduce restrictive assumptions. Since a large proportion of outliers are common for this problem, we instead propose a globally-optimal inlier set cardinality maximisation approach which jointly estimates optimal camera pose and optimal correspondences. Our approach employs branch-and-bound to search the 6D space of camera poses, guaranteeing global optimality without requiring a pose prior. The geometry of SE(3) is used to find novel upper and lower bounds for the number of inliers and local optimisation is integrated to accelerate convergence. The evaluation empirically supports the optimality proof and shows that the method performs much more robustly than existing approaches, including on a large-scale outdoor data-set.

##### Abstract (translated by Google)
从单个图像相对于预先计算的3D点集估计相机的6-DoF姿态对于许多计算机视觉应用来说是重要的任务。透视n点（PnP）解算器通常用于相机姿态估计，只要预先知道一组高质量的2D-3D特征对应关系即可。但是，找到二维关键点和一个三维点集之间的最佳对应关系并不重要，特别是在仅知道几何（位置）信息的情况下。同时姿态和对应问题的现有方法使用局部优化，因此不可能在没有良好的姿态初始化的情况下找到最优解，或者引入限制性假设。由于这个问题很大一部分异常值是常见的，我们改为提出一个全局最优的内点集合基数最大化方法，联合估计最佳相机姿态和最佳对应关系。我们的方法采用分支定界搜索摄像机姿态的6D空间，保证全局最优性，而不需要先前的姿势。 SE（3）的几何结构被用来寻找新颖的上下界数量和局部优化被整合，以加速收敛。评估经验支持最优性证明，并表明该方法比现有方法，包括在大型户外数据集上执行得更为稳健。

##### URL
[https://arxiv.org/abs/1709.09384](https://arxiv.org/abs/1709.09384)

##### PDF
[https://arxiv.org/pdf/1709.09384](https://arxiv.org/pdf/1709.09384)

