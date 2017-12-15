---
layout: post
title: "Clustering Millions of Faces by Identity"
date: 2016-04-04 18:53:12
categories: arXiv_CV
tags: arXiv_CV Face
author: Charles Otto, Dayong Wang, Anil K. Jain
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we attempt to address the following problem: Given a large number of unlabeled face images, cluster them into the individual identities present in this data. We consider this a relevant problem in different application scenarios ranging from social media to law enforcement. In large-scale scenarios the number of faces in the collection can be of the order of hundreds of million, while the number of clusters can range from a few thousand to millions--leading to difficulties in terms of both run-time complexity and evaluating clustering and per-cluster quality. An efficient and effective Rank-Order clustering algorithm is developed to achieve the desired scalability, and better clustering accuracy than other well-known algorithms such as k-means and spectral clustering. We cluster up to 123 million face images into over 10 million clusters, and analyze the results in terms of both external cluster quality measures (known face labels) and internal cluster quality measures (unknown face labels) and run-time. Our algorithm achieves an F-measure of 0.87 on a benchmark unconstrained face dataset (LFW, consisting of 13K faces), and 0.27 on the largest dataset considered (13K images in LFW, plus 123M distractor images). Additionally, we present preliminary work on video frame clustering (achieving 0.71 F-measure when clustering all frames in the benchmark YouTube Faces dataset). A per-cluster quality measure is developed which can be used to rank individual clusters and to automatically identify a subset of good quality clusters for manual exploration.

##### Abstract (translated by Google)
在这项工作中，我们试图解决以下问题：给定大量未标记的人脸图像，将它们聚类成数据中存在的个人身份。我们认为这是从社交媒体到执法等不同应用场景的一个相关问题。在大规模场景中，集合中的人脸数量可能达到数亿人，而集群的数量可能从几千到几百万不等，从而导致运行时复杂性和评估方面的困难聚类和每个群集的质量。 Rank-Order聚类算法的有效性和有效性被开发来实现期望的可扩展性，并且比其他众所周知的算法如k均值和谱聚类更好的聚类精度。我们将1.23亿张人脸图像聚类到超过1000万个聚类中，并根据外部聚类质量度量（已知人脸标签）和内部聚类质量度量（未知人脸标签）和运行时间来分析结果。我们的算法在基准无约束人脸数据集（LFW，由13K个脸部组成）上实现0.87的F-measure，并且在考虑的最大数据集（在LFW中的13K个图像，加上123M牵引图像）上为0.27。此外，我们还介绍了视频帧聚类的初步工作（将基准YouTube Faces数据集中的所有帧聚类时，实现了0.71的F-measure）。开发了一个集群质量度量，可以用来对单个集群进行排序，并自动识别用于手动探索的优质集群子集。

##### URL
[https://arxiv.org/abs/1604.00989](https://arxiv.org/abs/1604.00989)

##### PDF
[https://arxiv.org/pdf/1604.00989](https://arxiv.org/pdf/1604.00989)

