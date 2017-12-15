---
layout: post
title: "Knowledge Enhanced Hybrid Neural Network for Text Matching"
date: 2016-11-15 03:11:59
categories: arXiv_CL
tags: arXiv_CL Knowledge CNN
author: Yu Wu, Wei Wu, Zhoujun Li, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Long text brings a big challenge to semantic matching due to their complicated semantic and syntactic structures. To tackle the challenge, we consider using prior knowledge to help identify useful information and filter out noise to matching in long text. To this end, we propose a knowledge enhanced hybrid neural network (KEHNN). The model fuses prior knowledge into word representations by knowledge gates and establishes three matching channels with words, sequential structures of sentences given by Gated Recurrent Units (GRU), and knowledge enhanced representations. The three channels are processed by a convolutional neural network to generate high level features for matching, and the features are synthesized as a matching score by a multilayer perceptron. The model extends the existing methods by conducting matching on words, local structures of sentences, and global context of sentences. Evaluation results from extensive experiments on public data sets for question answering and conversation show that KEHNN can significantly outperform the-state-of-the-art matching models and particularly improve the performance on pairs with long text.

##### Abstract (translated by Google)
长文本由于其复杂的语义和句法结构给语义匹配带来了巨大的挑战。为了应对这一挑战，我们考虑使用先前的知识来帮助识别有用的信息，并滤除噪音，以便在长文本中进行匹配。为此，我们提出了一个知识增强混合神经网络（KEHNN）。该模型将先验知识融合到知识门的词表示中，并建立了词汇的三个匹配通道，门控循环单元（GRU）给出句子的顺序结构以及知识增强表示。通过卷积神经网络对三个通道进行处理，生成高水平的匹配特征，并通过多层感知器将特征合成为匹配分数。该模型通过对单词，句子的局部结构以及句子的全局上下文进行匹配来扩展现有方法。通过对问答和对话的公共数据集进行大量实验的评估结果表明，KEHNN可以显着地胜过最先进的匹配模型，尤其是可以提高长文本对的性能。

##### URL
[https://arxiv.org/abs/1611.04684](https://arxiv.org/abs/1611.04684)

##### PDF
[https://arxiv.org/pdf/1611.04684](https://arxiv.org/pdf/1611.04684)

