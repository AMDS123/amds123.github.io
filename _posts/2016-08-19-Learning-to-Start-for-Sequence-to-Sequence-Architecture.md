---
layout: post
title: "Learning to Start for Sequence to Sequence Architecture"
date: 2016-08-19 09:48:13
categories: arXiv_CL
tags: arXiv_CL Face Relation
author: Qingfu Zhu, Weinan Zhang, Lianqiang Zhou, Ting Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The sequence to sequence architecture is widely used in the response generation and neural machine translation to model the potential relationship between two sentences. It typically consists of two parts: an encoder that reads from the source sentence and a decoder that generates the target sentence word by word according to the encoder's output and the last generated word. However, it faces to the cold start problem when generating the first word as there is no previous word to refer. Existing work mainly use a special start symbol </s>to generate the first word. An obvious drawback of these work is that there is not a learnable relationship between words and the start symbol. Furthermore, it may lead to the error accumulation for decoding when the first word is incorrectly generated. In this paper, we proposed a novel approach to learning to generate the first word in the sequence to sequence architecture rather than using the start symbol. Experimental results on the task of response generation of short text conversation show that the proposed approach outperforms the state-of-the-art approach in both of the automatic and manual evaluations.

##### Abstract (translated by Google)
序列结构的序列被广泛用于响应生成和神经机器翻译中，以模拟两个句子之间的潜在关系。它通常由两部分组成：一个从源语句读取的编码器和一个根据编码器的输出和最后生成的字单词生成目标语句的解码器。然而，在生成第一个单词时，由于没有以前的单词可供参考，所以它面临冷启动问题。现有的工作主要使用特殊的开始符号来生成第一个单词。这些工作的明显缺点是，单词和开始符号之间没有可学的关系。而且，当错误地产生第一个字时，可能导致解码的错误积累。在本文中，我们提出了一种新颖的学习方法来生成序列中的第一个单词，以对架构进行排序，而不是使用开始符号。短文本会话响应生成的实验结果表明，所提出的方法在自动评估和人工评估中均优于现有技术。

##### URL
[https://arxiv.org/abs/1608.05554](https://arxiv.org/abs/1608.05554)

##### PDF
[https://arxiv.org/pdf/1608.05554](https://arxiv.org/pdf/1608.05554)

