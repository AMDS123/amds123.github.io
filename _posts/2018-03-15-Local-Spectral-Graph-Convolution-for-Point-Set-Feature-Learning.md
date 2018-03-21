---
layout: post
title: "Local Spectral Graph Convolution for Point Set Feature Learning"
date: 2018-03-15 16:00:50
categories: arXiv_CV
tags: arXiv_CV Segmentation Classification Deep_Learning
author: Chu Wang, Babak Samari, Kaleem Siddiqi
mathjax: true
---

* content
{:toc}

##### Abstract
Feature learning on point clouds has shown great promise, with the introduction of effective and generalizable deep learning frameworks such as pointnet++. Thus far, however, point features have been abstracted in an independent and isolated manner, ignoring the relative layout of neighboring points as well as their features. In the present article, we propose to overcome this limitation by using spectral graph convolution on a local graph, combined with a novel graph pooling strategy. In our approach, graph convolution is carried out on a nearest neighbor graph constructed from a point's neighborhood, such that features are jointly learned. We replace the standard max pooling step with a recursive clustering and pooling strategy, devised to aggregate information from within clusters of nodes that are close to one another in their spectral coordinates, leading to richer overall feature descriptors. Through extensive experiments on diverse datasets, we show a consistent demonstrable advantage for the tasks of both point set classification and segmentation.

##### Abstract (translated by Google)
点云特征学习已经显示出很大的希望，并且引入了有效的，可普遍化的深度学习框架，如pointnet ++。然而，迄今为止，点特征已经以独立和孤立的方式被抽象出来，忽略了相邻点的相对布局以及它们的特征。在本文中，我们提出通过在局部图上使用谱图卷积来克服这个局限性，并结合一种新颖的图形池化策略。在我们的方法中，图卷积是在从一个点的邻域构建的最近邻图上进行的，因此特征是共同学习的。我们用递归聚类和池化策略替换标准最大池化步骤，设计用于聚集来自节点簇内的信息，这些节点在其光谱坐标中彼此接近，从而导致更丰富的整体特征描述符。通过对不同数据集进行广泛的实验，我们显示了点集分类和分割任务的一致可证明的优势。

##### URL
[https://arxiv.org/abs/1803.05827](https://arxiv.org/abs/1803.05827)

##### PDF
[https://arxiv.org/pdf/1803.05827](https://arxiv.org/pdf/1803.05827)

