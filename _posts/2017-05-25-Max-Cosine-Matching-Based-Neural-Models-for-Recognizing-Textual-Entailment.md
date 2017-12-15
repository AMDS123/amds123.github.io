---
layout: post
title: "Max-Cosine Matching Based Neural Models for Recognizing Textual Entailment"
date: 2017-05-25 05:45:42
categories: arXiv_CL
tags: arXiv_CL Embedding RNN Prediction
author: Zhipeng Xie, Junfeng Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Recognizing textual entailment is a fundamental task in a variety of text mining or natural language processing applications. This paper proposes a simple neural model for RTE problem. It first matches each word in the hypothesis with its most-similar word in the premise, producing an augmented representation of the hypothesis conditioned on the premise as a sequence of word pairs. The LSTM model is then used to model this augmented sequence, and the final output from the LSTM is fed into a softmax layer to make the prediction. Besides the base model, in order to enhance its performance, we also proposed three techniques: the integration of multiple word-embedding library, bi-way integration, and ensemble based on model averaging. Experimental results on the SNLI dataset have shown that the three techniques are effective in boosting the predicative accuracy and that our method outperforms several state-of-the-state ones.

##### Abstract (translated by Google)
识别文本蕴涵是各种文本挖掘或自然语言处理应用程序中的基本任务。本文提出了一个RTE问题的简单神经模型。它首先将假设中的每个单词与前提中最相似的单词进行匹配，产生一个以前提为条件的假设的增广表示形式作为一个单词对的序列。然后使用LSTM模型来对该增广序列进行建模，并且将来自LSTM的最终输出馈送到softmax层以进行预测。除基本模型外，为了提高其性能，本文还提出了三种技术：多词嵌入库的集成，双向集成和基于模型平均的集成。在SNLI数据集上的实验结果表明，这三种技术对于提高预测精度是有效的，而且我们的方法胜过了几个状态级别的方法。

##### URL
[https://arxiv.org/abs/1705.09054](https://arxiv.org/abs/1705.09054)

##### PDF
[https://arxiv.org/pdf/1705.09054](https://arxiv.org/pdf/1705.09054)

