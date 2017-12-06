---
layout: post
title: "Improving Neural Machine Translation through Phrase-based Forced Decoding"
date: 2017-11-01 12:25:20
categories: arXiv_CL
tags: arXiv_CL NMT
author: Jingyi Zhang, Masao Utiyama, Eiichro Sumita, Graham Neubig, Satoshi Nakamura
---

* content
{:toc}

##### Abstract
Compared to traditional statistical machine translation (SMT), neural machine translation (NMT) often sacrifices adequacy for the sake of fluency. We propose a method to combine the advantages of traditional SMT and NMT by exploiting an existing phrase-based SMT model to compute the phrase-based decoding cost for an NMT output and then using this cost to rerank the n-best NMT outputs. The main challenge in implementing this approach is that NMT outputs may not be in the search space of the standard phrase-based decoding algorithm, because the search space of phrase-based SMT is limited by the phrase-based translation rule table. We propose a soft forced decoding algorithm, which can always successfully find a decoding path for any NMT output. We show that using the forced decoding cost to rerank the NMT outputs can successfully improve translation quality on four different language pairs.

##### Abstract (translated by Google)
与传统的统计机器翻译（SMT）相比，神经机器翻译（NMT）常常为了流利而牺牲充足性。我们提出了一种方法，通过利用现有的基于短语的SMT模型来计算NMT输出的基于短语的解码成本，然后使用这个成本重新排序n个最佳的NMT输出，来结合传统SMT和NMT的优点。实现这种方法的主要挑战在于NMT输出可能不在标准的基于短语的解码算法的搜索空间中，因为基于短语的SMT的搜索空间受到基于短语的翻译规则表的限制。我们提出了一个软强制解码算法，它总是能够成功找到任何NMT输出的解码路径。我们表明，使用强制解码成本来重新排列NMT输出可以成功地提高四种不同语言对的翻译质量。

##### URL
[https://arxiv.org/abs/1711.00309](https://arxiv.org/abs/1711.00309)

