---
layout: post
title: "Encoding Sentences with Graph Convolutional Networks for Semantic Role Labeling"
date: 2017-07-30 17:24:38
categories: arXiv_SD
tags: arXiv_SD CNN RNN
author: Diego Marcheggiani, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic role labeling (SRL) is the task of identifying the predicate-argument structure of a sentence. It is typically regarded as an important step in the standard NLP pipeline. As the semantic representations are closely related to syntactic ones, we exploit syntactic information in our model. We propose a version of graph convolutional networks (GCNs), a recent class of neural networks operating on graphs, suited to model syntactic dependency graphs. GCNs over syntactic dependency trees are used as sentence encoders, producing latent feature representations of words in a sentence. We observe that GCN layers are complementary to LSTM ones: when we stack both GCN and LSTM layers, we obtain a substantial improvement over an already state-of-the-art LSTM SRL model, resulting in the best reported scores on the standard benchmark (CoNLL-2009) both for Chinese and English.

##### Abstract (translated by Google)
语义角色标注（SRL）是识别句子的谓词 - 论证结构的任务。它通常被认为是标准NLP管道中的一个重要步骤。由于语义表征与句法关系紧密相关，我们利用模型中的句法信息。我们提出了一个图形卷积网络（GCNs）的版本，最近一类在图上运行的神经网络，适用于语法依赖图模型。句法依赖树上的GCN用作句子编码器，产生句子中单词的潜在特征表示。我们观察到GCN层与LSTM层是互补的：当我们叠加GCN层和LSTM层时，我们获得了比已经最先进的LSTM SRL模型的实质性改进，导致在标准基准CoNLL-2009）中文和英文。

##### URL
[https://arxiv.org/abs/1703.04826](https://arxiv.org/abs/1703.04826)

##### PDF
[https://arxiv.org/pdf/1703.04826](https://arxiv.org/pdf/1703.04826)

