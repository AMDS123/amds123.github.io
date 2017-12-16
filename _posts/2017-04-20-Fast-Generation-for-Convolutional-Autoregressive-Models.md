---
layout: post
title: "Fast Generation for Convolutional Autoregressive Models"
date: 2017-04-20 04:13:21
categories: arXiv_CV
tags: arXiv_CV CNN
author: Prajit Ramachandran, Tom Le Paine, Pooya Khorrami, Mohammad Babaeizadeh, Shiyu Chang, Yang Zhang, Mark A. Hasegawa-Johnson, Roy H. Campbell, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional autoregressive models have recently demonstrated state-of-the-art performance on a number of generation tasks. While fast, parallel training methods have been crucial for their success, generation is typically implemented in a na\"{i}ve fashion where redundant computations are unnecessarily repeated. This results in slow generation, making such models infeasible for production environments. In this work, we describe a method to speed up generation in convolutional autoregressive models. The key idea is to cache hidden states to avoid redundant computation. We apply our fast generation method to the Wavenet and PixelCNN++ models and achieve up to $21\times$ and $183\times$ speedups respectively.

##### Abstract (translated by Google)
卷积自回归模型最近在许多发电任务中展现了最先进的性能。虽然快速的并行训练方法对于他们的成功至关重要，但是一代人通常是以不必要的方式重复计算冗余的方式来实施的，这导致生成缓慢，使得这样的模型在生产环境中是不可行的。我们描述了一种在卷积自回归模型中加速生成的方法，其关键思想是缓存隐藏状态以避免冗余计算。我们将快速生成方法应用于Wavenet和PixelCNN ++模型，实现高达$ 21 \ times $和$ 183 \ times $ speedups分别。

##### URL
[https://arxiv.org/abs/1704.06001](https://arxiv.org/abs/1704.06001)

##### PDF
[https://arxiv.org/pdf/1704.06001](https://arxiv.org/pdf/1704.06001)

