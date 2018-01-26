---
layout: post
title: "A Question-Focused Multi-Factor Attention Network for Question Answering"
date: 2018-01-25 07:08:04
categories: arXiv_CL
tags: arXiv_CL QA Attention Prediction Relation
author: Souvik Kundu, Hwee Tou Ng
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network models recently proposed for question answering (QA) primarily focus on capturing the passage-question relation. However, they have minimal capability to link relevant facts distributed across multiple sentences which is crucial in achieving deeper understanding, such as performing multi-sentence reasoning, co-reference resolution, etc. They also do not explicitly focus on the question and answer type which often plays a critical role in QA. In this paper, we propose a novel end-to-end question-focused multi-factor attention network for answer extraction. Multi-factor attentive encoding using tensor-based transformation aggregates meaningful facts even when they are located in multiple sentences. To implicitly infer the answer type, we also propose a max-attentional question aggregation mechanism to encode a question vector based on the important words in a question. During prediction, we incorporate sequence-level encoding of the first wh-word and its immediately following word as an additional source of question type information. Our proposed model achieves significant improvements over the best prior state-of-the-art results on three large-scale challenging QA datasets, namely NewsQA, TriviaQA, and SearchQA.

##### Abstract (translated by Google)
最近提出的问答（QA）的神经网络模型主要集中在捕捉通过问题的关系上。然而，将多个句子分布的相关事实联系起来的能力很小，这对于实现更深入的理解至关重要，比如进行多句子推理，共同参考解决等。他们也没有明确地关注问答类型在QA中经常起着关键的作用。在本文中，我们提出了一个新颖的端到端的以问题为中心的多因素关注网络来提取答案。即使在位于多个句子中的情况下，使用基于张量的变换的多因子细致编码也会聚集有意义的事实。为了隐含地推断答案类型，我们还提出了一个最大关注问题的聚合机制，以问题中的重要单词为基础对问题向量进行编码。在预测过程中，我们将第一个wh-词的序列级编码及其紧随其后的词作为问题类型信息的附加源。我们提出的模型比三个大规模具有挑战性的QA数据集（即NewsQA，TriviaQA和SearchQA）获得的最好的现有技术水平显着提高。

##### URL
[http://arxiv.org/abs/1801.08290](http://arxiv.org/abs/1801.08290)

##### PDF
[http://arxiv.org/pdf/1801.08290](http://arxiv.org/pdf/1801.08290)

