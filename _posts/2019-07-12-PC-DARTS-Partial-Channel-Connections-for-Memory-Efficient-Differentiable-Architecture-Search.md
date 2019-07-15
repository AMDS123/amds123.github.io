---
layout: post
title: "PC-DARTS: Partial Channel Connections for Memory-Efficient Differentiable Architecture Search"
date: 2019-07-12 13:26:09
categories: arXiv_CV
tags: arXiv_CV
author: Yuhui Xu, Lingxi Xie, Xiaopeng Zhang, Xin Chen, Guo-Jun Qi, Qi Tian, Hongkai Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
Differentiable architecture search (DARTS) provided a fast solution in finding effective network architectures, but suffered from large memory and computing overheads in jointly training a super-net and search for an optimal architecture. In this paper, we present a novel approach, namely Partially-Connected DARTS, by sampling a small part of super-net to reduce the redundancy in network space, thereby performing a more efficient search without comprising the performance. In particular, we perform operation search in a subset of channels and leave the held out part unchanged. This strategy may suffer from an undesired inconsistency on selecting the edges of super-net caused by the sampling of different channels. We solve it by introducing edge normalization, which adds a new set of edge-level hyper-parameters during search to reduce uncertainty in search. Thanks to the reduced memory cost, PC-DARTS can be trained with a larger batch size and, consequently, enjoys both faster speed and higher training stability. Experimental results demonstrate the effectiveness of the proposed method. Specifically, we achieve an error rate of 2:57% on CIFAR10 within merely 0:1 GPU-days for architecture search, and a state-of-the-art top-1 error rate of 24:2% on ImageNet (under the mobile setting) within 3.8 GPU-days for search. We have made our code available: https://github.com/yuhuixu1993/PC-DARTS.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05737](http://arxiv.org/abs/1907.05737)

##### PDF
[http://arxiv.org/pdf/1907.05737](http://arxiv.org/pdf/1907.05737)

