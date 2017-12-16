---
layout: post
title: "Fast k-means based on KNN Graph"
date: 2017-05-04 12:27:28
categories: arXiv_CV
tags: arXiv_CV
author: Cheng-Hao Deng, Wan-Lei Zhao
mathjax: true
---

* content
{:toc}

##### Abstract
In the era of big data, k-means clustering has been widely adopted as a basic processing tool in various contexts. However, its computational cost could be prohibitively high as the data size and the cluster number are large. It is well known that the processing bottleneck of k-means lies in the operation of seeking closest centroid in each iteration. In this paper, a novel solution towards the scalability issue of k-means is presented. In the proposal, k-means is supported by an approximate k-nearest neighbors graph. In the k-means iteration, each data sample is only compared to clusters that its nearest neighbors reside. Since the number of nearest neighbors we consider is much less than k, the processing cost in this step becomes minor and irrelevant to k. The processing bottleneck is therefore overcome. The most interesting thing is that k-nearest neighbor graph is constructed by iteratively calling the fast $k$-means itself. Comparing with existing fast k-means variants, the proposed algorithm achieves hundreds to thousands times speed-up while maintaining high clustering quality. As it is tested on 10 million 512-dimensional data, it takes only 5.2 hours to produce 1 million clusters. In contrast, to fulfill the same scale of clustering, it would take 3 years for traditional k-means.

##### Abstract (translated by Google)
在大数据时代，k-means聚类作为各种情况下的基本处理工具已被广泛采用。然而，由于数据大小和簇数很大，其计算成本可能非常高。众所周知，k-means的处理瓶颈在于每次迭代寻求最接近质心的操作。本文提出了一种解决k-means可扩展性问题的新方法。在该提议中，k-均值由近似k-最近邻图支持。在k-means迭代中，每个数据样本只与最近邻居所在的簇进行比较。由于我们考虑的最近邻居的数量远小于k，所以在这个步骤中的处理成本变得很小并且与k无关。处理瓶颈因此被克服。最有趣的是通过迭代调用快速$ k $ -means来构造k-最近邻图。与现有的快速k均值变种相比，该算法在保持高聚类质量的同时，实现了数百到数千倍的加速。由于在1000万个512维数据上进行测试，生产100万个集群只需要5.2小时。相反，为了达到相同的聚类规模，传统的k均值需要3年的时间。

##### URL
[https://arxiv.org/abs/1705.01813](https://arxiv.org/abs/1705.01813)

##### PDF
[https://arxiv.org/pdf/1705.01813](https://arxiv.org/pdf/1705.01813)

