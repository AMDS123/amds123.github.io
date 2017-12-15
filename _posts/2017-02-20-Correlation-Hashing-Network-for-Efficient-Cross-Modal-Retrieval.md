---
layout: post
title: "Correlation Hashing Network for Efficient Cross-Modal Retrieval"
date: 2017-02-20 11:25:05
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Relation
author: Yue Cao, Mingsheng Long, Jianmin Wang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing is widely applied to approximate nearest neighbor search for large-scale multimodal retrieval with storage and computation efficiency. Cross-modal hashing improves the quality of hash coding by exploiting semantic correlations across different modalities. Existing cross-modal hashing methods first transform data into low-dimensional feature vectors, and then generate binary codes by another separate quantization step. However, suboptimal hash codes may be generated since the quantization error is not explicitly minimized and the feature representation is not jointly optimized with the binary codes. This paper presents a Correlation Hashing Network (CHN) approach to cross-modal hashing, which jointly learns good data representation tailored to hash coding and formally controls the quantization error. The proposed CHN is a hybrid deep architecture that constitutes a convolutional neural network for learning good image representations, a multilayer perception for learning good text representations, two hashing layers for generating compact binary codes, and a structured max-margin loss that integrates all things together to enable learning similarity-preserving and high-quality hash codes. Extensive empirical study shows that CHN yields state of the art cross-modal retrieval performance on standard benchmarks.

##### Abstract (translated by Google)
散列法被广泛应用于大规模多模式检索的近似最近邻搜索，具有存储和计算效率。跨模态散列通过利用不同模态的语义相关来改进散列编码的质量。现有的交叉模式散列方法首先将数据转换为低维特征向量，然后通过另一个单独的量化步骤产生二进制代码。然而，由于量化误差未被明确地最小化并且特征表示不与二进制码一起被优化，所以可以生成次优化的哈希码。本文提出了一种相关散列网络（CHN）方法来交叉模式散列，它共同学习了针对散列编码量身定制的良好数据表示，并正式控制量化误差。所提出的CHN是一种混合型深层架构，它构成了用于学习良好图像表示的卷积神经网络，用于学习良好文本表示的多层感知，用于生成紧凑二进制代码的两个哈希层以及将所有事物集成在一起的结构化最大边缘损失使学习相似性保持和高质量的哈希码。大量的实证研究表明CHN在标准基准测试中获得了最先进的跨模态检索性能。

##### URL
[https://arxiv.org/abs/1602.06697](https://arxiv.org/abs/1602.06697)

##### PDF
[https://arxiv.org/pdf/1602.06697](https://arxiv.org/pdf/1602.06697)

