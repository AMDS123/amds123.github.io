---
layout: post
title: "Deep Stochastic Attraction and Repulsion Embedding for Image Based Localization"
date: 2018-08-27 10:52:44
categories: arXiv_CV
tags: arXiv_CV Image_Caption Embedding CNN
author: Liu Liu, Hongdong Li, Yuchao Dai
mathjax: true
---

* content
{:toc}

##### Abstract
This paper tackles the problem of large-scale image-based localization where the geographical location at which a query image was taken is estimated by retrieving geo-tagged reference images depicting the same place from a large database. For this problem, an important and yet under-researched issue is how to learn discriminative image representations that are best tailored to the task of geo-localization. 
 Aiming to find a novel image representation having higher location-discriminating power, this paper presents the following contributions: 1) we represent a place (location) as a set of exemplar images depicting the same landmarks, instead of some pre-defined geographic locations by partitioning the world; 2) we advocate the use of competitive learning among places, directly via feature embeddings, aiming to maximize similarities among intra-class images while minimizing similarities among inter-class images. This represents a significant departure from the state-of-the-art IBL methods using triplet ranking loss, which only enforces intra-place visual similarities are bigger than inter-place ones; 3) we propose a new Stochastic Attraction and Repulsion Embedding (SARE) loss function to facilitate the competitive learning. Our SARE loss is easy to implement and pluggable to any Convolutional Neural Network. Experiments show that the method improves localization performance on standard benchmarks by a large margin.

##### Abstract (translated by Google)
本文解决了大规模基于图像的定位问题，其中通过从大型数据库中检索描绘相同位置的地理标记参考图像来估计拍摄查询图像的地理位置。对于这个问题，一个重要但尚未研究的问题是如何学习最适合地理定位任务的判别图像表示。
 为了找到具有更高位置辨别力的新颖图像表示，本文提出了以下贡献：1）我们将一个地点（位置）表示为描绘相同地标的一组示例图像，而不是一些预先定义的地理位置划分世界; 2）我们主张通过特征嵌入直接在场所之间使用竞争性学习，旨在最大化类内图像之间的相似性，同时最小化类间图像之间的相似性。这代表了与使用三重排名损失的最先进的IBL方法的显着不同，其仅强制内部视觉相似性大于地点之间的相似性; 3）我们提出了一种新的随机吸引和排斥嵌入（SARE）损失函数，以促进竞争学习。我们的SARE丢失易于实现并可插入任何卷积神经网络。实验表明，该方法大大提高了标准基准测试的定位性能。

##### URL
[http://arxiv.org/abs/1808.08779](http://arxiv.org/abs/1808.08779)

##### PDF
[http://arxiv.org/pdf/1808.08779](http://arxiv.org/pdf/1808.08779)

