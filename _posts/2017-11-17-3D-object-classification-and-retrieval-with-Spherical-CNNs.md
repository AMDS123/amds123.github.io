---
layout: post
title: "3D object classification and retrieval with Spherical CNNs"
date: 2017-11-17 20:49:28
categories: arXiv_CV
tags: arXiv_CV Face Classification
author: Carlos Esteves, Christine Allen-Blanchette, Ameesh Makadia, Kostas Daniilidis
mathjax: true
---

* content
{:toc}

##### Abstract
3D object classification and retrieval presents many challenges that are not present in the traditional (planar) image setting. First, there is the question of shape representation. Face-vertex meshes, for instance, are widely used in computer graphics, but their irregular structure complicate their use as inputs to learning models. Previous works have converted meshes to more structured representations, such a collections of rendered views or volumetric grids, in order to feed them to 2D or 3D CNNs. These representations, however, are redundant and wasteful, requiring large amounts of storage, pre-processing time, and large networks with millions of parameters to handle them. Another challenge is how to treat object orientations. Orientation-invariance is a desired property for any classification engine, yet most current models do not address this explicitly, rather requiring increased model and sample complexity to handle arbitrary input orientations. We present a model that aims to be efficient in both the number of learnable parameters and input size. We leverage the group convolution equivariance properties; more specifically, the spherical convolution, to build a network that learns feature maps equivariant to SO(3) actions by design. By mapping a 3D input to the surface of a sphere, we also end up with a small input size.

##### Abstract (translated by Google)
3D对象分类和检索提出了许多在传统（平面）图像设置中不存在的挑战。首先是形状表示的问题。例如，面顶点网格被广泛用于计算机图形学，但是它们的不规则结构使其作为学习模型的输入变得复杂。以前的作品已经将网格转换为更多结构化的表示，例如渲染的视图或体积网格的集合，以便将它们馈送到2D或3D CNN。然而，这些表示是多余的和浪费的，需要大量的存储，预处理时间和具有数百万个参数的大型网络来处理它们。另一个挑战是如何处理对象的方向。方向不变性是任何分类引擎的期望属性，但是大多数当前的模型没有明确地解决这个问题，而是需要增加模型和样本的复杂性来处理任意的输入方向。我们提出一个模型，旨在提高可学习参数的数量和输入大小。我们利用组卷积等变性属性;更具体地说，球面卷积，以建立一个网络，学习特征映射等同于SO（3）行动的设计。通过将3D输入映射到球体的表面，我们最终也只需要很小的输入大小。

##### URL
[https://arxiv.org/abs/1711.06721](https://arxiv.org/abs/1711.06721)

##### PDF
[https://arxiv.org/pdf/1711.06721](https://arxiv.org/pdf/1711.06721)

