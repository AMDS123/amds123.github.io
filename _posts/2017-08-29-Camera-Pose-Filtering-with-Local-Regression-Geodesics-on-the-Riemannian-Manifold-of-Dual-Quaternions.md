---
layout: post
title: "Camera Pose Filtering with Local Regression Geodesics on the Riemannian Manifold of Dual Quaternions"
date: 2017-08-29 16:28:16
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Benjamin Busam, Tolga Birdal, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
Time-varying, smooth trajectory estimation is of great interest to the vision community for accurate and well behaving 3D systems. In this paper, we propose a novel principal component local regression filter acting directly on the Riemannian manifold of unit dual quaternions $\mathbb{D} \mathbb{H}_1$. We use a numerically stable Lie algebra of the dual quaternions together with $\exp$ and $\log$ operators to locally linearize the 6D pose space. Unlike state of the art path smoothing methods which either operate on $SO\left(3\right)$ of rotation matrices or the hypersphere $\mathbb{H}_1$ of quaternions, we treat the orientation and translation jointly on the dual quaternion quadric in the 7-dimensional real projective space $\mathbb{R}\mathbb{P}^7$. We provide an outlier-robust IRLS algorithm for generic pose filtering exploiting this manifold structure. Besides our theoretical analysis, our experiments on synthetic and real data show the practical advantages of the manifold aware filtering on pose tracking and smoothing.

##### Abstract (translated by Google)
时变，平滑的轨迹估计对于视觉社区对于准确和行为良好的3D系统非常感兴趣。在本文中，我们提出了一种新的主​​成分局部回归滤波器直接作用于单位双四元数黎曼流形$ \ mathbb {D} \ mathbb {H} _1 $。我们使用双四元数的数值稳定李代数和$ \ exp $和$ \ log $运算符来局部线性化6D姿态空间。与在四元数的$ SO \ left（3 \ right）$或四元数的超球面$ \ mathbb {H} _1 $上运算的现有技术路径平滑方法不同，我们在双四元数在七维实射影空间$ \ mathbb {R} \ mathbb {P} ^ 7 $。我们提供了异常强大的IRLS算法，用于利用这种流形结构的通用姿态滤波。除了我们的理论分析，我们在合成和实际数据上的实验显示了流形意识滤波对姿态跟踪和平滑的实际优势。

##### URL
[https://arxiv.org/abs/1704.07072](https://arxiv.org/abs/1704.07072)

##### PDF
[https://arxiv.org/pdf/1704.07072](https://arxiv.org/pdf/1704.07072)

