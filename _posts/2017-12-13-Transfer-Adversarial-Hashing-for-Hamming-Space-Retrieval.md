---
layout: post
title: "Transfer Adversarial Hashing for Hamming Space Retrieval"
date: 2017-12-13 06:06:13
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Adversarial
author: Zhangjie Cao, Mingsheng Long, Chao Huang, Jianmin Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Hashing is widely applied to large-scale image retrieval due to the storage and retrieval efficiency. Existing work on deep hashing assumes that the database in the target domain is identically distributed with the training set in the source domain. This paper relaxes this assumption to a transfer retrieval setting, which allows the database and the training set to come from different but relevant domains. However, the transfer retrieval setting will introduce two technical difficulties: first, the hash model trained on the source domain cannot work well on the target domain due to the large distribution gap; second, the domain gap makes it difficult to concentrate the database points to be within a small Hamming ball. As a consequence, transfer retrieval performance within Hamming Radius 2 degrades significantly in existing hashing methods. This paper presents Transfer Adversarial Hashing (TAH), a new hybrid deep architecture that incorporates a pairwise $t$-distribution cross-entropy loss to learn concentrated hash codes and an adversarial network to align the data distributions between the source and target domains. TAH can generate compact transfer hash codes for efficient image retrieval on both source and target domains. Comprehensive experiments validate that TAH yields state of the art Hamming space retrieval performance on standard datasets.

##### Abstract (translated by Google)
由于存储和检索效率的原因，散列技术被广泛应用于大规模的图像检索。现有的深度散列工作假定目标域中的数据库与源域中的训练集相同。本文将这个假设放宽到转移检索设置，这允许数据库和训练集来自不同但相关的领域。然而，传输检索设置会带来两个技术难点：一是由于分布间隙较大，在源域上训练的散列模型在目标域上不能很好地工作，其次，领域差距使得把数据库点集中在一个小的汉明球内变得困难。因此，Hamming Radius 2中的传输检索性能在现有的散列方法中显着降低。本文提出了转移对抗散列技术（TAH），这是一种新的混合深度架构，它包含了一对$ t $分配交叉熵损失来学习集中哈希代码和一个敌对网络来调整源和目标域之间的数据分布。 TAH可以生成紧凑的传输哈希码，以便在源域和目标域上进行高效的图像检索。综合实验验证了TAH在标准数据集上获得了最先进的海明空间检索性能。

##### URL
[http://arxiv.org/abs/1712.04616](http://arxiv.org/abs/1712.04616)

##### PDF
[http://arxiv.org/pdf/1712.04616](http://arxiv.org/pdf/1712.04616)

