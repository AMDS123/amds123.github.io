---
layout: post
title: "A Continuous Optimization Approach for Efficient and Accurate Scene Flow"
date: 2016-07-27 07:07:07
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Zhaoyang Lv, Chris Beall, Pablo F. Alcantarilla, Fuxin Li, Zsolt Kira, Frank Dellaert
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a continuous optimization method for solving dense 3D scene flow problems from stereo imagery. As in recent work, we represent the dynamic 3D scene as a collection of rigidly moving planar segments. The scene flow problem then becomes the joint estimation of pixel-to-segment assignment, 3D position, normal vector and rigid motion parameters for each segment, leading to a complex and expensive discrete-continuous optimization problem. In contrast, we propose a purely continuous formulation which can be solved more efficiently. Using a fine superpixel segmentation that is fixed a-priori, we propose a factor graph formulation that decomposes the problem into photometric, geometric, and smoothing constraints. We initialize the solution with a novel, high-quality initialization method, then independently refine the geometry and motion of the scene, and finally perform a global non-linear refinement using Levenberg-Marquardt. We evaluate our method in the challenging KITTI Scene Flow benchmark, ranking in third position, while being 3 to 30 times faster than the top competitors.

##### Abstract (translated by Google)
我们提出了一个连续的优化方法来解决从立体图像密集的三维场景流问题。就像在最近的工作中一样，我们将动态的3D场景表示为一系列刚性移动的平面片段。场景流问题变成了每个分段的像素到像素分配，3D位置，法向量和刚体运动参数的联合估计，导致了一个复杂而昂贵的离散连续优化问题。相比之下，我们提出了一个可以更有效地解决的纯粹连续的配方。使用先验固定的精细超像素分割，我们提出了一个因子图形式，将问题分解成光度，几何和平滑约束。我们用一种新颖的，高质量的初始化方法初始化解，然后独立地完善场景的几何和运动，最后用Levenberg-Marquardt进行全局非线性精化。我们在具有挑战性的KITTI Scene Flow基准测试中评估我们的方法，排名第三，比顶级竞争对手快3到30倍。

##### URL
[https://arxiv.org/abs/1607.07983](https://arxiv.org/abs/1607.07983)

##### PDF
[https://arxiv.org/pdf/1607.07983](https://arxiv.org/pdf/1607.07983)

