---
layout: post
title: "Linkage Based Face Clustering via Graph Convolution Network"
date: 2019-03-27 09:36:23
categories: arXiv_CV
tags: arXiv_CV Face Prediction Relation
author: Zhongdao Wang, Liang Zheng, Yali Li, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present an accurate and scalable approach to the face clustering task. We aim at grouping a set of faces by their potential identities. We formulate this task as a link prediction problem: a link exists between two faces if they are of the same identity. The key idea is that we find the local context in the feature space around an instance (face) contains rich information about the linkage relationship between this instance and its neighbors. By constructing sub-graphs around each instance as input data, which depict the local context, we utilize the graph convolution network (GCN) to perform reasoning and infer the likelihood of linkage between pairs in the sub-graphs. Experiments show that our method is more robust to the complex distribution of faces than conventional methods, yielding favorably comparable results to state-of-the-art methods on standard face clustering benchmarks, and is scalable to large datasets. Furthermore, we show that the proposed method does not need the number of clusters as prior, is aware of noises and outliers, and can be extended to a multi-view version for more accurate clustering accuracy.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.11306](http://arxiv.org/abs/1903.11306)

##### PDF
[http://arxiv.org/pdf/1903.11306](http://arxiv.org/pdf/1903.11306)

