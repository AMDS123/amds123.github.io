---
layout: post
title: "A Combinatorial Solution to Non-Rigid 3D Shape-to-Image Matching"
date: 2017-05-18 14:59:07
categories: arXiv_CV
tags: arXiv_CV Knowledge Gradient_Descent
author: Florian Bernard, Frank R. Schmidt, Johan Thunberg, Daniel Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a combinatorial solution for the problem of non-rigidly matching a 3D shape to 3D image data. To this end, we model the shape as a triangular mesh and allow each triangle of this mesh to be rigidly transformed to achieve a suitable matching to the image. By penalising the distance and the relative rotation between neighbouring triangles our matching compromises between image and shape information. In this paper, we resolve two major challenges: Firstly, we address the resulting large and NP-hard combinatorial problem with a suitable graph-theoretic approach. Secondly, we propose an efficient discretisation of the unbounded 6-dimensional Lie group SE(3). To our knowledge this is the first combinatorial formulation for non-rigid 3D shape-to-image matching. In contrast to existing local (gradient descent) optimisation methods, we obtain solutions that do not require a good initialisation and that are within a bound of the optimal solution. We evaluate the proposed method on the two problems of non-rigid 3D shape-to-shape and non-rigid 3D shape-to-image registration and demonstrate that it provides promising results.

##### Abstract (translated by Google)
我们提出了一个组合的解决方案的非刚性匹配的三维形状的三维图像数据的问题。为此，我们将形状建模为三角形网格，并允许对这个网格的每个三角形进行刚性变换以实现与图像的适当匹配。通过惩罚相邻三角形之间的距离和相对旋转，我们匹配图像和形状信息之间的妥协。在本文中，我们解决了两个主要的挑战：首先，我们用一个合适的图论方法来解决由此产生的大的NP-hard组合问题。其次，我们提出了无界6维李群SE（3）的有效离散化。就我们所知，这是非刚性3D形状 - 图像匹配的第一个组合表达式。与现有的局部（梯度下降）优化方法相比，我们获得的解决方案不需要良好的初始化，并且在最优解的范围内。我们评估所提出的方法在非刚性三维形状与形状和非刚性三维形状与图像配准的两个问题，并表明它提供了有希望的结果。

##### URL
[https://arxiv.org/abs/1611.05241](https://arxiv.org/abs/1611.05241)

##### PDF
[https://arxiv.org/pdf/1611.05241](https://arxiv.org/pdf/1611.05241)

