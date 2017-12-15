---
layout: post
title: "Discriminative Acoustic Word Embeddings: Recurrent Neural Network-Based Approaches"
date: 2016-11-08 15:13:19
categories: arXiv_CL
tags: arXiv_CL Speech_Recognition Embedding RNN Classification Recognition
author: Shane Settle, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Acoustic word embeddings --- fixed-dimensional vector representations of variable-length spoken word segments --- have begun to be considered for tasks such as speech recognition and query-by-example search. Such embeddings can be learned discriminatively so that they are similar for speech segments corresponding to the same word, while being dissimilar for segments corresponding to different words. Recent work has found that acoustic word embeddings can outperform dynamic time warping on query-by-example search and related word discrimination tasks. However, the space of embedding models and training approaches is still relatively unexplored. In this paper we present new discriminative embedding models based on recurrent neural networks (RNNs). We consider training losses that have been successful in prior work, in particular a cross entropy loss for word classification and a contrastive loss that explicitly aims to separate same-word and different-word pairs in a "Siamese network" training setting. We find that both classifier-based and Siamese RNN embeddings improve over previously reported results on a word discrimination task, with Siamese RNNs outperforming classification models. In addition, we present analyses of the learned embeddings and the effects of variables such as dimensionality and network structure.

##### Abstract (translated by Google)
声字嵌入---变长语音段的固定维矢量表示---已经开始被用于诸如语音识别和按例查询查询之类的任务。这样的嵌入可以被区分地学习，使得它们对于对应于相同单词的语音片段是相似的，而对于对应于不同单词的片段是不相似的。最近的研究发现，声学词汇嵌入可以胜过动态时间翘曲查询的例子搜索和相关的词区分任务。然而，嵌入模型和训练方法的空间仍然相对较少。在本文中，我们提出了基于递归神经网络（RNN）的新的判别嵌入模型。我们考虑培训在以前的工作中已经成功的损失，特别是对于单词分类的交叉熵损失和明确旨在在“连体网络”训练设置中分隔相同单词和不同单词对的对比损失。我们发现基于分类器和Siamese RNN嵌入相比先前报道的单词识别任务的结果有所改善，其中Siamese RNN优于分类模型。另外，我们还分析了学习嵌入和维度和网络结构等变量的影响。

##### URL
[https://arxiv.org/abs/1611.02550](https://arxiv.org/abs/1611.02550)

##### PDF
[https://arxiv.org/pdf/1611.02550](https://arxiv.org/pdf/1611.02550)

