---
layout: post
title: "Learning Two-View Correspondences and Geometry Using Order-Aware Network"
date: 2019-08-14 05:42:18
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Jiahui Zhang, Dawei Sun, Zixin Luo, Anbang Yao, Lei Zhou, Tianwei Shen, Yurong Chen, Long Quan, Hongen Liao
mathjax: true
---

* content
{:toc}

##### Abstract
Establishing correspondences between two images requires both local and global spatial context. Given putative correspondences of feature points in two views, in this paper, we propose Order-Aware Network, which infers the probabilities of correspondences being inliers and regresses the relative pose encoded by the essential matrix. Specifically, this proposed network is built hierarchically and comprises three novel operations. First, to capture the local context of sparse correspondences, the network clusters unordered input correspondences by learning a soft assignment matrix. These clusters are in a canonical order and invariant to input permutations. Next, the clusters are spatially correlated to form the global context of correspondences. After that, the context-encoded clusters are recovered back to the original size through a proposed upsampling operator. We intensively experiment on both outdoor and indoor datasets. The accuracy of the two-view geometry and correspondences are significantly improved over the state-of-the-arts. Code will be available at https://github.com/zjhthu/OANet.git.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.04964](http://arxiv.org/abs/1908.04964)

##### PDF
[http://arxiv.org/pdf/1908.04964](http://arxiv.org/pdf/1908.04964)

