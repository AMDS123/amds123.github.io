---
layout: post
title: "C2S2: Cost-aware Channel Sparse Selection for Progressive Network Pruning"
date: 2019-04-06 18:40:06
categories: arXiv_CV
tags: arXiv_CV Sparse Segmentation Image_Classification Semantic_Segmentation Optimization Classification
author: Chih-Yao Chiu, Hwann-Tzong Chen, Tyng-Luh Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This paper describes a channel-selection approach for simplifying deep neural networks. Specifically, we propose a new type of generic network layer, called pruning layer, to seamlessly augment a given pre-trained model for compression. Each pruning layer, comprising $1 \times 1$ depth-wise kernels, is represented with a dual format: one is real-valued and the other is binary. The former enables a two-phase optimization process of network pruning to operate with an end-to-end differentiable network, and the latter yields the mask information for channel selection. Our method progressively performs the pruning task layer-wise, and achieves channel selection according to a sparsity criterion to favor pruning more channels. We also develop a cost-aware mechanism to prevent the compression from sacrificing the expected network performance. Our results for compressing several benchmark deep networks on image classification and semantic segmentation are comparable to those by state-of-the-art.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03508](http://arxiv.org/abs/1904.03508)

##### PDF
[http://arxiv.org/pdf/1904.03508](http://arxiv.org/pdf/1904.03508)

