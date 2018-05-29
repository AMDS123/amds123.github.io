---
layout: post
title: "Convex Sparse Spectral Clustering: Single-view to Multi-view"
date: 2018-05-27 06:02:40
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse Embedding
author: Canyi Lu, Shuicheng Yan, Zhouchen Lin
mathjax: true
---

* content
{:toc}

##### Abstract
Spectral Clustering (SC) is one of the most widely used methods for data clustering. It first finds a low-dimensonal embedding $U$ of data by computing the eigenvectors of the normalized Laplacian matrix, and then performs k-means on $U^\top$ to get the final clustering result. In this work, we observe that, in the ideal case, $UU^\top$ should be block diagonal and thus sparse. Therefore we propose the Sparse Spectral Clustering (SSC) method which extends SC with sparse regularization on $UU^\top$. To address the computational issue of the nonconvex SSC model, we propose a novel convex relaxation of SSC based on the convex hull of the fixed rank projection matrices. Then the convex SSC model can be efficiently solved by the Alternating Direction Method of \canyi{Multipliers} (ADMM). Furthermore, we propose the Pairwise Sparse Spectral Clustering (PSSC) which extends SSC to boost the clustering performance by using the multi-view information of data. Experimental comparisons with several baselines on real-world datasets testify to the efficacy of our proposed methods.

##### Abstract (translated by Google)
光谱聚类（SC）是数据聚类中使用最广泛的方法之一。它首先通过计算归一化拉普拉斯矩阵的特征向量找到低维嵌入的$ U $数据，然后在$ U ^ \ top $上执行k-means来获得最终的聚类结果。在这项工作中，我们观察到，在理想情况下，$ UU ^ \ top $应该是块对角线，因此是稀疏的。因此，我们提出了稀疏光谱聚类（SSC）方法，它在$ UU ^ \ top $上扩展了稀疏正则化的SC。为了解决非凸性SSC模型的计算问题，我们提出了一种基于固定秩投影矩阵的凸包的SSC的新型凸松弛。然后利用\ canyi {Multipliers}（ADMM）的交替方向法可以有效地求解凸SSC模型。此外，我们提出了使用多视图数据信息来扩展SSC以提高聚类性能的成对稀疏光谱聚类（PSSC）。与现实世界数据集上的几个基线进行实验比较证明了我们提出的方法的有效性。

##### URL
[http://arxiv.org/abs/1511.06860](http://arxiv.org/abs/1511.06860)

##### PDF
[http://arxiv.org/pdf/1511.06860](http://arxiv.org/pdf/1511.06860)

