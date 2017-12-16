---
layout: post
title: "Proxy Templates for Inverse Compositional Photometric Bundle Adjustment"
date: 2017-04-23 19:42:48
categories: arXiv_CV
tags: arXiv_CV Sparse SLAM
author: Christopher Ham, Simon Lucey, Surya Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in 3D vision have demonstrated the strengths of photometric bundle adjustment. By directly minimizing reprojected pixel errors, instead of geometric reprojection errors, such methods can achieve sub-pixel alignment accuracy in both high and low textured regions. Typically, these problems are solved using a forwards compositional Lucas-Kanade formulation parameterized by 6-DoF rigid camera poses and a depth per point in the structure. For large problems the most CPU-intensive component of the pipeline is the creation and factorization of the Hessian matrix at each iteration. For many warps, the inverse compositional formulation can offer significant speed-ups since the Hessian need only be inverted once. In this paper, we show that an ordinary inverse compositional formulation does not work for warps of this type of parameterization due to ill-conditioning of its partial derivatives. However, we show that it is possible to overcome this limitation by introducing the concept of a proxy template image. We show an order of magnitude improvement in speed, with little effect on quality, going from forwards to inverse compositional in our own photometric bundle adjustment method designed for object-centric structure from motion. This means less processing time for large systems or denser reconstructions under the same real-time constraints. We additionally show that this theory can be readily applied to existing methods by integrating it with the recently released Direct Sparse Odometry SLAM algorithm.

##### Abstract (translated by Google)
3D视觉的最新进展已经证明了光度束调整的优势。通过直接最小化重投影像素误差，而不是几何重投影误差，这样的方法可以实现高和低纹理区域中的亚像素对准精度。典型地，这些问题通过使用由6-DoF刚性相机姿态参数化的前向成分Lucas-Kanade公式和结构中的每个点的深度来解决。对于大型问题，流水线中CPU占用最多的部分是在每次迭代中Hessian矩阵的创建和分解。对于许多经纱来说，由于Hessian只需要翻转一次，逆向成分配方可以提供显着的加速。在本文中，我们表明一个普通的逆组成公式不适用于这种类型参数化的曲线，因为它的偏导数是不适应的。然而，我们表明可以通过引入代理模板图像的概念来克服这个限制。我们在速度上有一个数量级的提高，对质量的影响很小，在我们自己设计的以运动为目标的光束组合调整方法中，从前向到逆向组合。这意味着在相同的实时约束条件下，大型系统的处理时间更少或更密集的重建。我们另外表明，这个理论可以很容易地应用到现有的方法，把它与最近发布的Direct Sparse Odometry SLAM算法结合起来。

##### URL
[https://arxiv.org/abs/1704.06967](https://arxiv.org/abs/1704.06967)

##### PDF
[https://arxiv.org/pdf/1704.06967](https://arxiv.org/pdf/1704.06967)

