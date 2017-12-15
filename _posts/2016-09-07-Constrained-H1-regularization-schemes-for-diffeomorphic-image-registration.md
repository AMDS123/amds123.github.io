---
layout: post
title: "Constrained $H^1$-regularization schemes for diffeomorphic image registration"
date: 2016-09-07 20:08:32
categories: arXiv_CV
tags: arXiv_CV Regularization Optimization
author: Andreas Mang, George Biros
mathjax: true
---

* content
{:toc}

##### Abstract
We propose regularization schemes for deformable registration and efficient algorithms for their numerical approximation. We treat image registration as a variational optimal control problem. The deformation map is parametrized by its velocity. Tikhonov regularization ensures well-posedness. Our scheme augments standard smoothness regularization operators based on $H^1$- and $H^2$-seminorms with a constraint on the divergence of the velocity field, which resembles variational formulations for Stokes incompressible flows. In our formulation, we invert for a stationary velocity field and a mass source map. This allows us to explicitly control the compressibility of the deformation map and by that the determinant of the deformation gradient. We also introduce a new regularization scheme that allows us to control shear. We use a globalized, preconditioned, matrix-free, reduced space (Gauss--)Newton--Krylov scheme for numerical optimization. We exploit variable elimination techniques to reduce the number of unknowns of our system; we only iterate on the reduced space of the velocity field. Our current implementation is limited to the two-dimensional case. The numerical experiments demonstrate that we can control the determinant of the deformation gradient without compromising registration quality. This additional control allows us to avoid oversmoothing of the deformation map. We also demonstrate that we can promote or penalize shear while controlling the determinant of the deformation gradient.

##### Abstract (translated by Google)
我们提出可变形配准的正则化方案和数值逼近的高效算法。我们将图像配准视为变分最优控制问题。变形图由其速度进行参数化。吉洪诺夫规则化确保良好的姿态。我们的方案增加了基于$ H ^ 1 $和$ H ^ 2 $ -seminorms的标准光滑正则化算子，这个算子对速度场的散度有一个约束，类似于斯托克斯不可压缩流的变分公式。在我们的公式中，我们倒置了一个平稳速度场和一个质量源图。这使我们能够明确地控制变形图的可压缩性，并由此确定变形梯度的行列式。我们还引入了一个新的正则化方案，使我们能够控制剪切。我们使用全球化，预处理，无矩阵，减少空间（高斯 - ）牛顿 - 克雷洛夫方案进行数值优化。我们利用可变消除技术来减少我们系统的未知数。我们只是在速度场的缩小的空间上进行迭代。我们目前的实施仅限于二维情况。数值实验表明，我们可以控制变形梯度的决定因素，而不会影响配准质量。这个额外的控制允许我们避免变形图的过度平滑。我们还证明，我们可以在控制变形梯度的行列式的同时促进或惩罚剪切力。

##### URL
[https://arxiv.org/abs/1503.00757](https://arxiv.org/abs/1503.00757)

##### PDF
[https://arxiv.org/pdf/1503.00757](https://arxiv.org/pdf/1503.00757)

