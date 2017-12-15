---
layout: post
title: "Efficient Multi-view Performance Capture of Fine-Scale Surface Detail"
date: 2016-02-05 14:08:47
categories: arXiv_CV
tags: arXiv_CV Face Quantitative
author: Nadia Robertini, Edilson De Aguiar, Thomas Helten, Christian Theobalt
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new effective way for performance capture of deforming meshes with fine-scale time-varying surface detail from multi-view video. Our method builds up on coarse 4D surface reconstructions, as obtained with commonly used template-based methods. As they only capture models of coarse-to-medium scale detail, fine scale deformation detail is often done in a second pass by using stereo constraints, features, or shading-based refinement. In this paper, we propose a new effective and stable solution to this second step. Our framework creates an implicit representation of the deformable mesh using a dense collection of 3D Gaussian functions on the surface, and a set of 2D Gaussians for the images. The fine scale deformation of all mesh vertices that maximizes photo-consistency can be efficiently found by densely optimizing a new model-to-image consistency energy on all vertex positions. A principal advantage is that our problem formulation yields a smooth closed form energy with implicit occlusion handling and analytic derivatives. Error-prone correspondence finding, or discrete sampling of surface displacement values are also not needed. We show several reconstructions of human subjects wearing loose clothing, and we qualitatively and quantitatively show that we robustly capture more detail than related methods.

##### Abstract (translated by Google)
我们提出了一个新的有效的方法来从多视角视频细节时变表面细节的变形网格的性能捕获。我们的方法建立在粗糙的4D表面重建上，如常用的基于模板的方法所获得的。由于它们仅捕捉粗糙到中等比例的细节模型，通常使用立体约束，特征或基于阴影的细化，通常在第二阶段完成细节变形细节。在本文中，我们提出了一个新的有效和稳定的解决方案，第二步。我们的框架使用表面上高密度的3D高斯函数集合和用于图像的一组2D高斯函数来创建可变形网格的隐式表示。通过在所有顶点位置上密集地优化新的模型到图像一致性能量，可以有效地发现所有网格顶点的细尺度变形，从而最大限度地提高光致一致性。一个主要的优点是我们的问题表达式产生一个平滑的封闭形式的能量，隐式的遮挡处理和分析派生。容易出错的通信发现或表面位移值的离散采样也是不需要的。我们展示了穿着宽松服装的人体对象的几种重构，并且我们定性和定量地表明，我们比相关方法强有力地捕捉更多的细节。

##### URL
[https://arxiv.org/abs/1602.02023](https://arxiv.org/abs/1602.02023)

##### PDF
[https://arxiv.org/pdf/1602.02023](https://arxiv.org/pdf/1602.02023)

