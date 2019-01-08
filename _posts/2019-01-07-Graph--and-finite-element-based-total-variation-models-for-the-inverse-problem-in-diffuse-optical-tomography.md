---
layout: post
title: "Graph- and finite element-based total variation models for the inverse problem in diffuse optical tomography"
date: 2019-01-07 18:52:32
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Optimization
author: Wenqi Lu, Jinming Duan, David Orive-Miguel, Lionel Herve, Iain B Styles
mathjax: true
---

* content
{:toc}

##### Abstract
Total variation (TV) is a powerful regularization method that has been widely applied in different imaging applications, but is difficult to apply to diffuse optical tomography (DOT) image reconstruction (inverse problem) due to complex and unstructured geometries, non-linearity of the data fitting and regularization terms, and non-differentiability of the regularization term. We develop several approaches to overcome these difficulties by: i) defining discrete differential operators for unstructured geometries using both finite element and graph representations; ii) developing an optimization algorithm based on the alternating direction method of multipliers (ADMM) for the non-differentiable and non-linear minimization problem; iii) investigating isotropic and anisotropic variants of TV regularization, and comparing their finite element- and graph-based implementations. These approaches are evaluated on experiments on simulated data and real data acquired from a tissue phantom. Our results show that both FEM and graph-based TV regularization is able to accurately reconstruct both sparse and non-sparse distributions without the over-smoothing effect of Tikhonov regularization and the over-sparsifying effect of L$_1$ regularization. The graph representation was found to out-perform the FEM method for low-resolution meshes, and the FEM method was found to be more accurate for high-resolution meshes.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.01969](http://arxiv.org/abs/1901.01969)

##### PDF
[http://arxiv.org/pdf/1901.01969](http://arxiv.org/pdf/1901.01969)

