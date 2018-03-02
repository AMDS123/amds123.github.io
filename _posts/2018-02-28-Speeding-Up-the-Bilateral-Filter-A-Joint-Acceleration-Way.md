---
layout: post
title: "Speeding Up the Bilateral Filter: A Joint Acceleration Way"
date: 2018-02-28 07:14:59
categories: arXiv_CV
tags: arXiv_CV Knowledge
author: Longquan Dai, Mengke Yuan, Xiaopeng Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Computational complexity of the brute-force implementation of the bilateral filter (BF) depends on its filter kernel size. To achieve the constant-time BF whose complexity is irrelevant to the kernel size, many techniques have been proposed, such as 2D box filtering, dimension promotion, and shiftability property. Although each of the above techniques suffers from accuracy and efficiency problems, previous algorithm designers were used to take only one of them to assemble fast implementations due to the hardness of combining them together. Hence, no joint exploitation of these techniques has been proposed to construct a new cutting edge implementation that solves these problems. Jointly employing five techniques: kernel truncation, best N -term approximation as well as previous 2D box filtering, dimension promotion, and shiftability property, we propose a unified framework to transform BF with arbitrary spatial and range kernels into a set of 3D box filters that can be computed in linear time. To the best of our knowledge, our algorithm is the first method that can integrate all these acceleration techniques and, therefore, can draw upon one another's strong point to overcome deficiencies. The strength of our method has been corroborated by several carefully designed experiments. In particular, the filtering accuracy is significantly improved without sacrificing the efficiency at running time.

##### Abstract (translated by Google)
双边滤波器（BF）的蛮力实现的计算复杂度取决于其滤波器内核大小。为了实现复杂度与内核大小无关的恒定时间BF，已经提出了许多技术，例如2D盒滤波，维度提升和可移位性属性。虽然上述每种技术都存在精度和效率问题，但由于将它们组合在一起的难度，以前的算法设计人员只能使用其中的一种来组装快速实现。因此，没有提出联合开发这些技术来构建解决这些问题的新尖端实施方案。我们提出了一个统一的框架，将任意空间和距离内核的BF变换成一组三维盒子滤波器，可以在线性时间内计算。就我们所知，我们的算法是第一种可以集成所有这些加速技术的方法，因此可以利用彼此的优势来克服缺陷。我们的方法的强度已经通过几个精心设计的实验得到证实。特别是，在不牺牲运行时效率的情况下，过滤精度显着提高。

##### URL
[http://arxiv.org/abs/1803.00004](http://arxiv.org/abs/1803.00004)

##### PDF
[http://arxiv.org/pdf/1803.00004](http://arxiv.org/pdf/1803.00004)

