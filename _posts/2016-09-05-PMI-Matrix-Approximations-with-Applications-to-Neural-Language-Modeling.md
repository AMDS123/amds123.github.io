---
layout: post
title: "PMI Matrix Approximations with Applications to Neural Language Modeling"
date: 2016-09-05 17:47:49
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Oren Melamud, Ido Dagan, Jacob Goldberger
mathjax: true
---

* content
{:toc}

##### Abstract
The negative sampling (NEG) objective function, used in word2vec, is a simplification of the Noise Contrastive Estimation (NCE) method. NEG was found to be highly effective in learning continuous word representations. However, unlike NCE, it was considered inapplicable for the purpose of learning the parameters of a language model. In this study, we refute this assertion by providing a principled derivation for NEG-based language modeling, founded on a novel analysis of a low-dimensional approximation of the matrix of pointwise mutual information between the contexts and the predicted words. The obtained language modeling is closely related to NCE language models but is based on a simplified objective function. We thus provide a unified formulation for two main language processing tasks, namely word embedding and language modeling, based on the NEG objective function. Experimental results on two popular language modeling benchmarks show comparable perplexity results, with a small advantage to NEG over NCE.

##### Abstract (translated by Google)
在word2vec中使用的负采样（NEG）目标函数是对噪声对比估计（NCE）方法的简化。 NEG被发现是非常有效的学习连续的词语表达。然而，与NCE不同的是，为了学习语言模型的参数，它被认为是不适用的。在这项研究中，我们通过提供基于NEG的语言建模的原理推导来反驳这个断言，建立在对情境和预测词之间的点状互信息矩阵的低维近似的新颖分析的基础上。所获得的语言建模与NCE语言模型密切相关，但基于简化的目标函数。因此，我们基于NEG目标函数为两个主要的语言处理任务，即词语嵌入和语言建模提供统一的表达。两个流行的语言建模基准的实验结果显示了可比较的困惑结果，与NCE相比有一个小的优势。

##### URL
[https://arxiv.org/abs/1609.01235](https://arxiv.org/abs/1609.01235)

##### PDF
[https://arxiv.org/pdf/1609.01235](https://arxiv.org/pdf/1609.01235)

