---
layout: post
title: "Attention Focusing for Neural Machine Translation by Bridging Source and Target Embeddings"
date: 2018-05-10 05:13:59
categories: arXiv_CL
tags: arXiv_CL Attention Embedding Prediction
author: Shaohui Kuang, Junhui Li, Ant&#xf3;nio Branco, Weihua Luo, Deyi Xiong
mathjax: true
---

* content
{:toc}

##### Abstract
In neural machine translation, a source sequence of words is encoded into a vector from which a target sequence is generated in the decoding phase. Differently from statistical machine translation, the associations between source words and their possible target counterparts are not explicitly stored. Source and target words are at the two ends of a long information processing procedure, mediated by hidden states at both the source encoding and the target decoding phases. This makes it possible that a source word is incorrectly translated into a target word that is not any of its admissible equivalent counterparts in the target language. 
 In this paper, we seek to somewhat shorten the distance between source and target words in that procedure, and thus strengthen their association, by means of a method we term bridging source and target word embeddings. We experiment with three strategies: (1) a source-side bridging model, where source word embeddings are moved one step closer to the output target sequence; (2) a target-side bridging model, which explores the more relevant source word embeddings for the prediction of the target sequence; and (3) a direct bridging model, which directly connects source and target word embeddings seeking to minimize errors in the translation of ones by the others. 
 Experiments and analysis presented in this paper demonstrate that the proposed bridging models are able to significantly improve quality of both sentence translation, in general, and alignment and translation of individual source words with target words, in particular.

##### Abstract (translated by Google)
在神经机器翻译中，单词的源序列被编码成在解码阶段中从其生成目标序列的向量。与统计机器翻译不同，源词与其可能的目标对应词之间的关联没有明确存储。源词和目标词位于长信息处理过程的两端，由信源编码阶段和目标解码阶段的隐藏状态调解。这样就有可能将源词语错误地翻译成目标语言中的任何可接受的等同对象。
 在本文中，我们试图通过一种方法来缩短源程序与目标程序之间的距离，从而加强它们之间的关联，我们称之为桥接源语言和目标词语嵌入。我们尝试了三种策略：（1）源端桥接模型，其中源词嵌入被移动更靠近输出目标序列一步; （2）目标侧桥接模型，其探索用于预测目标序列的更相关的源词嵌入; （3）直接桥接模型，它直接连接源词和目标词的嵌入，以尽量减少其他词汇翻译错误。
 本文提供的实验和分析表明，所提出的桥接模型能够显着提高句子翻译的质量，特别是对单词与目标词的对齐和翻译。

##### URL
[http://arxiv.org/abs/1711.05380](http://arxiv.org/abs/1711.05380)

##### PDF
[http://arxiv.org/pdf/1711.05380](http://arxiv.org/pdf/1711.05380)

