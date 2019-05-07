---
layout: post
title: "Essential Tensor Learning for Multi-view Spectral Clustering"
date: 2019-05-06 14:10:05
categories: arXiv_CV
tags: arXiv_CV Attention Relation
author: Jianlong Wu, Zhouchen Lin, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-view clustering attracts much attention recently, which aims to take advantage of multi-view information to improve the performance of clustering. However, most recent work mainly focus on self-representation based subspace clustering, which is of high computation complexity. In this paper, we focus on the Markov chain based spectral clustering method and propose a novel essential tensor learning method to explore the high order correlations for multi-view representation. We first construct a tensor based on multi-view transition probability matrices of the Markov chain. By incorporating the idea from robust principle component analysis, tensor singular value decomposition (t-SVD) based tensor nuclear norm is imposed to preserve the low-rank property of the essential tensor, which can well capture the principle information from multiple views. We also employ the tensor rotation operator for this task to better investigate the relationship among views as well as reduce the computation complexity. The proposed method can be efficiently optimized by the alternating direction method of multipliers~(ADMM). Extensive experiments on six real world datasets corresponding to five different applications show that our method achieves superior performance over other state-of-the-art methods.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1807.03602](http://arxiv.org/abs/1807.03602)

##### PDF
[http://arxiv.org/pdf/1807.03602](http://arxiv.org/pdf/1807.03602)

