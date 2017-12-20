---
layout: post
title: "Scale-Space Anisotropic Total Variation for Limited Angle Tomography"
date: 2017-12-19 13:59:10
categories: arXiv_CV
tags: arXiv_CV Regularization
author: Yixing Huang, Oliver Taubmann, Xiaolin Huang, Viktor Haase, Guenter Lauritsch, Andreas Maier
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses streak reduction in limited angle tomography. Although the iterative reweighted total variation (wTV) algorithm reduces small streaks well, it is rather inept at eliminating large ones since total variation (TV) regularization is scale-dependent and may regard these streaks as homogeneous areas. Hence, the main purpose of this paper is to reduce streak artifacts at various scales. We propose the scale-space anisotropic total variation (ssaTV) algorithm in two different implementations. The first implementation (ssaTV-1) utilizes an anisotropic gradient-like operator which uses 2s neighboring pixels along the streaks' normal direction at each scale s. The second implementation (ssaTV-2) makes use of anisotropic down-sampling and up-sampling operations, similarly oriented along the streaks' normal direction, to apply TV regularization at various scales. Experiments on numerical and clinical data demonstrate that both ssaTV algorithms reduce streak artifacts more effectively and efficiently than wTV, particularly when using multiple scales.

##### Abstract (translated by Google)
本文讨论了有限角度断层扫描中条纹的减少。尽管迭代重加权总变差（wTV）算法很好地减少了小条纹，但是由于总变异（TV）正则化依赖于比例，并且可能将这些条纹视为均匀区域，所以它在消除大条纹方面是不适当的。因此，本文的主要目的是减少各种尺度的条纹伪影。我们在两种不同的实现中提出了尺度 - 空间各向异性总变化（ssaTV）算法。第一个实现（ssaTV-1）利用了一个各向异性梯度算子，它在每个尺度s沿条纹法线方向使用2个相邻像素。第二个实施（ssaTV-2）利用各向异性的下采样和上采样操作，类似地沿着条纹的正常方向，以在各种尺度上应用TV正则化。数值和临床数据的实验表明，两种ssaTV算法比wTV更有效和有效地减少条纹伪影，特别是当使用多个尺度时。

##### URL
[http://arxiv.org/abs/1712.06930](http://arxiv.org/abs/1712.06930)

##### PDF
[http://arxiv.org/pdf/1712.06930](http://arxiv.org/pdf/1712.06930)

