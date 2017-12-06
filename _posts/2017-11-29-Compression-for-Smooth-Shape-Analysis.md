---
layout: post
title: "Compression for Smooth Shape Analysis"
date: 2017-11-29 12:46:08
categories: arXiv_CV
tags: arXiv_CV
author: V. Estellers, F. R. Schmidt, D. Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Most 3D shape analysis methods use triangular meshes to discretize both the shape and functions on it as piecewise linear functions. With this representation, shape analysis requires fine meshes to represent smooth shapes and geometric operators like normals, curvatures, or Laplace-Beltrami eigenfunctions at large computational and memory costs. We avoid this bottleneck with a compression technique that represents a smooth shape as subdivision surfaces and exploits the subdivision scheme to parametrize smooth functions on that shape with a few control parameters. This compression does not affect the accuracy of the Laplace-Beltrami operator and its eigenfunctions and allow us to compute shape descriptors and shape matchings at an accuracy comparable to triangular meshes but a fraction of the computational cost. Our framework can also compress surfaces represented by point clouds to do shape analysis of 3D scanning data.

##### Abstract (translated by Google)
大多数三维形状分析方法使用三角形网格来将其形状和功能分离为分段线性函数。通过这种表示，形状分析需要精细的网格来表示平滑的形状和几何操作符，如法线，曲率或拉普拉斯 - 贝尔特拉米本征函数。我们通过压缩技术来避免这个瓶颈，这种压缩技术表示平滑的形状作为细分曲面，并利用细分方案通过几个控制参数来对该形状上的平滑函数进行参数化。这种压缩不会影响拉普拉斯 - 贝尔特拉米算子及其本征函数的准确性，并且允许我们以与三角形网格相当的精度计算形状描述符和形状匹配，但计算成本的一小部分。我们的框架也可以压缩由点云表示的表面来对3D扫描数据进行形状分析。

##### URL
[https://arxiv.org/abs/1711.10824](https://arxiv.org/abs/1711.10824)

