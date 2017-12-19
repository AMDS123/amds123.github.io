---
layout: post
title: "Diverse Landmark Sampling from Determinantal Point Processes for Scalable Manifold Learning"
date: 2015-03-11 21:09:28
categories: arXiv_CV
tags: arXiv_CV Sparse Embedding
author: Christian Wachinger, Polina Golland
mathjax: true
---

* content
{:toc}

##### Abstract
High computational costs of manifold learning prohibit its application for large point sets. A common strategy to overcome this problem is to perform dimensionality reduction on selected landmarks and to successively embed the entire dataset with the Nystr\"om method. The two main challenges that arise are: (i) the landmarks selected in non-Euclidean geometries must result in a low reconstruction error, (ii) the graph constructed from sparsely sampled landmarks must approximate the manifold well. We propose the sampling of landmarks from determinantal distributions on non-Euclidean spaces. Since current determinantal sampling algorithms have the same complexity as those for manifold learning, we present an efficient approximation running in linear time. Further, we recover the local geometry after the sparsification by assigning each landmark a local covariance matrix, estimated from the original point set. The resulting neighborhood selection based on the Bhattacharyya distance improves the embedding of sparsely sampled manifolds. Our experiments show a significant performance improvement compared to state-of-the-art landmark selection techniques.

##### Abstract (translated by Google)
流形学习的高计算成本阻止了其应用于大点集。克服这个问题的一个常用策略是对选定的地标进行维数降低，并用Nystrom方法连续嵌入整个数据集。出现的两个主要挑战是：（i）在非欧几里德几何中选择的地标必须从而导致重构误差较小;（ii）由稀疏采样点构成的图必须逼近流形井;我们提出从非欧几里德空间上行列式分布的标志点采样;由于目前的行列式采样算法具有与流形学习，我们提出了一个有效的近似在线性时间运行，此外，我们恢复稀疏后的局部几何，通过分配每个界标一个局部的协方差矩阵，从原始点集估计，基于Bhattacharyya距离产生的邻域选择改善嵌入稀疏采样流形。我们的实验显示了一个重要的性能与最先进的地标选择技术相比，这是一个进步。

##### URL
[https://arxiv.org/abs/1503.03506](https://arxiv.org/abs/1503.03506)

##### PDF
[https://arxiv.org/pdf/1503.03506](https://arxiv.org/pdf/1503.03506)

