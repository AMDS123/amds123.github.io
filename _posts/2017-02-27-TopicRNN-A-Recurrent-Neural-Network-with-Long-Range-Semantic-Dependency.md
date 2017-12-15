---
layout: post
title: "TopicRNN: A Recurrent Neural Network with Long-Range Semantic Dependency"
date: 2017-02-27 03:03:38
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Face RNN Language_Model Prediction
author: Adji B. Dieng, Chong Wang, Jianfeng Gao, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose TopicRNN, a recurrent neural network (RNN)-based language model designed to directly capture the global semantic meaning relating words in a document via latent topics. Because of their sequential nature, RNNs are good at capturing the local structure of a word sequence - both semantic and syntactic - but might face difficulty remembering long-range dependencies. Intuitively, these long-range dependencies are of semantic nature. In contrast, latent topic models are able to capture the global underlying semantic structure of a document but do not account for word ordering. The proposed TopicRNN model integrates the merits of RNNs and latent topic models: it captures local (syntactic) dependencies using an RNN and global (semantic) dependencies using latent topics. Unlike previous work on contextual RNN language modeling, our model is learned end-to-end. Empirical results on word prediction show that TopicRNN outperforms existing contextual RNN baselines. In addition, TopicRNN can be used as an unsupervised feature extractor for documents. We do this for sentiment analysis on the IMDB movie review dataset and report an error rate of $6.28\%$. This is comparable to the state-of-the-art $5.91\%$ resulting from a semi-supervised approach. Finally, TopicRNN also yields sensible topics, making it a useful alternative to document models such as latent Dirichlet allocation.

##### Abstract (translated by Google)
本文提出了一种基于递归神经网络（RNN）的TopicRNN语言模型，通过潜在的主题直接捕获文档中的全局语义相关词。由于它们的连续性，RNN擅长捕捉单词序列的局部结构 - 包括语义和句法 - 但是在记忆远程依赖时可能会遇到困难。直觉上来说，这些远程依赖是具有语义性质的。相比之下，潜在主题模型能够捕捉文档的全局潜在语义结构，但不考虑词语排序。所提出的TopicRNN模型整合了RNN和潜在话题模型的优点：它使用RNN和全局（语义）依赖关系使用潜在主题捕获本地（语法）依赖关系。与之前关于上下文RNN语言建模的工作不同，我们的模型是端到端学习的。单词预测的实证结果表明，TopicRNN优于现有的上下文RNN基线。另外，TopicRNN可以用作文档的无监督特征提取器。我们在IMDB电影评论数据集上进行情感分析，并报告$ 6.28 \％$的错误率。这与半监督方法所得到的最新的$ 5.91 \％$相当。最后，TopicRNN也产生了明智的主题，使其成为文档模型（如潜在的Dirichlet分配）的有用替代方案。

##### URL
[https://arxiv.org/abs/1611.01702](https://arxiv.org/abs/1611.01702)

##### PDF
[https://arxiv.org/pdf/1611.01702](https://arxiv.org/pdf/1611.01702)

