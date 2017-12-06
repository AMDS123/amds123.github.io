---
layout: post
title: 'Incorporating Discrete Translation Lexicons into Neural Machine Translation'
date: 2017-12-06 09:36:23
categories: arXiv_CL
tags: arXiv_CL NMT
author: Philip Arthur, Graham Neubig, Satoshi Nakamura
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) often makes mistakes in translating low-frequency content words that are essential to understanding the meaning of the sentence. We propose a method to alleviate this problem by augmenting NMT systems with discrete translation lexicons that efficiently encode translations of these low-frequency words. We describe a method to calculate the lexicon probability of the next word in the translation candidate by using the attention vector of the NMT model to select which source word lexical probabilities the model should focus on. We test two methods to combine this probability with the standard NMT probability: (1) using it as a bias, and (2) linear interpolation. Experiments on two corpora show an improvement of 2.0-2.3 BLEU and 0.13-0.44 NIST score, and faster convergence time.

##### Abstract (translated by Google)
神经机器翻译（NMT）经常在翻译低频内容词时出错，这些词对于理解句子的含义是必不可少的。我们提出了一种方法来缓解这个问题，通过用离散的翻译词典扩充NMT系统来有效地编码这些低频词的翻译。我们通过使用NMT模型的注意向量来计算翻译候选者中的下一个词的词典概率来选择模型应该关注哪个词汇词概率的方法。我们测试了两种方法将这个概率与标准的NMT概率相结合：（1）用它作为偏差，（2）线性插值。对两个语料库的实验显示，2.0-2.3 BLEU和0.13-0.44 NIST得分的提高，收敛时间更快。

##### URL
[https://arxiv.org/abs/1606.02006](https://arxiv.org/abs/1606.02006)

