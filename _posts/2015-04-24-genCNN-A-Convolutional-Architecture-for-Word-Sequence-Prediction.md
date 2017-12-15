---
layout: post
title: "$gen$CNN: A Convolutional Architecture for Word Sequence Prediction"
date: 2015-04-24 08:44:05
categories: arXiv_CL
tags: arXiv_CL Text_Generation CNN RNN Language_Model Prediction Relation
author: Mingxuan Wang, Zhengdong Lu, Hang Li, Wenbin Jiang, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel convolutional architecture, named $gen$CNN, for word sequence prediction. Different from previous work on neural network-based language modeling and generation (e.g., RNN or LSTM), we choose not to greedily summarize the history of words as a fixed length vector. Instead, we use a convolutional neural network to predict the next word with the history of words of variable length. Also different from the existing feedforward networks for language modeling, our model can effectively fuse the local correlation and global correlation in the word sequence, with a convolution-gating strategy specifically designed for the task. We argue that our model can give adequate representation of the history, and therefore can naturally exploit both the short and long range dependencies. Our model is fast, easy to train, and readily parallelized. Our extensive experiments on text generation and $n$-best re-ranking in machine translation show that $gen$CNN outperforms the state-of-the-arts with big margins.

##### Abstract (translated by Google)
我们提出了一种新的卷积结构，名为$ gen $ CNN，用于单词序列预测。不同于以前在基于神经网络的语言建模和生成（例如，RNN或LSTM）方面的工作，我们选择不要贪婪地总结作为固定长度向量的词的历史。相反，我们使用卷积神经网络来预测具有可变长度的单词的历史的下一个单词。与现有的语言建模前馈网络不同，我们的模型可以有效地融合词序中的局部相关性和全局相关性，并且专门为这个任务设计了卷积门控策略。我们认为，我们的模型可以给出足够的历史表示，因此可以自然地利用短期和长期的依赖关系。我们的模型速度快，易于训练，并且易于并行化。我们在文本生成方面进行的大量实验以及机器翻译中的最佳重新排名显示，CNN $ CNN的表现优于现有技术，利润空间大。

##### URL
[https://arxiv.org/abs/1503.05034](https://arxiv.org/abs/1503.05034)

##### PDF
[https://arxiv.org/pdf/1503.05034](https://arxiv.org/pdf/1503.05034)

