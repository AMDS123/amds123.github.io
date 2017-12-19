---
layout: post
title: "Improved Residual Vector Quantization for High-dimensional Approximate Nearest Neighbor Search"
date: 2015-09-17 10:19:37
categories: arXiv_CV
tags: arXiv_CV
author: Shicong Liu, Hongtao Lu, Junru Shao
mathjax: true
---

* content
{:toc}

##### Abstract
Quantization methods have been introduced to perform large scale approximate nearest search tasks. Residual Vector Quantization (RVQ) is one of the effective quantization methods. RVQ uses a multi-stage codebook learning scheme to lower the quantization error stage by stage. However, there are two major limitations for RVQ when applied to on high-dimensional approximate nearest neighbor search: 1. The performance gain diminishes quickly with added stages. 2. Encoding a vector with RVQ is actually NP-hard. In this paper, we propose an improved residual vector quantization (IRVQ) method, our IRVQ learns codebook with a hybrid method of subspace clustering and warm-started k-means on each stage to prevent performance gain from dropping, and uses a multi-path encoding scheme to encode a vector with lower distortion. Experimental results on the benchmark datasets show that our method gives substantially improves RVQ and delivers better performance compared to the state-of-the-art.

##### Abstract (translated by Google)
已经引入量化方法来执行大规模近似最近的搜索任务。残差矢量量化（RVQ）是有效的量化方法之一。 RVQ采用多级码书学习方案逐级降低量化误差。然而，当应用于高维近似最近邻搜索时，RVQ存在两个主要限制：1.随着阶段的增加，性能增益迅速减小。 2.用RVQ编码一个矢量实际上是NP-hard。在本文中，我们提出了一种改进的残差矢量量化（IRVQ）方法，我们的IRVQ学习码书，在每个阶段使用子空间聚类和热启动k-means的混合方法来防止性能增益下降，并且使用多路径编码方案来编码具有较低失真的矢量。基准数据集上的实验结果显示，与最先进的技术相比，我们的方法大大提高了RVQ并提供了更好的性能。

##### URL
[https://arxiv.org/abs/1509.05195](https://arxiv.org/abs/1509.05195)

##### PDF
[https://arxiv.org/pdf/1509.05195](https://arxiv.org/pdf/1509.05195)

