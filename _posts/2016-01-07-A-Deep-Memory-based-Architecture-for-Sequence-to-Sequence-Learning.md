---
layout: post
title: "A Deep Memory-based Architecture for Sequence-to-Sequence Learning"
date: 2016-01-07 08:14:08
categories: arXiv_CL
tags: arXiv_CL Relation
author: Fandong Meng, Zhengdong Lu, Zhaopeng Tu, Hang Li, Qun Liu
mathjax: true
---

* content
{:toc}

##### Abstract
We propose DEEPMEMORY, a novel deep architecture for sequence-to-sequence learning, which performs the task through a series of nonlinear transformations from the representation of the input sequence (e.g., a Chinese sentence) to the final output sequence (e.g., translation to English). Inspired by the recently proposed Neural Turing Machine (Graves et al., 2014), we store the intermediate representations in stacked layers of memories, and use read-write operations on the memories to realize the nonlinear transformations between the representations. The types of transformations are designed in advance but the parameters are learned from data. Through layer-by-layer transformations, DEEPMEMORY can model complicated relations between sequences necessary for applications such as machine translation between distant languages. The architecture can be trained with normal back-propagation on sequenceto-sequence data, and the learning can be easily scaled up to a large corpus. DEEPMEMORY is broad enough to subsume the state-of-the-art neural translation model in (Bahdanau et al., 2015) as its special case, while significantly improving upon the model with its deeper architecture. Remarkably, DEEPMEMORY, being purely neural network-based, can achieve performance comparable to the traditional phrase-based machine translation system Moses with a small vocabulary and a modest parameter size.

##### Abstract (translated by Google)
我们提出DEEPMEMORY，这是一种新颖的序列到序列学习的深层架构，它通过从输入序列（例如，一个中文句子）的表示到最终输出序列的一系列非线性变换来执行任务（例如，翻译为英语）。受最近提出的Neural Turing Machine（Graves et al。，2014）的启发，我们将中间表示存储在存储器的堆栈层中，并对存储器使用读写操作来实现表示之间的非线性转换。预先设计了转换的类型，但参数是从数据中学习的。通过逐层转换，DEEPMEMORY可以为应用程序（如遥远语言之间的机器翻译）所需的序列之间的复杂关系建模。该架构可以通过在序列到序列数据上的正常的反向传播来训练，并且学习可以容易地扩展到大的语料库。 DEEPMEMORY的范围很广，足以包含（Bahdanau et al。，2015）最先进的神经翻译模型作为其特殊情况，同时其模型的深层结构也得到了显着改善。值得注意的是，DEEPMEMORY是纯粹的神经网络，可以达到与传统的基于短语的机器翻译系统Moses相媲美的性能，词汇量小，参数大小适中。

##### URL
[https://arxiv.org/abs/1506.06442](https://arxiv.org/abs/1506.06442)

##### PDF
[https://arxiv.org/pdf/1506.06442](https://arxiv.org/pdf/1506.06442)

