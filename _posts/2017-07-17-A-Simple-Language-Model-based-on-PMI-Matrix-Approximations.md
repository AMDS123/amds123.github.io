---
layout: post
title: "A Simple Language Model based on PMI Matrix Approximations"
date: 2017-07-17 16:21:46
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Oren Melamud, Ido Dagan, Jacob Goldberger
mathjax: true
---

* content
{:toc}

##### Abstract
In this study, we introduce a new approach for learning language models by training them to estimate word-context pointwise mutual information (PMI), and then deriving the desired conditional probabilities from PMI at test time. Specifically, we show that with minor modifications to word2vec's algorithm, we get principled language models that are closely related to the well-established Noise Contrastive Estimation (NCE) based language models. A compelling aspect of our approach is that our models are trained with the same simple negative sampling objective function that is commonly used in word2vec to learn word embeddings.

##### Abstract (translated by Google)
在这项研究中，我们引入了一种新的学习语言模型的方法，通过训练他们来估计词语上下文逐点互信息（PMI），然后在测试时从PMI中导出所需的条件概率。具体来说，我们展示了对word2vec算法进行细微的修改，我们得到了与已经建立的基于噪声对比估计（NCE）的语言模型密切相关的原则性语言模型。我们的方法的一个引人注目的方面是，我们的模型是用word2vec中常用的相同的简单负抽样目标函数来学习单词嵌入。

##### URL
[https://arxiv.org/abs/1707.05266](https://arxiv.org/abs/1707.05266)

##### PDF
[https://arxiv.org/pdf/1707.05266](https://arxiv.org/pdf/1707.05266)

