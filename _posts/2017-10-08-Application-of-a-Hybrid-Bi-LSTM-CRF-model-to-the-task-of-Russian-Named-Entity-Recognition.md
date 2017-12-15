---
layout: post
title: "Application of a Hybrid Bi-LSTM-CRF model to the task of Russian Named Entity Recognition"
date: 2017-10-08 09:13:41
categories: arXiv_CL
tags: arXiv_CL GAN Embedding RNN Prediction Recognition
author: L. T. Anh, M. Y. Arkhipov, M. S. Burtsev
mathjax: true
---

* content
{:toc}

##### Abstract
Named Entity Recognition (NER) is one of the most common tasks of the natural language processing. The purpose of NER is to find and classify tokens in text documents into predefined categories called tags, such as person names, quantity expressions, percentage expressions, names of locations, organizations, as well as expression of time, currency and others. Although there is a number of approaches have been proposed for this task in Russian language, it still has a substantial potential for the better solutions. In this work, we studied several deep neural network models starting from vanilla Bi-directional Long Short-Term Memory (Bi-LSTM) then supplementing it with Conditional Random Fields (CRF) as well as highway networks and finally adding external word embeddings. All models were evaluated across three datasets: Gareev's dataset, Person-1000, FactRuEval-2016. We found that extension of Bi-LSTM model with CRF significantly increased the quality of predictions. Encoding input tokens with external word embeddings reduced training time and allowed to achieve state of the art for the Russian NER task.

##### Abstract (translated by Google)
命名实体识别（NER）是自然语言处理中最常见的任务之一。 NER的目的是将文本文档中的标记找到并分类为预定义的标签类别，例如人名，数量表达式，百分比表达式，位置名称，组织，以及时间，货币等的表达。尽管俄语提出了许多方法来解决这个问题，但它仍然有着更好的解决方案的潜力。在这项工作中，我们研究了从香草双向长短期记忆（Bi-LSTM）开始，然后用条件随机场（CRF）以及高速公路网络补充它的几个深度神经网络模型，最后添加外部字嵌入。所有模型都在三个数据集上进行评估：Gareev的数据集Person-1000，FactRuEval-2016。我们发现用CRF扩展Bi-LSTM模型显着提高了预测的质量。使用外部字嵌入对输入令牌进行编码减少了训练时间，并使俄罗斯NER任务达到了最高水平。

##### URL
[https://arxiv.org/abs/1709.09686](https://arxiv.org/abs/1709.09686)

##### PDF
[https://arxiv.org/pdf/1709.09686](https://arxiv.org/pdf/1709.09686)

