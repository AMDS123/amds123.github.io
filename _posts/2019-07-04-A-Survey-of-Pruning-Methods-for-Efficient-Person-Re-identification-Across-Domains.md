---
layout: post
title: "A Survey of Pruning Methods for Efficient Person Re-identification Across Domains"
date: 2019-07-04 18:02:53
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification Survey Deep_Learning Recognition
author: Hugo Masson, Amran Bhuiyan, Le Thanh Nguyen-Meidine, Mehrsan Javan, Parthipan Siva, Ismail Ben Ayed, Eric Granger
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed a substantial increase in the deep learning architectures proposed for visual recognition tasks like person re-identification, where individuals must be recognized over multiple distributed cameras. Although deep Siamese networks have greatly improved the state-of-the-art accuracy, the computational complexity of the CNNs used for feature extraction remains an issue, hindering their deployment on platforms with with limited resources, or in applications with real-time constraints. Thus, there is an obvious advantage to compressing these architectures without significantly decreasing their accuracy. This paper provides a survey of state-of-the-art pruning techniques that are suitable for compressing deep Siamese networks applied to person re-identification. These techniques are analysed according to their pruning criteria and strategy, and according to different design scenarios for exploiting pruning methods to fine-tuning networks for target applications. Experimental results obtained using Siamese networks with ResNet feature extractors, and multiple benchmarks re-identification datasets, indicate that pruning can considerably reduce network complexity while maintaining a high level of accuracy. In scenarios where pruning is performed with large pre-training or fine-tuning datasets, the number of FLOPS required by the ResNet feature extractor is reduced by half, while maintaining a comparable rank-1 accuracy (within 1\% of the original model). Pruning while training a larger CNNs can also provide a significantly better performance than fine-tuning smaller ones.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02547](http://arxiv.org/abs/1907.02547)

##### PDF
[http://arxiv.org/pdf/1907.02547](http://arxiv.org/pdf/1907.02547)

