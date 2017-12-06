---
layout: post
title: "Pre-Translation for Neural Machine Translation"
date: 2016-10-17 18:14:24
categories: arXiv_CL
tags: arXiv_CL NMT
author: Jan Niehues, Eunah Cho, Thanh-Le Ha, Alex Waibel
---

* content
{:toc}

##### Abstract
Recently, the development of neural machine translation (NMT) has significantly improved the translation quality of automatic machine translation. While most sentences are more accurate and fluent than translations by statistical machine translation (SMT)-based systems, in some cases, the NMT system produces translations that have a completely different meaning. This is especially the case when rare words occur. When using statistical machine translation, it has already been shown that significant gains can be achieved by simplifying the input in a preprocessing step. A commonly used example is the pre-reordering approach. In this work, we used phrase-based machine translation to pre-translate the input into the target language. Then a neural machine translation system generates the final hypothesis using the pre-translation. Thereby, we use either only the output of the phrase-based machine translation (PBMT) system or a combination of the PBMT output and the source sentence. We evaluate the technique on the English to German translation task. Using this approach we are able to outperform the PBMT system as well as the baseline neural MT system by up to 2 BLEU points. We analyzed the influence of the quality of the initial system on the final result.

##### Abstract (translated by Google)
最近，神经机器翻译（NMT）的发展大大提高了自动机器翻译的翻译质量。虽然大多数句子比基于统计机器翻译（SMT）的翻译系统更精确和流利，但在某些情况下，NMT系统会生成具有完全不同含义的翻译。当稀有词语出现时尤其如此。在使用统计机器翻译时，已经表明通过在预处理步骤中简化输入可以获得显着的收益。一个常用的例子是预先重新排序的方法。在这项工作中，我们使用基于短语的机器翻译将输入预翻译成目标语言。然后，神经机器翻译系统使用预翻译生成最终假设。因此，我们只使用基于短语的机器翻译（PBMT）系统的输出，或者使用PBMT输出和源语句的组合。我们评估英语到德语翻译任务的技巧。使用这种方法，我们能够超越PBMT系统以及基线神经MT系统多达2个BLEU点。我们分析了初始系统质量对最终结果的影响。

##### URL
[https://arxiv.org/abs/1610.05243](https://arxiv.org/abs/1610.05243)

