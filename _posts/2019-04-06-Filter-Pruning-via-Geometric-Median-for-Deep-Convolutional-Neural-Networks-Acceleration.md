---
layout: post
title: "Filter Pruning via Geometric Median for Deep Convolutional Neural Networks Acceleration"
date: 2019-04-06 03:59:11
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Yang He, Ping Liu, Ziwei Wang, Zhilan Hu, Yi Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Previous works utilized ''smaller-norm-less-important'' criterion to prune filters with smaller norm values in a convolutional neural network. In this paper, we analyze this norm-based criterion and point out that its effectiveness depends on two requirements that are not always met: (1) the norm deviation of the filters should be large; (2) the minimum norm of the filters should be small. To solve this problem, we propose a novel filter pruning method, namely Filter Pruning via Geometric Median (FPGM), to compress the model regardless of those two requirements. Unlike previous methods, FPGM compresses CNN models by pruning filters with redundancy, rather than those with ''relatively less'' importance. When applied to two image classification benchmarks, our method validates its usefulness and strengths. Notably, on CIFAR-10, FPGM reduces more than 52% FLOPs on ResNet-110 with even 2.69% relative accuracy improvement. Moreover, on ILSVRC-2012, FPGM reduces more than 42% FLOPs on ResNet-101 without top-5 accuracy drop, which has advanced the state-of-the-art. Code is publicly available on GitHub: https://github.com/he-y/filter-pruning-geometric-median

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.00250](http://arxiv.org/abs/1811.00250)

##### PDF
[http://arxiv.org/pdf/1811.00250](http://arxiv.org/pdf/1811.00250)

