---
layout: post
title: "Japanese Predicate Conjugation for Neural Machine Translation"
date: 2018-05-25 08:56:43
categories: arXiv_CL
tags: arXiv_CL Face NMT
author: Michiki Kurosawa, Yukio Matsumura, Hayahide Yamagishi, Mamoru Komachi
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) has a drawback in that can generate only high-frequency words owing to the computational costs of the softmax function in the output layer. 
 In Japanese-English NMT, Japanese predicate conjugation causes an increase in vocabulary size. For example, one verb can have as many as 19 surface varieties. In this research, we focus on predicate conjugation for compressing the vocabulary size in Japanese. The vocabulary list is filled with the various forms of verbs. We propose methods using predicate conjugation information without discarding linguistic information. The proposed methods can generate low-frequency words and deal with unknown words. Two methods were considered to introduce conjugation information: the first considers it as a token (conjugation token) and the second considers it as an embedded vector (conjugation feature). 
 The results using these methods demonstrate that the vocabulary size can be compressed by approximately 86.1% (Tanaka corpus) and the NMT models can output the words not in the training data set. Furthermore, BLEU scores improved by 0.91 points in Japanese-to-English translation, and 0.32 points in English-to-Japanese translation with ASPEC.

##### Abstract (translated by Google)
由于输出层中softmax函数的计算成本，神经机器翻译（NMT）的缺点是只能生成高频词。
 在日语 - 英语NMT中，日语谓词连接导致词汇量增加。例如，一个动词可以有多达19个表面品种。在这项研究中，我们专注于用日语来压缩词汇量的谓词共轭。词汇表中充满了各种形式的动词。我们提出了使用谓词共轭信息而不丢弃语言信息的方法。所提出的方法可以生成低频词并处理未知词。两种方法被认为是引入共轭信息：第一种认为它是一个令牌（共轭标记），第二种认为它是嵌入向量（共轭特征）。
 使用这些方法的结果表明，词汇大小可以被压缩大约86.1％（田中语料库），并且NMT模型可以输出不在训练数据集中的词。此外，BLEU成绩在日语翻译中提高了0.91分，ASPEC在英文翻译中提高了0.32分。

##### URL
[http://arxiv.org/abs/1805.10047](http://arxiv.org/abs/1805.10047)

##### PDF
[http://arxiv.org/pdf/1805.10047](http://arxiv.org/pdf/1805.10047)

