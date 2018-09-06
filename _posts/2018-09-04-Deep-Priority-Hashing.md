---
layout: post
title: "Deep Priority Hashing"
date: 2018-09-04 20:48:18
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval
author: Zhangjie Cao, Ziping Sun, Mingsheng Long, Jianmin Wang, Philip S. Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Deep hashing enables image retrieval by end-to-end learning of deep representations and hash codes from training data with pairwise similarity information. Subject to the distribution skewness underlying the similarity information, most existing deep hashing methods may underperform for imbalanced data due to misspecified loss functions. This paper presents Deep Priority Hashing (DPH), an end-to-end architecture that generates compact and balanced hash codes in a Bayesian learning framework. The main idea is to reshape the standard cross-entropy loss for similarity-preserving learning such that it down-weighs the loss associated to highly-confident pairs. This idea leads to a novel priority cross-entropy loss, which prioritizes the training on uncertain pairs over confident pairs. Also, we propose another priority quantization loss, which prioritizes hard-to-quantize examples for generation of nearly lossless hash codes. Extensive experiments demonstrate that DPH can generate high-quality hash codes and yield state-of-the-art image retrieval results on three datasets, ImageNet, NUS-WIDE, and MS-COCO.

##### Abstract (translated by Google)
深度哈希通过端对端学习深度表示和来自具有成对相似性信息的训练数据的哈希码来实现图像检索。受到相似性信息背后的分布偏差的影响，由于错误指定的损失函数，大多数现有的深度散列方法可能对不平衡数据的表现不佳。本文介绍了深度优先级哈希（DPH），这是一种端到端架构，可在贝叶斯学习框架中生成紧凑且平衡的哈希码。主要思想是重新设计保持相似性学习的标准交叉熵损失，以便降低与高度自信对相关的损失。这种想法导致了一种新颖的优先级交叉熵损失，它优先考虑在确定对上的不确定对上的训练。此外，我们提出另一个优先级量化损失，其优先考虑难以量化的示例以生成几乎无损的哈希码。大量实验表明，DPH可以生成高质量的哈希码，并在三个数据集ImageNet，NUS-WIDE和MS-COCO上产生最先进的图像检索结果。

##### URL
[http://arxiv.org/abs/1809.01238](http://arxiv.org/abs/1809.01238)

##### PDF
[http://arxiv.org/pdf/1809.01238](http://arxiv.org/pdf/1809.01238)

