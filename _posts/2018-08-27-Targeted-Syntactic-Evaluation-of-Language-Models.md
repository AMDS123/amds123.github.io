---
layout: post
title: "Targeted Syntactic Evaluation of Language Models"
date: 2018-08-27 20:42:51
categories: arXiv_CL
tags: arXiv_CL RNN Language_Model Prediction
author: Rebecca Marvin, Tal Linzen
mathjax: true
---

* content
{:toc}

##### Abstract
We present a dataset for evaluating the grammaticality of the predictions of a language model. We automatically construct a large number of minimally different pairs of English sentences, each consisting of a grammatical and an ungrammatical sentence. The sentence pairs represent different variations of structure-sensitive phenomena: subject-verb agreement, reflexive anaphora and negative polarity items. We expect a language model to assign a higher probability to the grammatical sentence than the ungrammatical one. In an experiment using this data set, an LSTM language model performed poorly on many of the constructions. Multi-task training with a syntactic objective (CCG supertagging) improved the LSTM's accuracy, but a large gap remained between its performance and the accuracy of human participants recruited online. This suggests that there is considerable room for improvement over LSTMs in capturing syntax in a language model.

##### Abstract (translated by Google)
我们提出了一个数据集，用于评估语言模型预测的语法。我们自动构造大量极小不同的英语句子，每个句子由一个语法和一个不合语法的句子组成。句子对代表结构敏感现象的不同变化：主语 - 动词一致，反身回指和负极性项。我们期望语言模型为语法句子分配比不语法句子更高的概率。在使用该数据集的实验中，LSTM语言模型在许多结构上表现不佳。具有句法目标的多任务训练（CCG超级标准）提高了LSTM的准确性，但其性能与在线招募的人类参与者的准确性之间仍存在较大差距。这表明在捕获语言模型中的语法时，LSTM存在相当大的改进空间。

##### URL
[http://arxiv.org/abs/1808.09031](http://arxiv.org/abs/1808.09031)

##### PDF
[http://arxiv.org/pdf/1808.09031](http://arxiv.org/pdf/1808.09031)

