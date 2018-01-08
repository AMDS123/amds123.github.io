---
layout: post
title: "Towards Understanding and Answering Multi-Sentence Recommendation Questions on Tourism"
date: 2018-01-05 16:38:05
categories: arXiv_CL
tags: arXiv_CL Knowledge QA RNN Recommendation
author: Danish Contractor, Barun Patra, Mausam Singla, Parag Singla
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the first system towards the novel task of answering complex multisentence recommendation questions in the tourism domain. Our solution uses a pipeline of two modules: question understanding and answering. For question understanding, we define an SQL-like query language that captures the semantic intent of a question; it supports operators like subset, negation, preference and similarity, which are often found in recommendation questions. We train and compare traditional CRFs as well as bidirectional LSTM-based models for converting a question to its semantic representation. We extend these models to a semisupervised setting with partially labeled sequences gathered through crowdsourcing. We find that our best model performs semi-supervised training of BiDiLSTM+CRF with hand-designed features and CCM(Chang et al., 2007) constraints. Finally, in an end to end QA system, our answering component converts our question representation into queries fired on underlying knowledge sources. Our experiments on two different answer corpora demonstrate that our system can significantly outperform baselines with up to 20 pt higher accuracy and 17 pt higher recall.

##### Abstract (translated by Google)
我们将第一个系统引入在旅游领域中回答复杂的多能力推荐问题的新任务。我们的解决方案使用两个模块的管道：问题的理解和回答。为了理解问题，我们定义了一个类似于SQL的查询语言，它捕捉问题的语义意图;它支持经常出现在推荐问题中的子集，否定，偏好和相似性等操作符。我们训练和比较传统CRF以及基于双向LSTM的模型，将问题转化为语义表示。我们将这些模型扩展到半监督环境，通过众包来收集部分标记的序列。我们发现，我们最好的模型执行BiDiLSTM + CRF的半监督训练，具有手工设计特征和CCM（Chang et al。，2007）约束。最后，在一个端对端的质量保证体系中，我们的应答组件将我们的问题表示转换为对基础知识源进行查询。我们对两个不同的答案语料库进行的实验表明，我们的系统可以显着超过基线，精确度高达20点，召回率高17点。

##### URL
[http://arxiv.org/abs/1801.01825](http://arxiv.org/abs/1801.01825)

##### PDF
[http://arxiv.org/pdf/1801.01825](http://arxiv.org/pdf/1801.01825)

