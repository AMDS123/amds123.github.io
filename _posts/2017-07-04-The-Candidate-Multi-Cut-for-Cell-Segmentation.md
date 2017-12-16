---
layout: post
title: "The Candidate Multi-Cut for Cell Segmentation"
date: 2017-07-04 11:05:40
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Jan Funke, Chong Zhang, Tobias Pietzsch, Stephan Saalfeld
mathjax: true
---

* content
{:toc}

##### Abstract
Two successful approaches for the segmentation of biomedical images are (1) the selection of segment candidates from a merge-tree, and (2) the clustering of small superpixels by solving a Multi-Cut problem. In this paper, we introduce a model that unifies both approaches. Our model, the Candidate Multi-Cut (CMC), allows joint selection and clustering of segment candidates from a merge-tree. This way, we overcome the respective limitations of the individual methods: (1) the space of possible segmentations is not constrained to candidates of a merge-tree, and (2) the decision for clustering can be made on candidates larger than superpixels, using features over larger contexts. We solve the optimization problem of selecting and clustering of candidates using an integer linear program. On datasets of 2D light microscopy of cell populations and 3D electron microscopy of neurons, we show that our method generalizes well and generates more accurate segmentations than merge-tree or Multi-Cut methods alone.

##### Abstract (translated by Google)
两种成功的分割生物医学图像的方法是：（1）从合并树中选择分割候选者;（2）通过解决多重切分问题来聚类小的超像素。在本文中，我们介绍一个统一两种方法的模型。我们的模型，候选多重切割（CMC）允许从合并树中选择和聚类候选区段。这样，我们克服了各个方法的局限性：（1）可能分割的空间不限于合并树的候选者;（2）可以对比超级像素大的候选者进行聚类的决定，功能在更大的上下文。我们利用整数线性规划解决了候选人选择和聚类的优化问题。在细胞群的二维光学显微镜和神经元的三维电子显微镜的数据集上，我们表明，我们的方法一般化得很好，并且比单独的合并树或多重切割方法生成更准确的分割。

##### URL
[https://arxiv.org/abs/1707.00907](https://arxiv.org/abs/1707.00907)

##### PDF
[https://arxiv.org/pdf/1707.00907](https://arxiv.org/pdf/1707.00907)

