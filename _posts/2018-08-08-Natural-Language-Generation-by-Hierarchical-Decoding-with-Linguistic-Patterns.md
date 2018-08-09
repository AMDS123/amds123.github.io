---
layout: post
title: "Natural Language Generation by Hierarchical Decoding with Linguistic Patterns"
date: 2018-08-08 13:12:10
categories: arXiv_CL
tags: arXiv_CL Knowledge Face RNN
author: Shang-Yu Su, Kai-Ling Lo, Yi-Ting Yeh, Yun-Nung Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language generation (NLG) is a critical component in spoken dialogue systems. Classic NLG can be divided into two phases: (1) sentence planning: deciding on the overall sentence structure, (2) surface realization: determining specific word forms and flattening the sentence structure into a string. Many simple NLG models are based on recurrent neural networks (RNN) and sequence-to-sequence (seq2seq) model, which basically contains an encoder-decoder structure; these NLG models generate sentences from scratch by jointly optimizing sentence planning and surface realization using a simple cross entropy loss training criterion. However, the simple encoder-decoder architecture usually suffers from generating complex and long sentences, because the decoder has to learn all grammar and diction knowledge. This paper introduces a hierarchical decoding NLG model based on linguistic patterns in different levels, and shows that the proposed method outperforms the traditional one with a smaller model size. Furthermore, the design of the hierarchical decoding is flexible and easily-extensible in various NLG systems.

##### Abstract (translated by Google)
自然语言生成（NLG）是口语对话系统中的关键组成部分。经典NLG可以分为两个阶段：（1）句子规划：决定整体句子结构，（2）表面实现：确定特定的单词形式并将句子结构展平成字符串。许多简单的NLG模型基于递归神经网络（RNN）和序列到序列（seq2seq）模型，其基本上包含编码器 - 解码器结构;这些NLG模型通过使用简单的交叉熵损失训练标准联合优化句子规划和表面实现，从头开始生成句子。然而，简单的编码器 - 解码器架构通常会产生复杂而长的句子，因为解码器必须学习所有语法和词汇知识。本文介绍了一种基于不同层次语言模式的分层解码NLG模型，表明该方法优于传统的模型尺寸较小的方法。此外，分层解码的设计在各种NLG系统中是灵活且易于扩展的。

##### URL
[http://arxiv.org/abs/1808.02747](http://arxiv.org/abs/1808.02747)

##### PDF
[http://arxiv.org/pdf/1808.02747](http://arxiv.org/pdf/1808.02747)

