---
layout: post
title: "Deep Group-shuffling Random Walk for Person Re-identification"
date: 2018-07-30 05:35:38
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification
author: Yantao Shen, Hongsheng Li, Tong Xiao, Shuai Yi, Dapeng Chen, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification aims at finding a person of interest in an image gallery by comparing the probe image of this person with all the gallery images. It is generally treated as a retrieval problem, where the affinities between the probe image and gallery images (P2G affinities) are used to rank the retrieved gallery images. However, most existing methods only consider P2G affinities but ignore the affinities between all the gallery images (G2G affinity). Some frameworks incorporated G2G affinities into the testing process, which is not end-to-end trainable for deep neural networks. In this paper, we propose a novel group-shuffling random walk network for fully utilizing the affinity information between gallery images in both the training and testing processes. The proposed approach aims at end-to-end refining the P2G affinities based on G2G affinity information with a simple yet effective matrix operation, which can be integrated into deep neural networks. Feature grouping and group shuffle are also proposed to apply rich supervisions for learning better person features. The proposed approach outperforms state-of-the-art methods on the Market-1501, CUHK03, and DukeMTMC datasets by large margins, which demonstrate the effectiveness of our approach.

##### Abstract (translated by Google)
人物重新识别旨在通过将该人物的探测图像与所有画廊图像进行比较来在图像库中找到感兴趣的人。它通常被视为检索问题，其中探测图像和图库图像之间的亲和力（P2G亲和力）用于对检索的图库图像进行排名。然而，大多数现有方法仅考虑P2G亲和力但忽略所有图库图像之间的亲和力（G2G亲和力）。一些框架将G2G亲和力纳入测试过程，这对于深度神经网络而言不是端到端可训练的。在本文中，我们提出了一种新的组改组随机游走网络，用于在训练和测试过程中充分利用画廊图像之间的亲和力信息。所提出的方法旨在通过简单而有效的矩阵运算来基于G2G亲和度信息端到端地改进P2G亲和力，其可以集成到深度神经网络中。还建议使用特征分组和群组改组来应用丰富的监督来学习更好的人物特征。所提出的方法在Market-1501，CUHK03和DukeMTMC数据集上的表现优于大型利润，这证明了我们的方法的有效性。

##### URL
[http://arxiv.org/abs/1807.11178](http://arxiv.org/abs/1807.11178)

##### PDF
[http://arxiv.org/pdf/1807.11178](http://arxiv.org/pdf/1807.11178)

