---
layout: post
title: "Learning with $ell^{0}$-Graph: $ell^{0}$-Induced Sparse Subspace Clustering"
date: 2015-11-18 07:11:42
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Yingzhen Yang, Jiashi Feng, Jianchao Yang, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Sparse subspace clustering methods, such as Sparse Subspace Clustering (SSC) \cite{ElhamifarV13} and $\ell^{1}$-graph \cite{YanW09,ChengYYFH10}, are effective in partitioning the data that lie in a union of subspaces. Most of those methods use $\ell^{1}$-norm or $\ell^{2}$-norm with thresholding to impose the sparsity of the constructed sparse similarity graph, and certain assumptions, e.g. independence or disjointness, on the subspaces are required to obtain the subspace-sparse representation, which is the key to their success. Such assumptions are not guaranteed to hold in practice and they limit the application of sparse subspace clustering on subspaces with general location. In this paper, we propose a new sparse subspace clustering method named $\ell^{0}$-graph. In contrast to the required assumptions on subspaces for most existing sparse subspace clustering methods, it is proved that subspace-sparse representation can be obtained by $\ell^{0}$-graph for arbitrary distinct underlying subspaces almost surely under the mild i.i.d. assumption on the data generation. We develop a proximal method to obtain the sub-optimal solution to the optimization problem of $\ell^{0}$-graph with proved guarantee of convergence. Moreover, we propose a regularized $\ell^{0}$-graph that encourages nearby data to have similar neighbors so that the similarity graph is more aligned within each cluster and the graph connectivity issue is alleviated. Extensive experimental results on various data sets demonstrate the superiority of $\ell^{0}$-graph compared to other competing clustering methods, as well as the effectiveness of regularized $\ell^{0}$-graph.

##### Abstract (translated by Google)
稀疏子空间聚类方法，例如稀疏子空间聚类（SSC）\ cite {ElhamifarV13}和$ \ ell ^ {1} $  -  graph \ cite {YanW09，ChengYYFH10}在划分位于子空间联合中的数据。这些方法中的大多数使用具有阈值的$ \ ell ^ {1} $  - 范数或$ \ ell ^ {2} $  - 范数来强加所构造的稀疏相似性图的稀疏性，并且某些假设例如独立性或不相交性，子空间需要获得子空间 - 稀疏表示，这是他们成功的关键。这样的假设在实践中不能保证，并且限制了在具有一般位置的子空间上的稀疏子空间聚类的应用。本文提出了一种新的稀疏子空间聚类方法$ \ ell ^ {0} $  -  graph。与大多数现有稀疏子空间聚类方法所需的子空间假设相比，证明了子空间稀疏表示可以通过$ \ ell ^ {0} $  -  graph获得任意不同的基本子空间，几乎可以肯定地在温和的i.i.d.数据生成的假设。我们开发了一种近似方法来获得具有收敛性证明的$ \ ell ^ {0} $  - 图的优化问题的次优解。此外，我们提出了一个正则化的$ \ ell {0} $  - 图，鼓励附近的数据具有相似的邻居，以便相似图在每个聚类内更加一致，并且图连通性问题得到缓解。在各种数据集上的广泛的实验结果证明了与其他竞争聚类方法相比，$ \ ell ^ {0} $  - 图的优越性以及正则化$ \ ell ^ {0} $  - 图的有效性。

##### URL
[https://arxiv.org/abs/1510.08520](https://arxiv.org/abs/1510.08520)

##### PDF
[https://arxiv.org/pdf/1510.08520](https://arxiv.org/pdf/1510.08520)

