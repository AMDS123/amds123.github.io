---
layout: post
title: "Optimising Spatial and Tonal Data for PDE-based Inpainting"
date: 2015-06-15 12:15:26
categories: arXiv_CV
tags: arXiv_CV Sparse Survey Gradient_Descent
author: Laurent Hoeltgen, Markus Mainberger, Sebastian Hoffmann, Joachim Weickert, Ching Hoo Tang, Simon Setzer, Daniel Johannsen, Frank Neumann, Benjamin Doerr
mathjax: true
---

* content
{:toc}

##### Abstract
Some recent methods for lossy signal and image compression store only a few selected pixels and fill in the missing structures by inpainting with a partial differential equation (PDE). Suitable operators include the Laplacian, the biharmonic operator, and edge-enhancing anisotropic diffusion (EED). The quality of such approaches depends substantially on the selection of the data that is kept. Optimising this data in the domain and codomain gives rise to challenging mathematical problems that shall be addressed in our work. In the 1D case, we prove results that provide insights into the difficulty of this problem, and we give evidence that a splitting into spatial and tonal (i.e. function value) optimisation does hardly deteriorate the results. In the 2D setting, we present generic algorithms that achieve a high reconstruction quality even if the specified data is very sparse. To optimise the spatial data, we use a probabilistic sparsification, followed by a nonlocal pixel exchange that avoids getting trapped in bad local optima. After this spatial optimisation we perform a tonal optimisation that modifies the function values in order to reduce the global reconstruction error. For homogeneous diffusion inpainting, this comes down to a least squares problem for which we prove that it has a unique solution. We demonstrate that it can be found efficiently with a gradient descent approach that is accelerated with fast explicit diffusion (FED) cycles. Our framework allows to specify the desired density of the inpainting mask a priori. Moreover, is more generic than other data optimisation approaches for the sparse inpainting problem, since it can also be extended to nonlinear inpainting operators such as EED. This is exploited to achieve reconstructions with state-of-the-art quality. We also give an extensive literature survey on PDE-based image compression methods.

##### Abstract (translated by Google)
一些最近的用于有损信号和图像压缩的方法仅存储少量选择的像素，并通过修改偏微分方程（PDE）来填充缺失的结构。适合的算子包括拉普拉斯算子，双调和算子和边缘增强各向异性扩散（EED）。这种方法的质量在很大程度上取决于对数据的选择。在领域和共域中优化这些数据会产生具有挑战性的数学问题，这些问题应该在我们的工作中解决。在1D的情况下，我们证明了这个问题的难度，并且我们给出证据表明，分解为空间和色调（即函数值）的优化几乎不会使结果恶化。在2D设置中，我们提出了即使指定的数据非常稀疏也能实现高重建质量的通用算法。为了优化空间数据，我们使用概率sparsification，其次是一个非局部像素交换，避免陷入局部最优的optima。在这个空间优化之后，我们执行音调优化，修改函数值以减少全局重构误差。对于均匀扩散修复，这归结为最小二乘问题，我们证明它有一个独特的解决方案。我们证明，它可以有效地找到一个梯度下降的方法，加速与快速显式扩散（FED）周期。我们的框架允许先验地指定所需的修补掩模的密度。此外，与其他数据优化方法相比，稀疏修复问题更通用，因为它也可以扩展到EED等非线性修补算子。这被利用来实现具有最新质量的重建。我们还对基于PDE的图像压缩方法进行了广泛的文献调查。

##### URL
[https://arxiv.org/abs/1506.04566](https://arxiv.org/abs/1506.04566)

##### PDF
[https://arxiv.org/pdf/1506.04566](https://arxiv.org/pdf/1506.04566)

