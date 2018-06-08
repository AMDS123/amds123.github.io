---
layout: post
title: "Spectral Network Embedding: A Fast and Scalable Method via Sparsity"
date: 2018-06-07 11:38:34
categories: arXiv_AI
tags: arXiv_AI Sparse Attention GAN Embedding Classification Language_Model Prediction
author: Jie Zhang, Yan Wang, Jie Tang
mathjax: true
---

* content
{:toc}

##### Abstract
Network embedding aims to learn low-dimensional representations of nodes in a network, while the network structure and inherent properties are preserved. It has attracted tremendous attention recently due to significant progress in downstream network learning tasks, such as node classification, link prediction, and visualization. However, most existing network embedding methods suffer from the expensive computations due to the large volume of networks. In this paper, we propose a $10\times \sim 100\times$ faster network embedding method, called Progle, by elegantly utilizing the sparsity property of online networks and spectral analysis. In Progle, we first construct a \textit{sparse} proximity matrix and train the network embedding efficiently via sparse matrix decomposition. Then we introduce a network propagation pattern via spectral analysis to incorporate local and global structure information into the embedding. Besides, this model can be generalized to integrate network information into other insufficiently trained embeddings at speed. Benefiting from sparse spectral network embedding, our experiment on four different datasets shows that Progle outperforms or is comparable to state-of-the-art unsupervised comparison approaches---DeepWalk, LINE, node2vec, GraRep, and HOPE, regarding accuracy, while is $10\times$ faster than the fastest word2vec-based method. Finally, we validate the scalability of Progle both in real large-scale networks and multiple scales of synthetic networks.

##### Abstract (translated by Google)
网络嵌入旨在学习网络中节点的低维表示，同时保留网络结构和固有属性。由于下游网络学习任务（如节点分类，链接预测和可视化）的显着进步，近来引起了极大的关注。然而，由于大量的网络，大多数现有网络嵌入方法遭受昂贵的计算。在本文中，我们通过优雅地利用在线网络和频谱分析的稀疏属性，提出了一种价格为10美元/次\ sim100 \ times快速网络嵌入方法，称为Progle。在Progle中，我们首先构造一个\ textit {sparse}接近矩阵，并通过稀疏矩阵分解有效地训练网络嵌入。然后我们通过频谱分析引入网络传播模式，将局部和全局结构信息合并到嵌入中。此外，该模型可以推广到将网络信息快速整合到其他训练不足的嵌入中。受益于稀疏的频谱网络嵌入，我们对四个不同数据集的实验显示，Progle在准确性方面优于或可与最先进的无监督比较方法（DeepWalk，LINE，node2vec，GraRep和HOPE）比基于word2vec的最快方法快10倍。最后，我们验证了Progle在实际大规模网络和多种规模的合成网络中的可扩展性。

##### URL
[http://arxiv.org/abs/1806.02623](http://arxiv.org/abs/1806.02623)

##### PDF
[http://arxiv.org/pdf/1806.02623](http://arxiv.org/pdf/1806.02623)

