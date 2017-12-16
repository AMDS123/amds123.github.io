---
layout: post
title: "Face Clustering: Representation and Pairwise Constraints"
date: 2017-06-15 20:17:33
categories: arXiv_CV
tags: arXiv_CV Face Image_Classification Classification
author: Yichun Shi, Charles Otto, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
Clustering face images according to their identity has two important applications: (i) grouping a collection of face images when no external labels are associated with images, and (ii) indexing for efficient large scale face retrieval. The clustering problem is composed of two key parts: face representation and choice of similarity for grouping faces. We first propose a representation based on ResNet, which has been shown to perform very well in image classification problems. Given this representation, we design a clustering algorithm, Conditional Pairwise Clustering (ConPaC), which directly estimates the adjacency matrix only based on the similarity between face images. This allows a dynamic selection of number of clusters and retains pairwise similarity between faces. ConPaC formulates the clustering problem as a Conditional Random Field (CRF) model and uses Loopy Belief Propagation to find an approximate solution for maximizing the posterior probability of the adjacency matrix. Experimental results on two benchmark face datasets (LFW and IJB-B) show that ConPaC outperforms well known clustering algorithms such as k-means, spectral clustering and approximate rank-order. Additionally, our algorithm can naturally incorporate pairwise constraints to obtain a semi-supervised version that leads to improved clustering performance. We also propose an k-NN variant of ConPaC, which has a linear time complexity given a k-NN graph, suitable for large datasets.

##### Abstract (translated by Google)
将人脸图像根据其身份进行聚类有两个重要的应用：（i）当没有外部标签与图像相关联时将一组人脸图像分组，以及（ii）用于高效大规模人脸检索的索引。聚类问题由两个关键部分组成：人脸表示和人脸分类相似度的选择。我们首先提出一种基于ResNet的表示方法，该方法在图像分类问题中表现出色。给定这种表示，我们设计了一种聚类算法，ConPaC（ConPaC），它只根据人脸图像之间的相似性直接估计邻接矩阵。这允许动态选择数量的聚类并保留面部之间的配对相似度。 ConPaC将聚类问题描述为一个条件随机场（CRF）模型，并使用Loopy Belief Propagation来寻找一个最大化邻接矩阵后验概率的近似解。在两个基准人脸数据集（LFW和IJB-B）上的实验结果表明，ConPaC优于众所周知的聚类算法，如k均值，谱聚类和近似排序。此外，我们的算法自然可以结合成对约束来获得导致改进的聚类性能的半监督版本。我们还提出了ConPaC的k-NN变体，其具有适合于大数据集的k-NN图的线性时间复杂度。

##### URL
[https://arxiv.org/abs/1706.05067](https://arxiv.org/abs/1706.05067)

##### PDF
[https://arxiv.org/pdf/1706.05067](https://arxiv.org/pdf/1706.05067)

