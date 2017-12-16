---
layout: post
title: "LED-based Photometric Stereo: Modeling, Calibration and Numerical Solution"
date: 2017-09-04 17:38:30
categories: arXiv_CV
tags: arXiv_CV
author: Yvain Quéau, Bastien Durix, Tao Wu, Daniel Cremers, François Lauze, Jean-Denis Durou
mathjax: true
---

* content
{:toc}

##### Abstract
We conduct a thorough study of photometric stereo under nearby point light source illumination, from modeling to numerical solution, through calibration. In the classical formulation of photometric stereo, the luminous fluxes are assumed to be directional, which is very difficult to achieve in practice. Rather, we use light-emitting diodes (LEDs) to illuminate the scene to reconstruct. Such point light sources are very convenient to use, yet they yield a more complex photometric stereo model which is arduous to solve. We first derive in a physically sound manner this model, and show how to calibrate its parameters. Then, we discuss two state-of-the-art numerical solutions. The first one alternatingly estimates the albedo and the normals, and then integrates the normals into a depth map. It is shown empirically to be independent from the initialization, but convergence of this sequential approach is not established. The second one directly recovers the depth, by formulating photometric stereo as a system of PDEs which are partially linearized using image ratios. Although the sequential approach is avoided, initialization matters a lot and convergence is not established either. Therefore, we introduce a provably convergent alternating reweighted least-squares scheme for solving the original system of PDEs, without resorting to image ratios for linearization. Finally, we extend this study to the case of RGB images.

##### Abstract (translated by Google)
在附近点光源照明下，从建模到数值解，通过标定，我们对光度立体进行了深入的研究。在光度立体的经典表述中，光通量假定为定向的，这在实践中是非常难以实现的。相反，我们使用发光二极管（LED）照亮现场重建。这种点光源使用起来非常方便，但却产生了一个更复杂的光度立体模型，而且这个模型很难解决。我们首先从物理上推导出这个模型，并展示如何校准它的参数。然后，我们讨论两个最先进的数值解决方案。第一个交替估计反照率和法线，然后将法线积分成深度图。经验表明，它与初始化无关，但是这种顺序方法的收敛性还没有建立。第二个直接恢复的深度，通过制定光度立体作为一个PDE系统的部分线性化使用图像比例。尽管避免了顺序方法，但初始化很重要，收敛也不成立。因此，我们引入了一种可证明的交替重加权最小二乘方法来求解原始偏微分方程组，而不用求出图像比率的线性化。最后，我们将这个研究扩展到RGB图像的情况。

##### URL
[https://arxiv.org/abs/1707.01018](https://arxiv.org/abs/1707.01018)

##### PDF
[https://arxiv.org/pdf/1707.01018](https://arxiv.org/pdf/1707.01018)

