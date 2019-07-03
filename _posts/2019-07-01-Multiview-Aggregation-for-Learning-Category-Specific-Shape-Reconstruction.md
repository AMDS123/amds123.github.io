---
layout: post
title: "Multiview Aggregation for Learning Category-Specific Shape Reconstruction"
date: 2019-07-01 22:01:37
categories: arXiv_CV
tags: arXiv_CV Sparse Face
author: Srinath Sridhar, Davis Rempe, Julien Valentin, Sofien Bouaziz, Leonidas J. Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
We investigate the problem of learning category-specific 3D surface shape reconstruction from a variable number of RGB views of previously unobserved object instances. Most approaches for multiview shape reconstruction operate on sparse shape representations, or assume a fixed number of views. We present a method that can estimate dense 3D shape, and aggregate shape across multiple and varying number of input views. Given a single input view of an object instance, we propose a representation that encodes the dense shape of the visible object surface parts as well as the surface behind line of sight and occluded by the visible surface. When multiple input views are available, the shape representation is designed to be aggregated into a single 3D shape using an inexpesive union operation. We train a 2D CNN to learn to predict this representation from a variable number of views (1 or more). We further aggregate multiview information by using permutation equivariant layers that promote order-agnostic view information exchange at the feature level. Experiments show that our approach is able to produce dense reconstructions of objects, and is able to produce better results as more views are added.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.01085](http://arxiv.org/abs/1907.01085)

##### PDF
[http://arxiv.org/pdf/1907.01085](http://arxiv.org/pdf/1907.01085)

