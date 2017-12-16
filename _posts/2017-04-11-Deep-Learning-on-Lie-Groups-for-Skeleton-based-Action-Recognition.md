---
layout: post
title: "Deep Learning on Lie Groups for Skeleton-based Action Recognition"
date: 2017-04-11 08:47:00
categories: arXiv_CV
tags: arXiv_CV Action_Recognition Classification Deep_Learning Recognition
author: Zhiwu Huang, Chengde Wan, Thomas Probst, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
In recent years, skeleton-based action recognition has become a popular 3D classification problem. State-of-the-art methods typically first represent each motion sequence as a high-dimensional trajectory on a Lie group with an additional dynamic time warping, and then shallowly learn favorable Lie group features. In this paper we incorporate the Lie group structure into a deep network architecture to learn more appropriate Lie group features for 3D action recognition. Within the network structure, we design rotation mapping layers to transform the input Lie group features into desirable ones, which are aligned better in the temporal domain. To reduce the high feature dimensionality, the architecture is equipped with rotation pooling layers for the elements on the Lie group. Furthermore, we propose a logarithm mapping layer to map the resulting manifold data into a tangent space that facilitates the application of regular output layers for the final classification. Evaluations of the proposed network for standard 3D human action recognition datasets clearly demonstrate its superiority over existing shallow Lie group feature learning methods as well as most conventional deep learning methods.

##### Abstract (translated by Google)
近年来，基于骨架的动作识别已经成为流行的3D分类问题。最先进的方法通常首先将每个运动序列表示为具有附加的动态时间扭曲的李群上的高维轨迹，然后浅层地学习有利的李群特征。在本文中，我们将李群结构纳入深层网络结构，以便学习更适合3D动作识别的李群特征。在网络结构中，我们设计了旋转映射层，将输入的李群特征转换为理想的，在时域上更好地对齐。为了降低高特征维度，该体系结构在Lie群上的元素上配备了旋转池层。此外，我们提出了一个对数映射层，将得到的流形数据映射到一个切线空间，便于最终分类的常规输出层的应用。所提出的标准三维人体动作识别数据集网络的评估清楚地表明其优于现有的浅层李群特征学习方法以及大多数传统的深度学习方法。

##### URL
[https://arxiv.org/abs/1612.05877](https://arxiv.org/abs/1612.05877)

##### PDF
[https://arxiv.org/pdf/1612.05877](https://arxiv.org/pdf/1612.05877)

