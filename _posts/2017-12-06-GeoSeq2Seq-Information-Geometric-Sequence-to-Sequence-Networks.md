---
layout: post
title: 'GeoSeq2Seq: Information Geometric Sequence-to-Sequence Networks'
date: 2017-12-06 03:29:20
categories: arXiv_CV
tags: arXiv_CV Image_Caption Caption RNN
author: Alessandro Bay, Biswa Sengupta
---

* content
{:toc}

##### Abstract
The Fisher information metric is an important foundation of information geometry, wherein it allows us to approximate the local geometry of a probability distribution. Recurrent neural networks such as the Sequence-to-Sequence (Seq2Seq) networks that have lately been used to yield state-of-the-art performance on speech translation or image captioning have so far ignored the geometry of the latent embedding, that they iteratively learn. We propose the information geometric Seq2Seq network which abridges the gap between deep recurrent neural networks and information geometry. Specifically, the latent embedding offered by a recurrent network is encoded as a Fisher kernel of a parametric Gaussian Mixture Model, a formalism common in computer vision. We utilise such a network to predict the shortest routes between two nodes of a graph by learning the adjacency matrix using the information geometric Seq2Seq model; our results show that for such a problem the probabilistic representation of the latent embedding supersedes the non-probabilistic embedding by 10-15%.

##### Abstract (translated by Google)
Fisher信息度量是信息几何的重要基础，它允许我们近似概率分布的局部几何。近来被用于在语音翻译或图像字幕上得到最新性能的序列到序列（Seq2Seq）网络等递归神经网络迄今为止忽略了潜在嵌入的几何结构，它们迭代地学习。我们提出信息几何Seq2Seq网络，缩小了深层递归神经网络与信息几何之间的差距。具体而言，由循环网络提供的潜在嵌入被编码为参数高斯混合模型的费舍尔内核，计算机视觉中常见的形式主义。我们利用这样的网络，通过使用信息几何Seq2Seq模型来学习邻接矩阵来预测图的两个节点之间的最短路线;我们的结果表明，对于这样的问题，潜在嵌入的概率表示取代了非概率嵌入10-15％。

##### URL
[https://arxiv.org/abs/1710.09363](https://arxiv.org/abs/1710.09363)

