---
layout: post
title: "Partial Procedural Geometric Model Fitting for Point Clouds"
date: 2016-10-17 00:47:36
categories: arXiv_CV
tags: arXiv_CV Face Optimization
author: Zongliang Zhang, Jonathan Li, Yulan Guo, Yangbin Lin, Ming Cheng, Cheng Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Geometric model fitting is a fundamental task in computer graphics and computer vision. However, most geometric model fitting methods are unable to fit an arbitrary geometric model (e.g. a surface with holes) to incomplete data, due to that the similarity metrics used in these methods are unable to measure the rigid partial similarity between arbitrary models. This paper hence proposes a novel rigid geometric similarity metric, which is able to measure both the full similarity and the partial similarity between arbitrary geometric models. The proposed metric enables us to perform partial procedural geometric model fitting (PPGMF). The task of PPGMF is to search a procedural geometric model space for the model rigidly similar to a query of non-complete point set. Models in the procedural model space are generated according to a set of parametric modeling rules. A typical query is a point cloud. PPGMF is very useful as it can be used to fit arbitrary geometric models to non-complete (incomplete, over-complete or hybrid-complete) point cloud data. For example, most laser scanning data is non-complete due to occlusion. Our PPGMF method uses Markov chain Monte Carlo technique to optimize the proposed similarity metric over the model space. To accelerate the optimization process, the method also employs a novel coarse-to-fine model dividing strategy to reject dissimilar models in advance. Our method has been demonstrated on a variety of geometric models and non-complete data. Experimental results show that the PPGMF method based on the proposed metric is able to fit non-complete data, while the method based on other metrics is unable. It is also shown that our method can be accelerated by several times via early rejection.

##### Abstract (translated by Google)
几何模型拟合是计算机图形学和计算机视觉的基本任务。然而，由于在这些方法中使用的相似性量度不能够测量任意模型之间的刚性部分相似性，所以大多数几何模型拟合方法不能够将任意的几何模型（例如具有孔的表面）拟合成不完整的数据。因此，本文提出了一种新的刚性几何相似性度量，它能够测量任意几何模型之间的完全相似度和部分相似度。建议的度量使我们能够执行部分程序几何模型拟合（PPGMF）。 PPGMF的任务是为模型搜索一个程序化的几何模型空间，类似于非完整点集的查询。程序模型空间中的模型是根据一组参数化建模规则生成的。典型的查询是点云。 PPGMF非常有用，因为它可用于将任意几何模型拟合为非完整（不完整，过度完成或混合完整）点云数据。例如，大多数激光扫描数据由于遮挡而不完整。我们的PPGMF方法使用马尔科夫链蒙特卡罗技术来优化模型空间上提出的相似性度量。为了加速优化过程，该方法还采用了一种新的粗细模型划分策略，提前拒绝不相似的模型。我们的方法已经在各种几何模型和不完整的数据上进行了演示。实验结果表明，基于所提出的度量的PPGMF方法能够适应非完整的数据，而基于其他度量的方法则无法实现。这也表明，我们的方法可以通过早期拒绝加速几次。

##### URL
[https://arxiv.org/abs/1610.04936](https://arxiv.org/abs/1610.04936)

##### PDF
[https://arxiv.org/pdf/1610.04936](https://arxiv.org/pdf/1610.04936)

