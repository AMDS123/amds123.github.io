---
layout: post
title: "Path-Invariant Map Networks"
date: 2019-06-04 08:14:47
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation
author: Zaiwei Zhang, Zhenxiao Liang, Lemeng Wu, Xiaowei Zhou, Qixing Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Optimizing a network of maps among a collection of objects/domains (or map synchronization) is a central problem across computer vision and many other relevant fields. Compared to optimizing pairwise maps in isolation, the benefit of map synchronization is that there are natural constraints among a map network that can improve the quality of individual maps. While such self-supervision constraints are well-understood for undirected map networks (e.g., the cycle-consistency constraint), they are under-explored for directed map networks, which naturally arise when maps are given by parametric maps (e.g., a feed-forward neural network). In this paper, we study a natural self-supervision constraint for directed map networks called path-invariance, which enforces that composite maps along different paths between a fixed pair of source and target domains are identical. We introduce path-invariance bases for efficient encoding of the path-invariance constraint and present an algorithm that outputs a path-variance basis with polynomial time and space complexities. We demonstrate the effectiveness of our approach on optimizing object correspondences, estimating dense image maps via neural networks, and semantic segmentation of 3D scenes via map networks of diverse 3D representations. In particular, for 3D semantic segmentation, our approach only requires 8% labeled data from ScanNet to achieve the same performance as training a single 3D segmentation network with 30% to 100% labeled data.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.11647](http://arxiv.org/abs/1812.11647)

##### PDF
[http://arxiv.org/pdf/1812.11647](http://arxiv.org/pdf/1812.11647)

