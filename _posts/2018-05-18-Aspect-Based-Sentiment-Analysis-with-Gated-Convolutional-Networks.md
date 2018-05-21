---
layout: post
title: "Aspect Based Sentiment Analysis with Gated Convolutional Networks"
date: 2018-05-18 04:24:52
categories: arXiv_CL
tags: arXiv_CL Sentiment Attention CNN RNN
author: Wei Xue, Tao Li
mathjax: true
---

* content
{:toc}

##### Abstract
Aspect based sentiment analysis (ABSA) can provide more detailed information than general sentiment analysis, because it aims to predict the sentiment polarities of the given aspects or entities in text. We summarize previous approaches into two subtasks: aspect-category sentiment analysis (ACSA) and aspect-term sentiment analysis (ATSA). Most previous approaches employ long short-term memory and attention mechanisms to predict the sentiment polarity of the concerned targets, which are often complicated and need more training time. We propose a model based on convolutional neural networks and gating mechanisms, which is more accurate and efficient. First, the novel Gated Tanh-ReLU Units can selectively output the sentiment features according to the given aspect or entity. The architecture is much simpler than attention layer used in the existing models. Second, the computations of our model could be easily parallelized during training, because convolutional layers do not have time dependency as in LSTM layers, and gating units also work independently. The experiments on SemEval datasets demonstrate the efficiency and effectiveness of our models.

##### Abstract (translated by Google)
基于方面的情感分析（ABSA）可以提供比一般情感分析更详细的信息，因为它旨在预测文本中给定方面或实体的情感极性。我们将以前的方法归纳为两个子任务：纵向分类情感分析（ACSA）和方面期望情绪分析（ATSA）。大多数以前的方法使用长期的短期记忆和注意机制来预测相关目标的情绪极性，这往往是复杂的并且需要更多的训练时间。我们提出了一个基于卷积神经网络和门控机制的模型，它更加准确和高效。首先，新型门控Tanh-ReLU单元可以根据给定方面或实体有选择地输出情感特征。该架构比现有模型中使用的关注层简单得多。其次，我们模型的计算可以在训练期间容易并行化，因为卷积层不像LSTM层那样具有时间依赖性，并且选通单元也独立工作。 SemEval数据集上的实验证明了我们模型的效率和有效性。

##### URL
[http://arxiv.org/abs/1805.07043](http://arxiv.org/abs/1805.07043)

##### PDF
[http://arxiv.org/pdf/1805.07043](http://arxiv.org/pdf/1805.07043)

