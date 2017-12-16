---
layout: post
title: "Learning Efficient Point Cloud Generation for Dense 3D Object Reconstruction"
date: 2017-06-21 17:56:59
categories: arXiv_CV
tags: arXiv_CV Face CNN Optimization Prediction
author: Chen-Hsuan Lin, Chen Kong, Simon Lucey
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional methods of 3D object generative modeling learn volumetric predictions using deep networks with 3D convolutional operations, which are direct analogies to classical 2D ones. However, these methods are computationally wasteful in attempt to predict 3D shapes, where information is rich only on the surfaces. In this paper, we propose a novel 3D generative modeling framework to efficiently generate object shapes in the form of dense point clouds. We use 2D convolutional operations to predict the 3D structure from multiple viewpoints and jointly apply geometric reasoning with 2D projection optimization. We introduce the pseudo-renderer, a differentiable module to approximate the true rendering operation, to synthesize novel depth maps for optimization. Experimental results for single-image 3D object reconstruction tasks show that we outperforms state-of-the-art methods in terms of shape similarity and prediction density.

##### Abstract (translated by Google)
3D对象生成建模的常规方法使用具有3D卷积操作的深度网络来学习容积预测，其与经典的2D类似。然而，这些方法在计算上是浪费的，试图预测3D形状，其中信息仅在表面上丰富。在本文中，我们提出了一种新的三维生成建模框架，以高密度云形式高效地生成物体形状。我们使用二维卷积运算从多个角度预测三维结构，并联合应用几何推理和二维投影优化。我们引入伪渲染器，一个可微模块来逼近真实的渲染操作，合成新颖的深度图进行优化。单图像三维对象重建任务的实验结果表明，我们在形状相似性和预测密度方面胜过了最先进的方法。

##### URL
[https://arxiv.org/abs/1706.07036](https://arxiv.org/abs/1706.07036)

##### PDF
[https://arxiv.org/pdf/1706.07036](https://arxiv.org/pdf/1706.07036)

