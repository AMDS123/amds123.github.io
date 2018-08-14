---
layout: post
title: "Incremental Non-Rigid Structure-from-Motion with Unknown Focal Length"
date: 2018-08-13 12:53:10
categories: arXiv_CV
tags: arXiv_CV Attention Face
author: Thomas Probst, Danda Pani Paudel, Ajad Chhatkuli, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
The perspective camera and the isometric surface prior have recently gathered increased attention for Non-Rigid Structure-from-Motion (NRSfM). Despite the recent progress, several challenges remain, particularly the computational complexity and the unknown camera focal length. In this paper we present a method for incremental Non-Rigid Structure-from-Motion (NRSfM) with the perspective camera model and the isometric surface prior with unknown focal length. In the template-based case, we provide a method to estimate four parameters of the camera intrinsics. For the template-less scenario of NRSfM, we propose a method to upgrade reconstructions obtained for one focal length to another based on local rigidity and the so-called Maximum Depth Heuristics (MDH). On its basis we propose a method to simultaneously recover the focal length and the non-rigid shapes. We further solve the problem of incorporating a large number of points and adding more views in MDH-based NRSfM and efficiently solve them with Second-Order Cone Programming (SOCP). This does not require any shape initialization and produces results orders of times faster than many methods. We provide evaluations on standard sequences with ground-truth and qualitative reconstructions on challenging YouTube videos. These evaluations show that our method performs better in both speed and accuracy than the state of the art.

##### Abstract (translated by Google)
最近，透视摄像机和等距表面已经越来越受到非刚性结构运动（NRSfM）的关注。尽管最近取得了进展，但仍然存在一些挑战，特别是计算复杂性和未知的相机焦距。在本文中，我们提出了一种增量非刚性运动结构（NRSfM）的方法，其中透视摄像机模型和具有未知焦距的等距表面。在基于模板的情况下，我们提供了一种估计相机内在函数的四个参数的方法。对于NRSfM的无模板场景，我们提出了一种方法，可以根据局部刚度和所谓的最大深度启发法（MDH）将一个焦距获得的重建升级到另一个焦距。在此基础上，我们提出了一种同时恢复焦距和非刚性形状的方法。我们进一步解决了在基于MDH的NRSfM中合并大量点并添加更多视图的问题，并通过二阶锥编程（SOCP）有效地解决了这些问题。这不需要任何形状初始化，并且比许多方法产生的结果次序快。我们提供有关标准序列的评估，并对具有挑战性的YouTube视频进行真实性和定性重建。这些评估表明，我们的方法在速度和准确度方面都比现有技术表现更好。

##### URL
[http://arxiv.org/abs/1808.04181](http://arxiv.org/abs/1808.04181)

##### PDF
[http://arxiv.org/pdf/1808.04181](http://arxiv.org/pdf/1808.04181)

