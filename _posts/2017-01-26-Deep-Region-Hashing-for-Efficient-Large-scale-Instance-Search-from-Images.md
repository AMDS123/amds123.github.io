---
layout: post
title: "Deep Region Hashing for Efficient Large-scale Instance Search from Images"
date: 2017-01-26 23:18:58
categories: arXiv_CV
tags: arXiv_CV CNN
author: Jingkuan Song, Tao He, Lianli Gao, Xing Xu, Heng Tao Shen
mathjax: true
---

* content
{:toc}

##### Abstract
Instance Search (INS) is a fundamental problem for many applications, while it is more challenging comparing to traditional image search since the relevancy is defined at the instance level. Existing works have demonstrated the success of many complex ensemble systems that are typically conducted by firstly generating object proposals, and then extracting handcrafted and/or CNN features of each proposal for matching. However, object bounding box proposals and feature extraction are often conducted in two separated steps, thus the effectiveness of these methods collapses. Also, due to the large amount of generated proposals, matching speed becomes the bottleneck that limits its application to large-scale datasets. To tackle these issues, in this paper we propose an effective and efficient Deep Region Hashing (DRH) approach for large-scale INS using an image patch as the query. Specifically, DRH is an end-to-end deep neural network which consists of object proposal, feature extraction, and hash code generation. DRH shares full-image convolutional feature map with the region proposal network, thus enabling nearly cost-free region proposals. Also, each high-dimensional, real-valued region features are mapped onto a low-dimensional, compact binary codes for the efficient object region level matching on large-scale dataset. Experimental results on four datasets show that our DRH can achieve even better performance than the state-of-the-arts in terms of MAP, while the efficiency is improved by nearly 100 times.

##### Abstract (translated by Google)
实例搜索（INS）是许多应用程序的基本问题，而与传统图像搜索相比，实例搜索（INS）更具挑战性，因为相关性是在实例级定义的。现有的作品已经证明了许多复杂的合奏系统的成功，这些合奏系统通常首先产生对象建议，然后提取每个建议的手工和/或CNN特征进行匹配。然而，对象边界框提议和特征提取往往分两步进行，这些方法的有效性崩溃了。另外，由于生成的提议数量较大，匹配速度成为限制其应用于大规模数据集的瓶颈。针对这些问题，本文提出了一种基于图像补丁作为查询的大规模INS的高效深层哈希（DRH）方法。具体而言，DRH是由对象提议，特征提取和哈希码生成组成的端到端深度神经网络。 DRH与地区提案网络共享全图像卷积特征地图，从而实现近乎成本的地区提案。此外，每个高维实值区域特征被映射到低维紧凑二进制代码，用于大规模数据集上的高效对象区域级别匹配。在四个数据集上的实验结果表明，我们的DRH在MAP方面可以达到比现有技术更好的性能，而效率提高了近100倍。

##### URL
[https://arxiv.org/abs/1701.07901](https://arxiv.org/abs/1701.07901)

##### PDF
[https://arxiv.org/pdf/1701.07901](https://arxiv.org/pdf/1701.07901)

