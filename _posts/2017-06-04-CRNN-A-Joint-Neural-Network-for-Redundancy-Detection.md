---
layout: post
title: "CRNN: A Joint Neural Network for Redundancy Detection"
date: 2017-06-04 13:12:45
categories: arXiv_CL
tags: arXiv_CL Salient Text_Classification Embedding CNN RNN Classification Language_Model Detection
author: Xinyu Fu, Eugene Ch'ng, Uwe Aickelin, Simon See
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes a novel framework for detecting redundancy in supervised sentence categorisation. Unlike traditional singleton neural network, our model incorporates character-aware convolutional neural network (Char-CNN) with character-aware recurrent neural network (Char-RNN) to form a convolutional recurrent neural network (CRNN). Our model benefits from Char-CNN in that only salient features are selected and fed into the integrated Char-RNN. Char-RNN effectively learns long sequence semantics via sophisticated update mechanism. We compare our framework against the state-of-the-art text classification algorithms on four popular benchmarking corpus. For instance, our model achieves competing precision rate, recall ratio, and F1 score on the Google-news data-set. For twenty-news-groups data stream, our algorithm obtains the optimum on precision rate, recall ratio, and F1 score. For Brown Corpus, our framework obtains the best F1 score and almost equivalent precision rate and recall ratio over the top competitor. For the question classification collection, CRNN produces the optimal recall rate and F1 score and comparable precision rate. We also analyse three different RNN hidden recurrent cells' impact on performance and their runtime efficiency. We observe that MGU achieves the optimal runtime and comparable performance against GRU and LSTM. For TFIDF based algorithms, we experiment with word2vec, GloVe, and sent2vec embeddings and report their performance differences.

##### Abstract (translated by Google)
本文提出了一个新的监督句子分类冗余框架。与传统的单点神经网络不同，我们的模型将特征感知卷积神经网络（Char-CNN）与特征感知递归神经网络（Char-RNN）结合起来形成卷积递归神经网络（CRNN）。我们的模型受益于Char-CNN，因为只选择了一些显着的特征并将其输入到综合的Char-RNN中。 Char-RNN通过复杂的更新机制有效地学习长序列语义。我们将我们的框架与四种流行的基准语料库上最先进的文本分类算法进行比较。例如，我们的模型在Google新闻数据集上实现了竞争的精确率，召回率和F1分数。对于二十个新闻组的数据流，我们的算法获得最佳的精度，召回率和F1分数。对于布朗语料库，我们的框架获得了最好的F1分数和几乎相当于精确率和召回率的顶级竞争对手。对于问题分类收集，CRNN产生最佳召回率和F1分数和可比准确率。我们还分析了三种不同的RNN隐藏循环单元对性能和运行效率的影响。我们观察到MGU实现了对GRU和LSTM的最佳运行时间和可比较的性能。对于基于TFIDF的算法，我们使用word2vec，GloVe和sent2vec嵌入进行实验，并报告它们的性能差异。

##### URL
[https://arxiv.org/abs/1706.01069](https://arxiv.org/abs/1706.01069)

##### PDF
[https://arxiv.org/pdf/1706.01069](https://arxiv.org/pdf/1706.01069)

