---
layout: post
title: "Protein identification with deep learning: from abc to xyz"
date: 2017-10-08 01:23:18
categories: arXiv_CV
tags: arXiv_CV GAN Caption CNN RNN Deep_Learning
author: Ngoc Hieu Tran, Zachariah Levine, Lei Xin, Baozhen Shan, Ming Li
mathjax: true
---

* content
{:toc}

##### Abstract
Proteins are the main workhorses of biological functions in a cell, a tissue, or an organism. Identification and quantification of proteins in a given sample, e.g. a cell type under normal/disease conditions, are fundamental tasks for the understanding of human health and disease. In this paper, we present DeepNovo, a deep learning-based tool to address the problem of protein identification from tandem mass spectrometry data. The idea was first proposed in the context of de novo peptide sequencing [1] in which convolutional neural networks and recurrent neural networks were applied to predict the amino acid sequence of a peptide from its spectrum, a similar task to generating a caption from an image. We further develop DeepNovo to perform sequence database search, the main technique for peptide identification that greatly benefits from numerous existing protein databases. We combine two modules de novo sequencing and database search into a single deep learning framework for peptide identification, and integrate de Bruijn graph assembly technique to offer a complete solution to reconstruct protein sequences from tandem mass spectrometry data. This paper describes a comprehensive protocol of DeepNovo for protein identification, including training neural network models, dynamic programming search, database querying, estimation of false discovery rate, and de Bruijn graph assembly. Training and testing data, model implementations, and comprehensive tutorials in form of IPython notebooks are available in our GitHub repository (this https URL).

##### Abstract (translated by Google)
蛋白质是细胞，组织或生物体中生物功能的主要工具。鉴定和定量给定样品中的蛋白质，例如正常/疾病状态下的细胞类型是理解人类健康和疾病的基本任务。在本文中，我们介绍DeepNovo，一种基于深度学习的工具，用于解决串联质谱数据中蛋白质鉴定的问题。这个想法最初是在从头肽测序[1]的背景下提出的，其中应用卷积神经网络和递归神经网络从其光谱预测肽的氨基酸序列，类似的任务是从图像生成标题。我们进一步开发DeepNovo以进行序列数据库检索，这是肽鉴定的主要技术，它从众多现有的蛋白质数据库中获益匪浅。我们将两个模块从头测序和数据库搜索结合到一个用于肽鉴定的深度学习框架中，并整合de Bruijn图形组装技术，以提供从串联质谱数据重建蛋白质序列的完整解决方案。本文描述了DeepNovo用于蛋白质鉴定的综合协议，包括训练神经网络模型，动态规划搜索，数据库查询，错误发现率估计和de Bruijn图组装。我们的GitHub存储库（此https URL）中提供了IPython笔记本形式的培训和测试数据，模型实现以及综合教程。

##### URL
[https://arxiv.org/abs/1710.02765](https://arxiv.org/abs/1710.02765)

##### PDF
[https://arxiv.org/pdf/1710.02765](https://arxiv.org/pdf/1710.02765)

