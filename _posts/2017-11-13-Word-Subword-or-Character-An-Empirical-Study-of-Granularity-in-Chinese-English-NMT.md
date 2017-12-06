---
layout: post
title: "Word, Subword or Character? An Empirical Study of Granularity in Chinese-English NMT"
date: 2017-11-13 07:42:56
categories: arXiv_CL
tags: arXiv_CL NMT
author: Yining Wang, Long Zhou, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural machine translation (NMT), a new approach to machine translation, has been proved to outperform conventional statistical machine translation (SMT) across a variety of language pairs. Translation is an open-vocabulary problem, but most existing NMT systems operate with a fixed vocabulary, which causes the incapability of translating rare words. This problem can be alleviated by using different translation granularities, such as character, subword and hybrid word-character. Translation involving Chinese is one of the most difficult tasks in machine translation, however, to the best of our knowledge, there has not been any other work exploring which translation granularity is most suitable for Chinese in NMT. In this paper, we conduct an extensive comparison using Chinese-English NMT as a case study. Furthermore, we discuss the advantages and disadvantages of various translation granularities in detail. Our experiments show that subword model performs best for Chinese-to-English translation with the vocabulary which is not so big while hybrid word-character model is most suitable for English-to-Chinese translation. Moreover, experiments of different granularities show that Hybrid_BPE method can achieve best result on Chinese-to-English translation task.

##### Abstract (translated by Google)
神经机器翻译（NMT）是一种新的机器翻译方法，已经被证明在各种语言对中胜过传统的统计机器翻译（SMT）。翻译是一个开放的词汇问题，但是大多数现有的NMT系统都是以固定的词汇来运作的，这导致翻译罕见词语的能力不足。这个问题可以通过使用不同的转换粒度来缓解，如字符，子字和混合字符。涉及汉语的翻译是机器翻译中最困难的任务之一，但据我们所知，目前还没有其他的工作正在探索哪种翻译粒度最适合汉语的NMT。在本文中，我们用中英文NMT作为一个案例进行了广泛的比较。此外，我们还详细讨论了各种翻译粒度的优缺点。我们的实验表明，子词模型在词汇量不是很大的情况下表现最好，而混合词模型最适合英汉翻译。而且，不同粒度的实验表明，Hybrid_BPE方法在汉英翻译任务中取得了最好的效果。

##### URL
[https://arxiv.org/abs/1711.04457](https://arxiv.org/abs/1711.04457)

