---
layout: post
title: "Riemannian Optimization for Skip-Gram Negative Sampling"
date: 2017-04-26 11:17:51
categories: arXiv_CL
tags: arXiv_CL Embedding Optimization Language_Model Gradient_Descent
author: Alexander Fonarev, Oleksii Hrinchuk, Gleb Gusev, Pavel Serdyukov, Ivan Oseledets
mathjax: true
---

* content
{:toc}

##### Abstract
Skip-Gram Negative Sampling (SGNS) word embedding model, well known by its implementation in "word2vec" software, is usually optimized by stochastic gradient descent. However, the optimization of SGNS objective can be viewed as a problem of searching for a good matrix with the low-rank constraint. The most standard way to solve this type of problems is to apply Riemannian optimization framework to optimize the SGNS objective over the manifold of required low-rank matrices. In this paper, we propose an algorithm that optimizes SGNS objective using Riemannian optimization and demonstrates its superiority over popular competitors, such as the original method to train SGNS and SVD over SPPMI matrix.

##### Abstract (translated by Google)
通过在“word2vec”软件中实现的“Skip-Gram Negative Sampling（SGNS）”字嵌入模型通常通过随机梯度下降来优化。然而，SGNS目标的优化可以看作是寻找具有低秩约束的良好矩阵的问题。解决这类问题的最为标准的方法是应用黎曼优化框架来优化所需的低秩矩阵的流形上的SGNS目标。在本文中，我们提出了一种使用黎曼优化来优化SGNS目标的算法，并且证明了其优于普通竞争者的优越性，例如在SPPMI矩阵上训练SGNS和SVD的原始方法。

##### URL
[https://arxiv.org/abs/1704.08059](https://arxiv.org/abs/1704.08059)

##### PDF
[https://arxiv.org/pdf/1704.08059](https://arxiv.org/pdf/1704.08059)

