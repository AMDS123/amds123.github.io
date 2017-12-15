---
layout: post
title: "A Generative Word Embedding Model and its Low Rank Positive Semidefinite Solution"
date: 2015-08-16 14:12:17
categories: arXiv_CL
tags: arXiv_CL Sentiment Embedding Optimization Inference Language_Model
author: Shaohua Li, Jun Zhu, Chunyan Miao
mathjax: true
---

* content
{:toc}

##### Abstract
Most existing word embedding methods can be categorized into Neural Embedding Models and Matrix Factorization (MF)-based methods. However some models are opaque to probabilistic interpretation, and MF-based methods, typically solved using Singular Value Decomposition (SVD), may incur loss of corpus information. In addition, it is desirable to incorporate global latent factors, such as topics, sentiments or writing styles, into the word embedding model. Since generative models provide a principled way to incorporate latent factors, we propose a generative word embedding model, which is easy to interpret, and can serve as a basis of more sophisticated latent factor models. The model inference reduces to a low rank weighted positive semidefinite approximation problem. Its optimization is approached by eigendecomposition on a submatrix, followed by online blockwise regression, which is scalable and avoids the information loss in SVD. In experiments on 7 common benchmark datasets, our vectors are competitive to word2vec, and better than other MF-based methods.

##### Abstract (translated by Google)
大多数现有的词嵌入方法可以被分类为神经嵌入模型和基于矩阵分解（MF）的方法。然而，一些模型对于概率解释是不透明的，基于MF的方法通常使用奇异值分解（Singular Value Decomposition，SVD）来解决，可能会导致语料库信息的丢失。此外，还希望将诸如主题，情感或写作风格等全球潜在因素整合到单词嵌入模型中。由于生成模型提供了融合潜在因素的原则性方法，我们提出了一个生成性词语嵌入模型，这个模型易于解释，可以作为更复杂的潜在因素模型的基础。模型推论降为低秩加权正半定近似问题。其优化是通过在子矩阵上进行特征分解来实现的，其次是在线逐块回归，这是可扩展的，并且避免了SVD中的信息损失。在7个常用基准数据集的实验中，我们的载体比word2vec更具竞争力，并且比其他基于MF的方法更好。

##### URL
[https://arxiv.org/abs/1508.03826](https://arxiv.org/abs/1508.03826)

##### PDF
[https://arxiv.org/pdf/1508.03826](https://arxiv.org/pdf/1508.03826)

