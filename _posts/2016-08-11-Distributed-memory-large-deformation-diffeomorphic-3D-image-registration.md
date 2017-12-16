---
layout: post
title: "Distributed-memory large deformation diffeomorphic 3D image registration"
date: 2016-08-11 22:52:27
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Andreas Mang, Amir Gholami, George Biros
mathjax: true
---

* content
{:toc}

##### Abstract
We present a parallel distributed-memory algorithm for large deformation diffeomorphic registration of volumetric images that produces large isochoric deformations (locally volume preserving). Image registration is a key technology in medical image analysis. Our algorithm uses a partial differential equation constrained optimal control formulation. Finding the optimal deformation map requires the solution of a highly nonlinear problem that involves pseudo-differential operators, biharmonic operators, and pure advection operators both forward and back- ward in time. A key issue is the time to solution, which poses the demand for efficient optimization methods as well as an effective utilization of high performance computing resources. To address this problem we use a preconditioned, inexact, Gauss-Newton- Krylov solver. Our algorithm integrates several components: a spectral discretization in space, a semi-Lagrangian formulation in time, analytic adjoints, different regularization functionals (including volume-preserving ones), a spectral preconditioner, a highly optimized distributed Fast Fourier Transform, and a cubic interpolation scheme for the semi-Lagrangian time-stepping. We demonstrate the scalability of our algorithm on images with resolution of up to $1024^3$ on the "Maverick" and "Stampede" systems at the Texas Advanced Computing Center (TACC). The critical problem in the medical imaging application domain is strong scaling, that is, solving registration problems of a moderate size of $256^3$---a typical resolution for medical images. We are able to solve the registration problem for images of this size in less than five seconds on 64 x86 nodes of TACC's "Maverick" system.

##### Abstract (translated by Google)
我们提出了一个并行的分布式记忆算法，用于产生大等容变形（局部容积维持）的体积图像的大变形微分同构配准。图像配准是医学图像分析中的关键技术。我们的算法使用偏微分方程约束最优控制公式。寻找最佳变形图要求解决一个高度非线性问题，包括伪微分算子，双调和算子和纯对流算子的时间向前和向后。一个关键问题是解决问题的时间，这就需要有效的优化方法以及高性能计算资源的有效利用。为了解决这个问题，我们使用一个预处理的，不精确的高斯 - 牛顿 - 克雷洛夫求解器。我们的算法集成了几个组成部分：空间光谱离散化，时间半拉格朗日公式，解析伴随，不同正则化函数（包括体积保留），谱预处理器，高度优化的分布式快速傅里叶变换和三次插值方案为半拉格朗日时间步进。我们在德克萨斯高级计算中心（TACC）的“Maverick”和“Stampede”系统上展示了我们的算法在分辨率高达$ 1024 ^ 3 $的图像上的可伸缩性。医学成像应用领域中的关键问题是强大的缩放，即解决医学图像典型分辨率中等大小的注册问题。在TACC的“Maverick”系统的64个x86节点上，我们能够在不到5秒的时间内解决这个大小的图像的注册问题。

##### URL
[https://arxiv.org/abs/1608.03630](https://arxiv.org/abs/1608.03630)

##### PDF
[https://arxiv.org/pdf/1608.03630](https://arxiv.org/pdf/1608.03630)

