---
layout: post
title: "Softmax Dissection: Towards Understanding Intra- and Inter-clas Objective for Embedding Learning"
date: 2019-08-04 06:50:20
categories: arXiv_CV
tags: arXiv_CV Face Embedding Recognition Face_Recognition
author: Lanqing He, Zhongdao Wang, Yali Li, Shengjin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
The softmax loss and its variants are widely used as objectives for embedding learning, especially in applications like face recognition. However, the intra- and inter-class objectives in the softmax loss are entangled, therefore a well-optimized inter-class objective leads to relaxation on the intra-class objective, and vice versa. In this paper, we propose to dissect the softmax loss into independent intra- and inter-class objective (D-Softmax). With D-Softmax as objective, we can have a clear understanding of both the intra- and inter-class objective, therefore it is straightforward to tune each part to the best state. Furthermore, we find the computation of the inter-class objective is redundant and propose two sampling-based variants of D-Softmax to reduce the computation cost. Training with regular-scale data, experiments in face verification show D-Softmax is favorably comparable to existing losses such as SphereFace and ArcFace. Training with massive-scale data, experiments show the fast variants of D-Softmax significantly accelerates the training process (such as 64x) with only a minor sacrifice in performance, outperforming existing acceleration methods of softmax in terms of both performance and efficiency.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.01281](http://arxiv.org/abs/1908.01281)

##### PDF
[http://arxiv.org/pdf/1908.01281](http://arxiv.org/pdf/1908.01281)

