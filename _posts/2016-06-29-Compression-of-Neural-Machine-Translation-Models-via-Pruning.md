---
layout: post
title: "Compression of Neural Machine Translation Models via Pruning"
date: 2016-06-29 20:36:23
categories: arXiv_CL
tags: arXiv_CL NMT Deep_Learning
author: Abigail See, Minh-Thang Luong, Christopher D. Manning
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT), like many other deep learning domains, typically suffers from over-parameterization, resulting in large storage sizes. This paper examines three simple magnitude-based pruning schemes to compress NMT models, namely class-blind, class-uniform, and class-distribution, which differ in terms of how pruning thresholds are computed for the different classes of weights in the NMT architecture. We demonstrate the efficacy of weight pruning as a compression technique for a state-of-the-art NMT system. We show that an NMT model with over 200 million parameters can be pruned by 40% with very little performance loss as measured on the WMT'14 English-German translation task. This sheds light on the distribution of redundancy in the NMT architecture. Our main result is that with retraining, we can recover and even surpass the original performance with an 80%-pruned model.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1606.09274](https://arxiv.org/abs/1606.09274)

##### PDF
[https://arxiv.org/pdf/1606.09274](https://arxiv.org/pdf/1606.09274)

