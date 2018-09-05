---
layout: post
title: "Finding the Answers with Definition Models"
date: 2018-09-01 17:21:01
categories: arXiv_AI
tags: arXiv_AI Segmentation RNN Language_Model
author: Jack Parry
mathjax: true
---

* content
{:toc}

##### Abstract
Inspired by a previous attempt to answer crossword questions using neural networks (Hill, Cho, Korhonen, &amp; Bengio, 2015), this dissertation implements extensions to improve the performance of this existing definition model on the task of answering crossword questions. A discussion and evaluation of the original implementation finds that there are some ways in which the recurrent neural model could be extended. Insights from related fields neural language modeling and neural machine translation provide the justification and means required for these extensions. Two extensions are applied to the LSTM encoder, first taking the average of LSTM states across the sequence and secondly using a bidirectional LSTM, both implementations serve to improve model performance on a definitions and crossword test set. In order to improve performance on crossword questions, the training data is increased to include crossword questions and answers, and this serves to improve results on definitions as well as crossword questions. The final experiments are conducted using sub-word unit segmentation, first on the source side and then later preliminary experimentation is conducted to facilitate character-level output. Initially, an exact reproduction of the baseline results proves unsuccessful. Despite this, the extensions improve performance, allowing the definition model to surpass the performance of the recurrent neural network variants of the previous work (Hill, et al., 2015).

##### Abstract (translated by Google)
受先前尝试使用神经网络回答填字游戏问题的启发（Hill，Cho，Korhonen，＆amp; Bengio，2015），本论文实现了扩展，以改善现有定义模型在回答填字游戏问题上的表现。对原始实现的讨论和评估发现，有一些方法可以扩展递归神经模型。相关领域的见解神经语言建模和神经机器翻译提供了这些扩展所需的理由和手段。两个扩展应用于LSTM编码器，首先获取序列中LSTM状态的平均值，然后使用双向LSTM，这两种实现都用于提高定义和填字游戏测试集的模型性能。为了提高填字游戏问题的性能，培训数据增加到包括填字游戏问题和答案，这有助于改进定义和填字游戏问题的结果。最后的实验是使用子字单元分割进行的，首先在源侧进行，然后进行初步实验以促进字符级输出。最初，基线结果的精确复制证明是不成功的。尽管如此，扩展提高了性能，允许定义模型超越先前工作的递归神经网络变体的性能（Hill，et al。，2015）。

##### URL
[http://arxiv.org/abs/1809.00224](http://arxiv.org/abs/1809.00224)

##### PDF
[http://arxiv.org/pdf/1809.00224](http://arxiv.org/pdf/1809.00224)

