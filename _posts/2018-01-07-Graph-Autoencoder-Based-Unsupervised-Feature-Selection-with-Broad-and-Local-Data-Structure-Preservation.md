---
layout: post
title: "Graph Autoencoder-Based Unsupervised Feature Selection with Broad and Local Data Structure Preservation"
date: 2018-01-07 21:14:01
categories: arXiv_CV
tags: arXiv_CV Sparse Attention Embedding Relation
author: Siwei Feng, Marco F.Duarte
mathjax: true
---

* content
{:toc}

##### Abstract
Feature selection is a dimensionality reduction technique that selects a subset of representative features from high-dimensional data by eliminating irrelevant and redundant features. Recently, feature selection combined with sparse learning has attracted significant attention due to its outstanding performance compared with traditional feature selection methods that ignores correlation between features. These works first map data onto a low-dimensional subspace and then select features by posing a sparsity constraint on the transformation matrix. However, they are restricted by design to linear data transformation, a potential drawback given that the underlying correlation structures of data are often non-linear. To leverage a more sophisticated embedding, we propose an autoencoder-based unsupervised feature selection approach that leverages a single-layer autoencoder for a joint framework of feature selection and manifold learning. More specifically, we enforce column sparsity on the weight matrix connecting the input layer and the hidden layer, as in previous work. Additionally, we include spectral graph analysis on the projected data into the learning process to achieve local data geometry preservation from the original data space to the low-dimensional feature space. Extensive experiments are conducted on image, audio, text, and biological data. The promising experimental results validate the superiority of the proposed method.

##### Abstract (translated by Google)
特征选择是一种降维技术，通过消除不相关和多余的特征，从高维数据中选择代表特征的一个子集。近年来，特征选择与稀疏学习相结合，与传统的忽略特征相关性的特征选择方法相比，其性能优异，引起了人们的高度关注。这些作品首先将数据映射到低维子空间，然后通过对变换矩阵施加稀疏约束来选择特征。然而，它们受限于线性数据转换的设计，这是潜在的缺点，因为数据的基本相关结构通常是非线性的。为了利用更复杂的嵌入，我们提出了一种基于自动编码器的无监督特征选择方法，利用单层自编码器进行特征选择和流形学习的联合框架。更具体地说，我们在连接输入层和隐藏层的权重矩阵上执行列稀疏，就像以前的工作一样。另外，我们将投影数据的谱图分析纳入学习过程，实现从原始数据空间到低维特征空间的局部数据几何保存。对图像，音频，文本和生物数据进行了大量的实验。有希望的实验结果验证了所提出方法的优越性。

##### URL
[http://arxiv.org/abs/1801.02251](http://arxiv.org/abs/1801.02251)

##### PDF
[http://arxiv.org/pdf/1801.02251](http://arxiv.org/pdf/1801.02251)

