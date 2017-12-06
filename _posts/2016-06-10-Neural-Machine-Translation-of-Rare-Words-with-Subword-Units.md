---
layout: post
title: "Neural Machine Translation of Rare Words with Subword Units"
date: 2016-06-10 14:45:08
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Rico Sennrich, Barry Haddow, Alexandra Birch
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT) models typically operate with a fixed vocabulary, but translation is an open-vocabulary problem. Previous work addresses the translation of out-of-vocabulary words by backing off to a dictionary. In this paper, we introduce a simpler and more effective approach, making the NMT model capable of open-vocabulary translation by encoding rare and unknown words as sequences of subword units. This is based on the intuition that various word classes are translatable via smaller units than words, for instance names (via character copying or transliteration), compounds (via compositional translation), and cognates and loanwords (via phonological and morphological transformations). We discuss the suitability of different word segmentation techniques, including simple character n-gram models and a segmentation based on the byte pair encoding compression algorithm, and empirically show that subword models improve over a back-off dictionary baseline for the WMT 15 translation tasks English-German and English-Russian by 1.1 and 1.3 BLEU, respectively.

##### Abstract (translated by Google)
神经机器翻译（NMT）模型通常以固定的词汇表进行操作，但翻译是一个开放词汇的问题。以前的工作通过备份到字典来解决词典外的单词的翻译。在本文中，我们引入一个更简单和更有效的方法，使NMT模型能够开放词汇表翻译通过编码罕见和未知的单词作为子序列的单词。这是基于这样的直觉，即各种单词类别可以通过比单词更小的单位来翻译，例如（通过字符复制或音译）名称，化合物（通过构成翻译）以及同源词和借词（通过音韵和形态变换）。我们讨论了不同分词技术的适用性，包括简单字符n-gram模型和基于字节对编码压缩算法的分词，并且经验性地表明子词模型在WMT 15翻译任务的退避字典基线上得到了改进。 - 德语和英语 - 俄语分别为1.1和1.3 BLEU。

##### URL
[https://arxiv.org/abs/1508.07909](https://arxiv.org/abs/1508.07909)

