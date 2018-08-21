---
layout: post
title: "Support Neighbor Loss for Person Re-Identification"
date: 2018-08-18 01:40:56
categories: arXiv_CV
tags: arXiv_CV Re-identification Attention Person_Re-identification Embedding CNN
author: Kai Li, Zhengming Ding, Kunpeng Li, Yulun Zhang, Yun Fu
mathjax: true
---

* content
{:toc}

##### Abstract
Person re-identification (re-ID) has recently been tremendously boosted due to the advancement of deep convolutional neural networks (CNN). The majority of deep re-ID methods focus on designing new CNN architectures, while less attention is paid on investigating the loss functions. Verification loss and identification loss are two types of losses widely used to train various deep re-ID models, both of which however have limitations. Verification loss guides the networks to generate feature embeddings of which the intra-class variance is decreased while the inter-class ones is enlarged. However, training networks with verification loss tends to be of slow convergence and unstable performance when the number of training samples is large. On the other hand, identification loss has good separating and scalable property. But its neglect to explicitly reduce the intra-class variance limits its performance on re-ID, because the same person may have significant appearance disparity across different camera views. To avoid the limitations of the two types of losses, we propose a new loss, called support neighbor (SN) loss. Rather than being derived from data sample pairs or triplets, SN loss is calculated based on the positive and negative support neighbor sets of each anchor sample, which contain more valuable contextual information and neighborhood structure that are beneficial for more stable performance. To ensure scalability and separability, a softmax-like function is formulated to push apart the positive and negative support sets. To reduce intra-class variance, the distance between the anchor's nearest positive neighbor and furthest positive sample is penalized. Integrating SN loss on top of Resnet50, superior re-ID results to the state-of-the-art ones are obtained on several widely used datasets.

##### Abstract (translated by Google)
由于深度卷积神经网络（CNN）的进步，最近人们重新识别（re-ID）得到了极大的提升。大多数深度重新ID方法侧重于设计新的CNN架构，而较少关注于调查损耗函数。验证损失和识别丢失是广泛用于训练各种深度重新ID模型的两种类型的损失，但这两种模型都有局限性。验证损失指导网络生成特征嵌入，其中类内方差减小而类间方差扩大。然而，当训练样本的数量很大时，具有验证损失的训练网络趋于缓慢收敛和不稳定的性能。另一方面，识别丢失具有良好的分离性和可扩展性。但是忽略明确减少类内方差限制了其在重新ID上的表现，因为同一个人可能在不同的相机视图中具有显着的外观差异。为了避免这两种类型的损失的限制，我们提出了一种新的损失，称为支持邻居（SN）损失。不是从数据样本对或三元组导出，而是基于每个锚样本的正和负支持邻居集计算SN损失，其包含更有价值的上下文信息和邻域结构，这有利于更稳定的性能。为了确保可扩展性和可分离性，我们制定了类似softmax的功能，以推动正负支撑集。为了减少类内方差，锚的最近的正邻居和最远的正样本之间的距离受到惩罚。将SN损失整合到Resnet50之上，可以在几个广泛使用的数据集上获得优于现有技术的重新ID结果。

##### URL
[http://arxiv.org/abs/1808.06030](http://arxiv.org/abs/1808.06030)

##### PDF
[http://arxiv.org/pdf/1808.06030](http://arxiv.org/pdf/1808.06030)

