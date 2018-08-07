---
layout: post
title: "Tensors, Differential Geometry and Statistical Shading Analysis"
date: 2018-07-27 15:23:02
categories: arXiv_CV
tags: arXiv_CV Face
author: Daniel Niels Holtmann-Rice, Benjamin S. Kunsberg, Steven W. Zucker
mathjax: true
---

* content
{:toc}

##### Abstract
We develop a linear algebraic framework for the shape-from-shading problem, because tensors arise when scalar (e.g. image) and vector (e.g. surface normal) fields are differentiated multiple times. Using this framework, we first investigate when image derivatives exhibit invariance to changing illumination by calculating the statistics of image derivatives under general distributions on the light source. Second, we apply that framework to develop Taylor-like expansions, and build a boot-strapping algorithm to find the polynomial surface solutions (under any light source) consistent with a given patch to arbitrary order. A generic constraint on the light source restricts these solutions to a 2-D subspace, plus an unknown rotation matrix. It is this unknown matrix that encapsulates the ambiguity in the problem. Finally, we use the framework to computationally validate the hypothesis that image orientations (derivatives) provide increased invariance to illumination by showing (for a Lambertian model) that a shape-from-shading algorithm matching gradients instead of intensities provides more accurate reconstructions when illumination is incorrectly estimated under a flatness prior.

##### Abstract (translated by Google)
我们开发了一种用于阴影形状问题的线性代数框架，因为当标量（例如图像）和矢量（例如表面法线）场被多次区分时，会出现张量。使用该框架，我们首先通过计算光源上一般分布下的图像导数的统计来研究图像导数何时表现出对变化照明的不变性。其次，我们应用该框架来开发类似Taylor的扩展，并构建一个引导捆绑算法，以找到与任意顺序的给定补丁一致的多项式表面解（在任何光源下）。对光源的通用约束将这些解决方案限制为2-D子空间加上未知的旋转矩阵。正是这个未知矩阵囊括了问题的模糊性。最后，我们使用该框架来计算验证图像方向（导数）通过显示（对于朗伯模型）提供匹配渐变的形状而不是强度的形状从阴影的形状提供更精确的重建时的图像方向（衍生物）提供增加的照明不变性的假设。在平坦度之前错误估计。

##### URL
[http://arxiv.org/abs/1705.05902](http://arxiv.org/abs/1705.05902)

##### PDF
[http://arxiv.org/pdf/1705.05902](http://arxiv.org/pdf/1705.05902)

