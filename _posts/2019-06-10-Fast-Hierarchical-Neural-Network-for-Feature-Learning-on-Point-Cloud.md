---
layout: post
title: "Fast Hierarchical Neural Network for Feature Learning on Point Cloud"
date: 2019-06-10 16:49:40
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation CNN Classification
author: Can Chen, Luca Zanotti Fragonara, Antonios Tsourdos
mathjax: true
---

* content
{:toc}

##### Abstract
The analyses relying on 3D point clouds are an utterly complex task, often involving million of points, but also requiring computationally efficient algorithms because of many real-time applications; e.g. autonomous vehicle. However, point clouds are intrinsically irregular and the points are sparsely distributed in a non-Euclidean space, which normally requires point-wise processing to achieve high performances. Although shared filter matrices and pooling layers in convolutional neural networks (CNNs) are capable of reducing the dimensionality of the problem and extracting high-level information simultaneously, grids and highly regular data format are required as input. In order to balance model performance and complexity, we introduce a novel neural network architecture exploiting local features from a manually subsampled point set. In our network, a recursive farthest point sampling method is firstly applied to efficiently cover the entire point set. Successively, we employ the k-nearest neighbours (knn) algorithm to gather local neighbourhood for each group of the subsampled points. Finally, a multiple layer perceptron (MLP) is applied on the subsampled points and edges that connect corresponding point and neighbours to extract local features. The architecture has been tested for both shape classification and segmentation using the ModelNet40 and ShapeNet part datasets, in order to show that the network achieves the best trade-off in terms of competitive performance when compared to other state-of-the-art algorithms.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04117](http://arxiv.org/abs/1906.04117)

##### PDF
[http://arxiv.org/pdf/1906.04117](http://arxiv.org/pdf/1906.04117)

