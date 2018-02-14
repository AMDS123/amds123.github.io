---
layout: post
title: "Recurrent Slice Networks for 3D Segmentation on Point Clouds"
date: 2018-02-13 00:04:27
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation RNN
author: Qiangui Huang, Weiyue Wang, Ulrich Neumann
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a conceptually simple and powerful framework, Recurrent Slice Network (RSNet), for 3D semantic segmentation on point clouds. Performing 3D segmentation on point clouds is computationally efficient. And it is free of the quantitation artifact problems which exists in other 3D data formats such as voxelized volumes and multi view renderings. However, existing point clouds based methods either do not model local dependencies or rely on heavy extra computations. In contrast, our RSNet is equipped with a lightweight local dependency module, which is a combination of a novel slice pooling layer, Recurrent Neural Network (RNN) layers, and a slice unpooling layer. The slice pooling layer is designed to project features of unordered points into an ordered sequence of feature vectors. Then, RNNs are applied to model dependencies for the sequence. We validate the importance of local contexts and the effectiveness of our RSNet on the S3DIS, ScanNet, and ShapeNet dataset. Without bells and whistles, RSNet surpasses all previous state-of-the-art methods on these benchmarks. Moreover, additional computation analysis demonstrates the efficiency of RSNet.

##### Abstract (translated by Google)
在本文中，我们提出了一个概念上简单而强大的框架，即递归切片网络（RSNet），用于点云上的三维语义分割。在点云上执行3D分割在计算上是高效的。它不存在其他3D数据格式（如体素化体积和多视图渲染）中存在的定量伪像问题。然而，现有的基于点云的方法或者不模拟本地依赖或者依赖繁重的额外计算。相比之下，我们的RSNet配备了一个轻量级本地依赖模块，它是一个新颖的切片池层，递归神经网络（RNN）层和切片解卷层的组合。切片池层被设计为将无序点的特征投影到特征矢量的有序序列中。然后，将RNN应用于模型对序列的依赖关系。我们验证了本地环境的重要性以及RSNet在S3DIS，ScanNet和ShapeNet数据集上的有效性。无需花费大量时间，RSNet在这些基准测试中超越了以前所有先进的方法。此外，额外的计算分析显示了RSNet的效率。

##### URL
[http://arxiv.org/abs/1802.04402](http://arxiv.org/abs/1802.04402)

##### PDF
[http://arxiv.org/pdf/1802.04402](http://arxiv.org/pdf/1802.04402)

