---
layout: post
title: "Classifying Relations via Long Short Term Memory Networks along Shortest Dependency Path"
date: 2015-08-15 11:15:32
categories: arXiv_CV
tags: arXiv_CV RNN Classification Relation Memory_Networks
author: Xu Yan, Lili Mou, Ge Li, Yunchuan Chen, Hao Peng, Zhi Jin
mathjax: true
---

* content
{:toc}

##### Abstract
Relation classification is an important research arena in the field of natural language processing (NLP). In this paper, we present SDP-LSTM, a novel neural network to classify the relation of two entities in a sentence. Our neural architecture leverages the shortest dependency path (SDP) between two entities; multichannel recurrent neural networks, with long short term memory (LSTM) units, pick up heterogeneous information along the SDP. Our proposed model has several distinct features: (1) The shortest dependency paths retain most relevant information (to relation classification), while eliminating irrelevant words in the sentence. (2) The multichannel LSTM networks allow effective information integration from heterogeneous sources over the dependency paths. (3) A customized dropout strategy regularizes the neural network to alleviate overfitting. We test our model on the SemEval 2010 relation classification task, and achieve an $F_1$-score of 83.7\%, higher than competing methods in the literature.

##### Abstract (translated by Google)
关系分类是自然语言处理（NLP）领域的一个重要研究领域。在本文中，我们提出了一个新的神经网络SDP-LSTM来对一个句子中两个实体的关系进行分类。我们的神经架构利用两个实体之间的最短依赖路径（SDP）具有长期短期记忆（LSTM）单元的多通道递归神经网络，沿着SDP拾取异构信息。我们提出的模型有几个明显的特点：（1）最短的依赖路径保留了最相关的信息（对关系分类），同时消除了句子中不相关的单词。 （2）多信道LSTM网络允许从异质源到依赖路径的有效信息集成。 （3）定制的退出策略规范神经网络，以减轻过度拟合。我们在SemEval 2010关系分类任务上测试了我们的模型，并且获得了83.7％的$ F_1 $  - 分值，高于文献中的竞争方法。

##### URL
[https://arxiv.org/abs/1508.03720](https://arxiv.org/abs/1508.03720)

##### PDF
[https://arxiv.org/pdf/1508.03720](https://arxiv.org/pdf/1508.03720)

