---
layout: post
title: 'Modeling Source Syntax for Neural Machine Translation'
date: 2017-12-06 03:09:44
categories: arXiv_CL
tags: arXiv_CL
author: Junhui Li, Deyi Xiong, Zhaopeng Tu, Muhua Zhu, Min Zhang, Guodong Zhou
---

* content
{:toc}

##### Abstract
Even though a linguistics-free sequence to sequence model in neural machine translation (NMT) has certain capability of implicitly learning syntactic information of source sentences, this paper shows that source syntax can be explicitly incorporated into NMT effectively to provide further improvements. Specifically, we linearize parse trees of source sentences to obtain structural label sequences. On the basis, we propose three different sorts of encoders to incorporate source syntax into NMT: 1) Parallel RNN encoder that learns word and label annotation vectors parallelly; 2) Hierarchical RNN encoder that learns word and label annotation vectors in a two-level hierarchy; and 3) Mixed RNN encoder that stitchingly learns word and label annotation vectors over sequences where words and labels are mixed. Experimentation on Chinese-to-English translation demonstrates that all the three proposed syntactic encoders are able to improve translation accuracy. It is interesting to note that the simplest RNN encoder, i.e., Mixed RNN encoder yields the best performance with an significant improvement of 1.4 BLEU points. Moreover, an in-depth analysis from several perspectives is provided to reveal how source syntax benefits NMT.

##### Abstract (translated by Google)
尽管神经机器翻译（NMT）中一个无语言序列的序列模型具有一定的隐式学习源句子句法信息的能力，但本文表明，源句法可以有效地纳入NMT中，以提供进一步的改进。具体而言，我们线性化源句子的分析树，以获得结构标签序列。在此基础上，提出了三种不同的编码器，将源语法并入NMT：1）并行RNN编码器，并行学习单词和标注注释向量; 2）分层RNN编码器，学习两级层次中的单词和标签注释向量;以及3）混合RNN编码器，其在词和标签混合的序列上拼接学习单词和标签注释向量。汉英翻译实验表明，所提出的三种语法编码器都能够提高翻译的准确性。值得注意的是，最简单的RNN编码器，即混合RNN编码器产生最好的性能，并且有1.4 BLEU点的显着改进。此外，还从多个角度进行了深入的分析，揭示了源语法如何有利于NMT。

##### URL
[https://arxiv.org/abs/1705.01020](https://arxiv.org/abs/1705.01020)

