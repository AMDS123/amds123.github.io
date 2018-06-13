---
layout: post
title: "Multilingual Sentiment Analysis: An RNN-Based Framework for Limited Data"
date: 2018-06-08 14:01:31
categories: arXiv_CL
tags: arXiv_CL Sentiment Review Embedding RNN
author: Ethem F. Can, Aysu Ezen-Can, Fazli Can
mathjax: true
---

* content
{:toc}

##### Abstract
Sentiment analysis is a widely studied NLP task where the goal is to determine opinions, emotions, and evaluations of users towards a product, an entity or a service that they are reviewing. One of the biggest challenges for sentiment analysis is that it is highly language dependent. Word embeddings, sentiment lexicons, and even annotated data are language specific. Further, optimizing models for each language is very time consuming and labor intensive especially for recurrent neural network models. From a resource perspective, it is very challenging to collect data for different languages. 
 In this paper, we look for an answer to the following research question: can a sentiment analysis model trained on a language be reused for sentiment analysis in other languages, Russian, Spanish, Turkish, and Dutch, where the data is more limited? Our goal is to build a single model in the language with the largest dataset available for the task, and reuse it for languages that have limited resources. For this purpose, we train a sentiment analysis model using recurrent neural networks with reviews in English. We then translate reviews in other languages and reuse this model to evaluate the sentiments. Experimental results show that our robust approach of single model trained on English reviews statistically significantly outperforms the baselines in several different languages.

##### Abstract (translated by Google)
情感分析是一项广泛研究的NLP任务，其目标是确定用户对他们正在审查的产品，实体或服务的意见，情绪和评估。情感分析最大的挑战之一是它高度依赖于语言。词嵌入，情感词典，甚至注释数据都是特定于语言的。此外，针对每种语言的优化模型非常耗时且劳动强度大，特别是对于递归神经网络模型。从资源角度来看，收集不同语言的数据非常具有挑战性。
 在本文中，我们寻找对以下研究问题的回答：对于语言的情绪分析模型是否可以重用于其他语言（俄语，西班牙语，土耳其语和荷兰语）中情感分析，数据更有限？我们的目标是用可用于任务的最大数据集的语言构建单一模型，并将其用于资源有限的语言。为此，我们使用具有英文评论的递归神经网络来训练情感分析模型。然后，我们翻译其他语言的评论，并重新使用此模型评估情绪。实验结果表明，我们在英语评论上训练的单一模型的稳健方法在统计学上显着优于几种不同语言的基线。

##### URL
[http://arxiv.org/abs/1806.04511](http://arxiv.org/abs/1806.04511)

##### PDF
[http://arxiv.org/pdf/1806.04511](http://arxiv.org/pdf/1806.04511)

