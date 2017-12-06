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
蛋白质是细胞，组织或生物体中生物功能的主要力量。鉴定和定量给定样品中的蛋白质，例如正常/疾病状态下的细胞类型是理解人类健康和疾病的基本任务。在本文中，我们介绍DeepNovo，一个深入的学习为基础的工具，以解决从串联质谱数据蛋白质鉴定问题。这个想法最初是在de novo肽测序的背景下提出的[1]，其中卷积神经网络和递归神经网络被用于从其谱中预测肽的氨基酸序列，这与从图像生成字幕相似。我们进一步开发DeepNovo进行序列数据库搜索，肽鉴定的主要技术从大量现有的蛋白质数据库中受益匪浅。我们将两个模块从头测序和数据库搜索结合到一个单一的肽识别深度学习框架中，并集成了de Bruijn图谱组装技术，为从串联质谱数据重建蛋白质序列提供了一个完整的解决方案。本文描述了DeepNovo蛋白质识别的一个全面的协议，包括训练神经网络模型，动态规划搜索，数据库查询，错误发现率的估计和de Bruijn图组装。我们的GitHub存储库（此https URL）中提供了以IPython笔记本形式的培训和测试数据，模型实现和综合教程。

##### URL
[https://arxiv.org/abs/1710.02765](https://arxiv.org/abs/1710.02765)

