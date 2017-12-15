---
layout: post
title: "Automatic Generation of Natural Language Explanations"
date: 2017-07-04 14:52:41
categories: arXiv_CL
tags: arXiv_CL Review RNN Recommendation
author: Felipe Costa, Sixun Ouyang, Peter Dolog, Aonghus Lawlor
mathjax: true
---

* content
{:toc}

##### Abstract
An important task for recommender system is to generate explanations according to a user's preferences. Most of the current methods for explainable recommendations use structured sentences to provide descriptions along with the recommendations they produce. However, those methods have neglected the review-oriented way of writing a text, even though it is known that these reviews have a strong influence over user's decision. In this paper, we propose a method for the automatic generation of natural language explanations, for predicting how a user would write about an item, based on user ratings from different items' features. We design a character-level recurrent neural network (RNN) model, which generates an item's review explanations using long-short term memories (LSTM). The model generates text reviews given a combination of the review and ratings score that express opinions about different factors or aspects of an item. Our network is trained on a sub-sample from the large real-world dataset BeerAdvocate. Our empirical evaluation using natural language processing metrics shows the generated text's quality is close to a real user written review, identifying negation, misspellings, and domain specific vocabulary.

##### Abstract (translated by Google)
推荐系统的一个重要任务是根据用户的喜好产生解释。目前大多数可解释的建议方法都是使用结构化的句子来提供描述以及他们提出的建议。然而，这些方法忽略了面向审查的文本写作方式，尽管已知这些评论对用户的决定有很大的影响。在本文中，我们提出了一种自动生成自然语言解释的方法，用于根据用户对不同项目特征的评分，预测用户如何撰写项目。我们设计了一个字符级递归神经网络（RNN）模型，它使用长期短期记忆（LSTM）生成一个项目的回顾解释。该模型生成文本评论，综合评论和评分得分，表达关于项目的不同因素或方面的意见。我们的网络接受来自大型真实世界数据集BeerAdvocate的子样本的训练。我们使用自然语言处理度量的实证评估显示生成的文本质量接近真实的用户书面评论，识别否定，拼写错误和领域特定的词汇。

##### URL
[https://arxiv.org/abs/1707.01561](https://arxiv.org/abs/1707.01561)

##### PDF
[https://arxiv.org/pdf/1707.01561](https://arxiv.org/pdf/1707.01561)

