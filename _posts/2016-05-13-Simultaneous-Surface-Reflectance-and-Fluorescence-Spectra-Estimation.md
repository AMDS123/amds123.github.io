---
layout: post
title: "Simultaneous Surface Reflectance and Fluorescence Spectra Estimation"
date: 2016-05-13 16:36:09
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Henryk Blasinski, Joyce Farrell, Brian Wandell
mathjax: true
---

* content
{:toc}

##### Abstract
There is widespread interest in estimating the fluorescence properties of natural materials in an image. However, the separation between reflected and fluoresced components is difficult, because it is impossible to distinguish reflected and fluoresced photons without controlling the illuminant spectrum. We show how to jointly estimate the reflectance and fluorescence from a single set of images acquired under multiple illuminants. We present a framework based on a linear approximation to the physical equations describing image formation in terms of surface spectral reflectance and fluorescence due to multiple fluorophores. We relax the non-convex, inverse estimation problem in order to jointly estimate the reflectance and fluorescence properties in a single optimization step and we use the Alternating Direction Method of Multipliers (ADMM) approach to efficiently find a solution. We provide a software implementation of the solver for our method and prior methods. We evaluate the accuracy and reliability of the method using both simulations and experimental data. To acquire data to test the methods, we built a custom imaging system using a monochrome camera, a filter wheel with bandpass transmissive filters and a small number of light emitting diodes. We compared the system and algorithm performance with the ground truth as well as with prior methods. Our approach produces lower errors compared to earlier algorithms.

##### Abstract (translated by Google)
估计图像中天然材料的荧光性质具有广泛的兴趣。然而，反射和荧光组分之间的分离是困难的，因为在不控制发光光谱的情况下不可能区分反射的和发荧光的光子。我们展示了如何联合估计在多个光源下获取的一组图像的反射率和荧光。我们提出了一个基于线性近似的物理方程的框架描述图像形成的表面光谱反射率和荧光多个荧光。为了在单个优化步骤中联合估计反射率和荧光性质，我们放宽了非凸反向估计问题，并且我们使用交替方向乘法器（ADMM）方法来有效地找到解。我们为我们的方法和先前的方法提供了求解器的软件实现。我们使用模拟和实验数据来评估方法的准确性和可靠性。为了获取数据以测试方法，我们使用单色相机，带有带通透射滤光器的滤光轮和少量发光二极管构建定制成像系统。我们比较了系统和算法的性能，以及现有的方法。与早期的算法相比，我们的方法产生较低的错

##### URL
[https://arxiv.org/abs/1605.04243](https://arxiv.org/abs/1605.04243)

##### PDF
[https://arxiv.org/pdf/1605.04243](https://arxiv.org/pdf/1605.04243)

