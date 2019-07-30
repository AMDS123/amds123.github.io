---
layout: post
title: "Interlaced Sparse Self-Attention for Semantic Segmentation"
date: 2019-07-29 08:33:32
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Attention Semantic_Segmentation
author: Lang Huang, Yuhui Yuan, Jianyuan Guo, Chao Zhang, Xilin Chen, Jingdong Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we present a so-called interlaced sparse self-attention approach to improve the efficiency of the \emph{self-attention} mechanism for semantic segmentation. The main idea is that we factorize the dense affinity matrix as the product of two sparse affinity matrices. There are two successive attention modules each estimating a sparse affinity matrix. The first attention module is used to estimate the affinities within a subset of positions that have long spatial interval distances and the second attention module is used to estimate the affinities within a subset of positions that have short spatial interval distances. These two attention modules are designed so that each position is able to receive the information from all the other positions. In contrast to the original self-attention module, our approach decreases the computation and memory complexity substantially especially when processing high-resolution feature maps. We empirically verify the effectiveness of our approach on six challenging semantic segmentation benchmarks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.12273](http://arxiv.org/abs/1907.12273)

##### PDF
[http://arxiv.org/pdf/1907.12273](http://arxiv.org/pdf/1907.12273)

