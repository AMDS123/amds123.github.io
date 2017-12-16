---
layout: post
title: "Vectorial Dimension Reduction for Tensors Based on Bayesian Inference"
date: 2017-07-03 02:35:21
categories: arXiv_CV
tags: arXiv_CV Inference Classification
author: Fujiao Ju, Yanfeng Sun, Junbin Gao, Yongli Hu, Baocai Yin
mathjax: true
---

* content
{:toc}

##### Abstract
Dimensionality reduction for high-order tensors is a challenging problem. In conventional approaches, higher order tensors are `vectorized` via Tucker decomposition to obtain lower order tensors. This will destroy the inherent high-order structures or resulting in undesired tensors, respectively. This paper introduces a probabilistic vectorial dimensionality reduction model for tensorial data. The model represents a tensor by employing a linear combination of same order basis tensors, thus it offers a mechanism to directly reduce a tensor to a vector. Under this expression, the projection base of the model is based on the tensor CandeComp/PARAFAC (CP) decomposition and the number of free parameters in the model only grows linearly with the number of modes rather than exponentially. A Bayesian inference has been established via the variational EM approach. A criterion to set the parameters (factor number of CP decomposition and the number of extracted features) is empirically given. The model outperforms several existing PCA-based methods and CP decomposition on several publicly available databases in terms of classification and clustering accuracy.

##### Abstract (translated by Google)
高阶张量的维数降低是一个具有挑战性的问题。在传统的方法中，高阶张量通过塔克分解被“矢量化”以获得低阶张量。这将分别破坏固有的高阶结构或导致不希望的张量。本文介绍了一种概率向量降维的张量数据模型。该模型通过采用相同阶基础张量的线性组合来表示张量，因此它提供了直接将张量减小到矢量的机制。在这个表达式下，模型的投影基础是基于张量CandeComp / PARAFAC（CP）的分解，模型中自由参数的数量只随模式数目线性增长，而不是按指数规律增长。贝叶斯推断已经通过变分EM方法建立。根据经验给出设置参数（CP分解的因子数和提取的特征的数量）的标准。该模型在分类和聚类准确性方面胜过了几个现有的基于PCA的方法和在几个公开可用的数据库上的CP分解。

##### URL
[https://arxiv.org/abs/1707.00380](https://arxiv.org/abs/1707.00380)

##### PDF
[https://arxiv.org/pdf/1707.00380](https://arxiv.org/pdf/1707.00380)

