---
layout: post
title: "A Numerical Framework for Efficient Motion Estimation on Evolving Sphere-Like Surfaces based on Brightness and Mass Conservation Laws"
date: 2018-05-02 20:30:01
categories: arXiv_CV
tags: arXiv_CV Face
author: Lukas F. Lang
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we consider brightness and mass conservation laws for motion estimation on evolving Riemannian 2-manifolds that allow for a radial parametrisation from the 2-sphere. While conservation of brightness constitutes the foundation for optical flow methods and has been generalised to said scenario, we formulate in this article the principle of mass conservation for time-varying surfaces which are embedded in Euclidean 3-space and derive a generalised continuity equation. The main motivation for this work is efficient cell motion estimation in time-lapse (4D) volumetric fluorescence microscopy images of a living zebrafish embryo. Increasing spatial and temporal resolution of modern microscopes require efficient analysis of such data. With this application in mind we address this need and follow an emerging paradigm in this field: dimensional reduction. In light of the ill-posedness of considered conservation laws we employ Tikhonov regularisation and propose the use of spatially varying regularisation functionals that recover motion only in regions with cells. For the efficient numerical solution we devise a Galerkin method based on compactly supported (tangent) vectorial basis functions. Furthermore, for the fast and accurate estimation of the evolving sphere-like surface from scattered data we utilise surface interpolation with spatio-temporal regularisation. We present numerical results based on aforementioned zebrafish microscopy data featuring fluorescently labelled cells.

##### Abstract (translated by Google)
在这项工作中，我们考虑运动估计的亮度和质量守恒定律，以演化黎曼流形上的二维流形，从而允许从二维球体进行径向参数化。虽然亮度的保持构成了光流方法的基础，并且已经被推广到所述场景中，但是我们在本文中制定了嵌入欧几里德三维空间并且推导出广义连续性方程的时变表面的质量守恒原理。这项工作的主要动机是有效的细胞运动估计时间推移（4D）活体斑马鱼胚胎的体积荧光显微镜图像。现代显微镜的空间和时间分辨率越来越高，需要对这些数据进行有效的分析。考虑到这个应用，我们解决了这个需求，并遵循了这个领域的一个新兴范式：尺寸缩减。鉴于所考虑的守恒定律的不适宜性，我们采用了Tikhonov正则化方法，并提出使用空间变化的正则化函数来恢复仅在具有细胞的区域中的运动。对于有效的数值解，我们设计了一个基于紧支撑（切线）向量基函数的Galerkin方法。此外，为了从散射数据快速且准确地估计演变的类似球面，我们利用时空正则化的表面插值。我们基于上述提供荧光标记细胞的斑马鱼显微镜数据提供数值结果。

##### URL
[http://arxiv.org/abs/1805.01006](http://arxiv.org/abs/1805.01006)

##### PDF
[http://arxiv.org/pdf/1805.01006](http://arxiv.org/pdf/1805.01006)

