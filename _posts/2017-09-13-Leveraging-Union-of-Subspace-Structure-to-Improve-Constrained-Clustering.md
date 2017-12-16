---
layout: post
title: "Leveraging Union of Subspace Structure to Improve Constrained Clustering"
date: 2017-09-13 21:17:33
categories: arXiv_CV
tags: arXiv_CV Face Classification
author: John Lipor, Laura Balzano
mathjax: true
---

* content
{:toc}

##### Abstract
Many clustering problems in computer vision and other contexts are also classification problems, where each cluster shares a meaningful label. Subspace clustering algorithms in particular are often applied to problems that fit this description, for example with face images or handwritten digits. While it is straightforward to request human input on these datasets, our goal is to reduce this input as much as possible. We present a pairwise-constrained clustering algorithm that actively selects queries based on the union-of-subspaces model. The central step of the algorithm is in querying points of minimum margin between estimated subspaces; analogous to classifier margin, these lie near the decision boundary. We prove that points lying near the intersection of subspaces are points with low margin. Our procedure can be used after any subspace clustering algorithm that outputs an affinity matrix. We demonstrate on several datasets that our algorithm drives the clustering error down considerably faster than the state-of-the-art active query algorithms on datasets with subspace structure and is competitive on other datasets.

##### Abstract (translated by Google)
计算机视觉和其他环境中的许多聚类问题也是分类问题，其中每个聚类分享一个有意义的标签。特别是子空间聚类算法经常被应用于符合这个描述的问题，例如面部图像或手写数字。尽管在这些数据集上请求人工输入很简单，但我们的目标是尽可能减少输入。我们提出了一个成对约束聚类算法，主动选择基于子空间联合模型的查询。该算法的核心步骤是查询估计子空间之间的最小余量点;类似于分类边界，这些位于决策边界附近。我们证明位于子空间交点附近的点是低边的点。我们的程序可以在输出亲和度矩阵的任何子空间聚类算法之后使用。我们在几个数据集上演示了我们的算法驱动聚类错误的速度明显快于具有子空间结构的数据集上的最先进的主动查询算法，并且在其他数据集上具有竞争力。

##### URL
[https://arxiv.org/abs/1608.02146](https://arxiv.org/abs/1608.02146)

##### PDF
[https://arxiv.org/pdf/1608.02146](https://arxiv.org/pdf/1608.02146)

