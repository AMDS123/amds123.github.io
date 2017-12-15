---
layout: post
title: "FALDOI: A new minimization strategy for large displacement variational optical flow"
date: 2016-09-29 11:38:52
categories: arXiv_CV
tags: arXiv_CV Sparse Quantitative
author: Roberto P. Palomares, Enric Meinhardt-Llopis, Coloma Ballester, Gloria Haro
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a large displacement optical flow method that introduces a new strategy to compute a good local minimum of any optical flow energy functional. The method requires a given set of discrete matches, which can be extremely sparse, and an energy functional which locally guides the interpolation from those matches. In particular, the matches are used to guide a structured coordinate-descent of the energy functional around these keypoints. It results in a two-step minimization method at the finest scale which is very robust to the inevitable outliers of the sparse matcher and able to capture large displacements of small objects. Its benefits over other variational methods that also rely on a set of sparse matches are its robustness against very few matches, high levels of noise and outliers. We validate our proposal using several optical flow variational models. The results consistently outperform the coarse-to-fine approaches and achieve good qualitative and quantitative performance on the standard optical flow benchmarks.

##### Abstract (translated by Google)
我们提出了一种大位移光流法，它引入了一种新的策略来计算任何光流能量函数的一个好的局部最小值。该方法需要给定的一组离散匹配，其可以是非常稀疏的，并且能量函数在局部引导来自这些匹配的插值。特别是，这些匹配被用来引导围绕这些关键点起作用的能量的结构化坐标下降。它以最好的尺度导致了两步最小化方法，这对于稀疏匹配器的不可避免的异常值是非常稳健的，并且能够捕获大的小物体的位移。与其他也依赖一组稀疏匹配的变分方法相比，它的好处是它对很少的匹配，高水平的噪声和异常值的鲁棒性。我们使用几个光流变分模型来验证我们的建议。结果始终优于粗到精的方法，并在标准光流基准上实现良好的定性和定量性能。

##### URL
[https://arxiv.org/abs/1602.08960](https://arxiv.org/abs/1602.08960)

##### PDF
[https://arxiv.org/pdf/1602.08960](https://arxiv.org/pdf/1602.08960)

