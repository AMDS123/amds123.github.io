---
layout: post
title: "A Latent Variable Recurrent Neural Network for Discourse Relation Language Models"
date: 2016-04-05 16:58:10
categories: arXiv_SD
tags: arXiv_SD RNN Classification Language_Model Prediction Relation
author: Yangfeng Ji, Gholamreza Haffari, Jacob Eisenstein
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a novel latent variable recurrent neural network architecture for jointly modeling sequences of words and (possibly latent) discourse relations between adjacent sentences. A recurrent neural network generates individual words, thus reaping the benefits of discriminatively-trained vector representations. The discourse relations are represented with a latent variable, which can be predicted or marginalized, depending on the task. The resulting model can therefore employ a training objective that includes not only discourse relation classification, but also word prediction. As a result, it outperforms state-of-the-art alternatives for two tasks: implicit discourse relation classification in the Penn Discourse Treebank, and dialog act classification in the Switchboard corpus. Furthermore, by marginalizing over latent discourse relations at test time, we obtain a discourse informed language model, which improves over a strong LSTM baseline.

##### Abstract (translated by Google)
本文提出了一种新的潜在变量递归神经网络结构，用于联合建模单词序列和相邻句子之间（可能是潜在的）话语关系。经常性的神经网络产生单独的单词，从而收获有区别地训练的向量表示的好处。话语关系用一个潜在的变量来表示，可以根据任务来预测或边缘化。因此，所得到的模型可以采用训练目标，不仅包括话语关系分类，还包括单词预测。因此，它胜过了两个任务的最先进的备选方案：宾州话语树库中的隐式话语关系分类，以及交换机语料库中的对话行为分类。此外，通过在测试时间边缘化潜在的话语关系，我们获得了一个话语知情的语言模型，它在一个强大的LSTM基线上得到了改进。

##### URL
[https://arxiv.org/abs/1603.01913](https://arxiv.org/abs/1603.01913)

##### PDF
[https://arxiv.org/pdf/1603.01913](https://arxiv.org/pdf/1603.01913)

