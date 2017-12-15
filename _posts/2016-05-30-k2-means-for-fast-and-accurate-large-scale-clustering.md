---
layout: post
title: "k2-means for fast and accurate large scale clustering"
date: 2016-05-30 16:17:45
categories: arXiv_CV
tags: arXiv_CV
author: Eirikur Agustsson, Radu Timofte, Luc Van Gool
mathjax: true
---

* content
{:toc}

##### Abstract
We propose k^2-means, a new clustering method which efficiently copes with large numbers of clusters and achieves low energy solutions. k^2-means builds upon the standard k-means (Lloyd's algorithm) and combines a new strategy to accelerate the convergence with a new low time complexity divisive initialization. The accelerated convergence is achieved through only looking at k_n nearest clusters and using triangle inequality bounds in the assignment step while the divisive initialization employs an optimal 2-clustering along a direction. The worst-case time complexity per iteration of our k^2-means is O(nk_nd+k^2d), where d is the dimension of the n data points and k is the number of clusters and usually n << k << k_n. Compared to k-means' O(nkd) complexity, our k^2-means complexity is significantly lower, at the expense of slightly increasing the memory complexity by O(nk_n+k^2). In our extensive experiments k^2-means is order(s) of magnitude faster than standard methods in computing accurate clusterings on several standard datasets and settings with hundreds of clusters and high dimensional data. Moreover, the proposed divisive initialization generally leads to clustering energies comparable to those achieved with the standard k-means++ initialization, while being significantly faster.

##### Abstract (translated by Google)
我们提出了k ^ 2均值聚类方法，该方法可以有效地处理大量的聚类并实现低能量解。 k ^ 2-意味着建立在标准的k-means（Lloyd算法）之上，并结合了一个新的策略来加速收敛，并有一个新的低时间复杂度分裂初始化。加速收敛是通过仅考虑k_n个最近簇并在分配步骤中使用三角形不等式边界来实现的，而分裂初始化沿着一个方向采用最优2-聚类。每k次迭代的最坏情况时间复杂度为O（nk_nd + k ^ 2d），其中d是n个数据点的维数，k是簇的数量，通常n << k << k_n。与k-means'O（nkd）复杂度相比，我们的k ^ 2均值复杂度显着降低，代价是通过O（nk_n + k ^ 2）稍微增加内存复杂度。在我们广泛的实验中，k ^ 2-means在数个标准数据集和具有数百个聚类和高维数据的设置上计算精确聚类时，比标准方法的数量级更快。此外，所提出的分裂初始化通常导致与通过标准k-means ++初始化所获得的聚类能量相当的聚类能量，同时明显更快。

##### URL
[https://arxiv.org/abs/1605.09299](https://arxiv.org/abs/1605.09299)

##### PDF
[https://arxiv.org/pdf/1605.09299](https://arxiv.org/pdf/1605.09299)

