---
layout: post
title: "Non-iterative rigid 2D/3D point-set registration using semidefinite programming"
date: 2016-04-06 04:51:33
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Yuehaw Khoo, Ankur Kapoor
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a convex programming framework for pose estimation in 2D/3D point-set registration with unknown point correspondences. We give two mixed-integer nonlinear program (MINP) formulations of the 2D/3D registration problem when there are multiple 2D images, and propose convex relaxations for both of the MINPs to semidefinite programs (SDP) that can be solved efficiently by interior point methods. Our approach to the 2D/3D registration problem is non-iterative in nature as we jointly solve for pose and correspondence. Furthermore, these convex programs can readily incorporate feature descriptors of points to enhance registration results. We prove that the convex programs exactly recover the solution to the original nonconvex 2D/3D registration problem under noiseless condition. We apply these formulations to the registration of 3D models of coronary vessels to their 2D projections obtained from multiple intra-operative fluoroscopic images. For this application, we experimentally corroborate the exact recovery property in the absence of noise and further demonstrate robustness of the convex programs in the presence of noise.

##### Abstract (translated by Google)
我们描述了一个用于未知点对应的二维/三维点集注册姿态估计的凸规划框架。当存在多个二维图像时，我们给出了二维/三维配准问题的两个混合整数非线性规划（MINP）公式，并提出了两个MINP到半定规划（SDP）的凸松弛算法，可以通过内点法。当我们联合求解姿势和对应关系时，我们的2D / 3D配准问题的方法本质上是非迭代的。而且，这些凸面程序可以容易地结合点的特征描述符来增强注册结果。我们证明了在无噪声情况下，凸函数可以准确地恢复原始非凸2D / 3D配准问题的解。我们将这些公式应用于从多个手术中透视图像获得的二维投影的冠状血管3D模型的配准。对于这个应用程序，我们通过实验证实了在没有噪声的情况下的精确恢复特性，并进一步证明了存在噪声的情况下凸函数的鲁棒性。

##### URL
[https://arxiv.org/abs/1501.00630](https://arxiv.org/abs/1501.00630)

##### PDF
[https://arxiv.org/pdf/1501.00630](https://arxiv.org/pdf/1501.00630)

