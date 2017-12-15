---
layout: post
title: "Shape and Spatially-Varying Reflectance Estimation From Virtual Exemplars"
date: 2016-09-21 00:10:38
categories: arXiv_CV
tags: arXiv_CV Face Optimization Gradient_Descent
author: Zhuo Hui, Aswin C Sankaranarayanan
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of estimating the shape of objects that exhibit spatially-varying reflectance. We assume that multiple images of the object are obtained under a fixed view-point and varying illumination, i.e., the setting of photometric stereo. At the core of our techniques is the assumption that the BRDF at each pixel lies in the non-negative span of a known BRDF dictionary.This assumption enables a per-pixel surface normal and BRDF estimation framework that is computationally tractable and requires no initialization in spite of the underlying problem being non-convex. Our estimation framework first solves for the surface normal at each pixel using a variant of example-based photometric stereo. We design an efficient multi-scale search strategy for estimating the surface normal and subsequently, refine this estimate using a gradient descent procedure. Given the surface normal estimate, we solve for the spatially-varying BRDF by constraining the BRDF at each pixel to be in the span of the BRDF dictionary, here, we use additional priors to further regularize the solution. A hallmark of our approach is that it does not require iterative optimization techniques nor the need for careful initialization, both of which are endemic to most state-of-the-art techniques. We showcase the performance of our technique on a wide range of simulated and real scenes where we outperform competing methods.

##### Abstract (translated by Google)
本文讨论了估计呈现空间变化的反射率的物体的形状的问题。我们假定在固定的视点和变化的照明下，即在光度立体的设置下，获得物体的多个图像。我们技术的核心是假定每个像素处的BRDF位于已知BRDF字典的非负范围内。该假设使得每像素表面法线和BRDF估计框架在计算上易于处理并且不需要初始化尽管潜在的问题是非凸的。我们的估计框架首先使用基于示例的光度立体的变体来解决每个像素处的表面法线。我们设计了一个有效的多尺度搜索策略来估计表面法线，然后使用梯度下降法来优化这个估计。给定表面法线估计，我们通过将每个像素处的BRDF限制在BRDF字典的范围内来解决空间变化的BRDF，在这里，我们使用附加的先验来进一步调整解。我们的方法的一个标志是，它不需要迭代优化技术，也不需要仔细的初始化，这两者都是大多数最先进的技术特有的。我们展示了我们的技术在广泛的模拟和真实场景中的表现，我们超越了竞争的方法。

##### URL
[https://arxiv.org/abs/1512.05278](https://arxiv.org/abs/1512.05278)

##### PDF
[https://arxiv.org/pdf/1512.05278](https://arxiv.org/pdf/1512.05278)

