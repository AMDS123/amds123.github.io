---
layout: post
title: "Vocabulary Manipulation for Neural Machine Translation"
date: 2016-05-10 20:50:56
categories: arXiv_CL
tags: arXiv_CL
author: Haitao Mi, Zhiguo Wang, Abe Ittycheriah
mathjax: true
---

* content
{:toc}

##### Abstract
In order to capture rich language phenomena, neural machine translation models have to use a large vocabulary size, which requires high computing time and large memory usage. In this paper, we alleviate this issue by introducing a sentence-level or batch-level vocabulary, which is only a very small sub-set of the full output vocabulary. For each sentence or batch, we only predict the target words in its sentence-level or batch-level vocabulary. Thus, we reduce both the computing time and the memory usage. Our method simply takes into account the translation options of each word or phrase in the source sentence, and picks a very small target vocabulary for each sentence based on a word-to-word translation model or a bilingual phrase library learned from a traditional machine translation model. Experimental results on the large-scale English-to-French task show that our method achieves better translation performance by 1 BLEU point over the large vocabulary neural machine translation system of Jean et al. (2015).

##### Abstract (translated by Google)
为了捕捉丰富的语言现象，神经机器翻译模型必须使用大量的词汇量，这需要高计算时间和大量的内存使用量。在本文中，我们通过引入一个句子级别或批次级别的词汇来缓解这个问题，这个词汇只是整个输出词汇的一个非常小的子集。对于每个句子或批次，我们只能预测句子级别或批次级别词汇中的目标词汇。因此，我们减少了计算时间和内存使用量。我们的方法只考虑源句子中每个单词或短语的翻译选项，并且基于从传统机器翻译中学习的单词对单词翻译模型或双语短语库来为每个句子选择非常小的目标词汇模型。大规模英语到法语任务的实验结果表明，我们的方法在Jean等人的大词汇量神经机器翻译系统上通过1个BLEU点实现了更好的翻译性能。 （2015年）。

##### URL
[https://arxiv.org/abs/1605.03209](https://arxiv.org/abs/1605.03209)

##### PDF
[https://arxiv.org/pdf/1605.03209](https://arxiv.org/pdf/1605.03209)

