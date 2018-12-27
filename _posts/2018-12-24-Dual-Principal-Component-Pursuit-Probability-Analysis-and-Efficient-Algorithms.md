---
layout: post
title: "Dual Principal Component Pursuit: Probability Analysis and Efficient Algorithms"
date: 2018-12-24 14:07:18
categories: arXiv_CV
tags: arXiv_CV Optimization Detection
author: Zhihui Zhu, Yifan Wang, Daniel P. Robinson, Daniel Q. Naiman, Rene Vidal, Manolis C. Tsakiris
mathjax: true
---

* content
{:toc}

##### Abstract
Recent methods for learning a linear subspace from data corrupted by outliers are based on convex $\ell_1$ and nuclear norm optimization and require the dimension of the subspace and the number of outliers to be sufficiently small. In sharp contrast, the recently proposed Dual Principal Component Pursuit (DPCP) method can provably handle subspaces of high dimension by solving a non-convex $\ell_1$ optimization problem on the sphere. However, its geometric analysis is based on quantities that are difficult to interpret and are not amenable to statistical analysis. In this paper we provide a refined geometric analysis and a new statistical analysis that show that DPCP can tolerate as many outliers as the square of the number of inliers, thus improving upon other provably correct robust PCA methods. We also propose a scalable Projected Sub-Gradient Method method (DPCP-PSGM) for solving the DPCP problem and show it admits linear convergence even though the underlying optimization problem is non-convex and non-smooth. Experiments on road plane detection from 3D point cloud data demonstrate that DPCP-PSGM can be more efficient than the traditional RANSAC algorithm, which is one of the most popular methods for such computer vision applications.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.09924](http://arxiv.org/abs/1812.09924)

##### PDF
[http://arxiv.org/pdf/1812.09924](http://arxiv.org/pdf/1812.09924)

