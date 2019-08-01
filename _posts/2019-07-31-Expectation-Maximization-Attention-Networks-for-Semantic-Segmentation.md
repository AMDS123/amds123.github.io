---
layout: post
title: "Expectation-Maximization Attention Networks for Semantic Segmentation"
date: 2019-07-31 11:35:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention Semantic_Segmentation Relation
author: Xia Li, Zhisheng Zhong, Jianlong Wu, Yibo Yang, Zhouchen Lin, Hong Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Self-attention mechanism has been widely used for various tasks. It is designed to compute the representation of each position by a weighted sum of the features at all positions. Thus, it can capture long-range relations for computer vision tasks. However, it is computationally consuming. Since the attention maps are computed w.r.t all other positions. In this paper, we formulate the attention mechanism into an expectation-maximization manner and iteratively estimate a much more compact set of bases upon which the attention maps are computed. By a weighted summation upon these bases, the resulting representation is low-rank and deprecates noisy information from the input. The proposed Expectation-Maximization Attention (EMA) module is robust to the variance of input and is also friendly in memory and computation. Moreover, we set up the bases maintenance and normalization methods to stabilize its training procedure. We conduct extensive experiments on popular semantic segmentation benchmarks including PASCAL VOC, PASCAL Context and COCO Stuff, on which we set new records.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13426](http://arxiv.org/abs/1907.13426)

##### PDF
[http://arxiv.org/pdf/1907.13426](http://arxiv.org/pdf/1907.13426)

