---
layout: post
title: 'Translating Phrases in Neural Machine Translation'
date: 2017-12-06 02:59:39
categories: arXiv_CL
tags: arXiv_CL NMT
author: Xing Wang, Zhaopeng Tu, Deyi Xiong, Min Zhang
---

* content
{:toc}

##### Abstract
Phrases play an important role in natural language understanding and machine translation (Sag et al., 2002; Villavicencio et al., 2005). However, it is difficult to integrate them into current neural machine translation (NMT) which reads and generates sentences word by word. In this work, we propose a method to translate phrases in NMT by integrating a phrase memory storing target phrases from a phrase-based statistical machine translation (SMT) system into the encoder-decoder architecture of NMT. At each decoding step, the phrase memory is first re-written by the SMT model, which dynamically generates relevant target phrases with contextual information provided by the NMT model. Then the proposed model reads the phrase memory to make probability estimations for all phrases in the phrase memory. If phrase generation is carried on, the NMT decoder selects an appropriate phrase from the memory to perform phrase translation and updates its decoding state by consuming the words in the selected phrase. Otherwise, the NMT decoder generates a word from the vocabulary as the general NMT decoder does. Experiment results on the Chinese to English translation show that the proposed model achieves significant improvements over the baseline on various test sets.

##### Abstract (translated by Google)
短语在自然语言理解和机器翻译中起着重要的作用（Sag等人，2002; Villavicencio等人，2005）。然而，很难将它们整合到当前逐字读取和生成句子的神经机器翻译（NMT）中。在这项工作中，我们提出了一种在NMT中翻译短语的方法，通过将基于短语的统计机器翻译（SMT）系统的短语存储器存储到NMT的编码器 - 解码器体系结构中。在每个解码步骤中，短语存储器首先由SMT模型重写，该模型利用NMT模型提供的上下文信息动态生成相关目标短语。然后，所提出的模型读取词组记忆以对词组记忆中的所有词组进行概率估计。如果进行短语生成，则NMT解码器从存储器中选择适当的短语来执行短语翻译，并通过消耗所选短语中的单词来更新其解码状态。否则，NMT解码器就像一般的NMT解码器那样从词汇表中产生一个单词。汉英翻译的实验结果表明，所提出的模型在各种测试集上都比基线有了显着的提高。

##### URL
[https://arxiv.org/abs/1708.01980](https://arxiv.org/abs/1708.01980)

