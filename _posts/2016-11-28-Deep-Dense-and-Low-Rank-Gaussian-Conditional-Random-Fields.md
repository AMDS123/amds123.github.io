---
layout: post
title: "Deep, Dense, and Low-Rank Gaussian Conditional Random Fields"
date: 2016-11-28 10:29:53
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation Embedding Semantic_Segmentation
author: Siddhartha Chandra, Iasonas Kokkinos
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we introduce a fully-connected graph structure in the Deep Gaussian Conditional Random Field (G-CRF) model. For this we express the pairwise interactions between pixels as the inner-products of low-dimensional embeddings, delivered by a new subnetwork of a deep architecture. We efficiently minimize the resulting energy by solving the resulting low-rank linear system with conjugate gradients, and derive an analytic expression for the gradient of our embeddings which allows us to train them end-to-end with backpropagation. We demonstrate the merit of our approach by achieving state of the art results on three challenging Computer Vision benchmarks, namely semantic segmentation, human parts segmentation, and saliency estimation. Our implementation is fully GPU based, built on top of the Caffe library, and will be made publicly available.

##### Abstract (translated by Google)
在这项工作中，我们在深度高斯条件随机场（G-CRF）模型中引入了完全连通的图结构。为此，我们将像素之间的成对交互作为低维嵌入的内积表示，由深度架构的新子网提供。我们通过用共轭梯度求解得到的低秩线性系统来有效地将所产生的能量最小化，并且得到我们嵌入的梯度的分析表达式，这允许我们用反向传播来对它们进行端对端地训练。通过在三个具有挑战性的计算机视觉基准上实现最先进的结果，即语义分割，人体部分分割和显着性估计，我们证明了我们方法的优点。我们的实现完全基于GPU，建立在Caffe库之上，并将公开发布。

##### URL
[https://arxiv.org/abs/1611.09051](https://arxiv.org/abs/1611.09051)

##### PDF
[https://arxiv.org/pdf/1611.09051](https://arxiv.org/pdf/1611.09051)

