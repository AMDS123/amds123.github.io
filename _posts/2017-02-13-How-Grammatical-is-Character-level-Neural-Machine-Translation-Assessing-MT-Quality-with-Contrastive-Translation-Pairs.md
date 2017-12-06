---
layout: post
title: "How Grammatical is Character-level Neural Machine Translation? Assessing MT Quality with Contrastive Translation Pairs"
date: 2017-02-13 09:59:05
categories: arXiv_CL
tags: arXiv_CL Segmentation NMT
author: Rico Sennrich
mathjax: true
---

* content
{:toc}

##### Abstract
Analysing translation quality in regards to specific linguistic phenomena has historically been difficult and time-consuming. Neural machine translation has the attractive property that it can produce scores for arbitrary translations, and we propose a novel method to assess how well NMT systems model specific linguistic phenomena such as agreement over long distances, the production of novel words, and the faithful translation of polarity. The core idea is that we measure whether a reference translation is more probable under a NMT model than a contrastive translation which introduces a specific type of error. We present LingEval97, a large-scale data set of 97000 contrastive translation pairs based on the WMT English->German translation task, with errors automatically created with simple rules. We report results for a number of systems, and find that recently introduced character-level NMT systems perform better at transliteration than models with byte-pair encoding (BPE) segmentation, but perform more poorly at morphosyntactic agreement, and translating discontiguous units of meaning.

##### Abstract (translated by Google)
根据具体的语言现象分析翻译质量历史上是困难和耗时的。神经机器翻译具有吸引人的特点，它可以产生任意翻译的分数，并且我们提出一种新的方法来评估NMT系统如何模拟特定的语言现象，例如长距离协议，小说词的产生，忠实的翻译极性。其核心思想是，我们衡量一个NMT模型下的参考翻译是否比引入特定类型错误的对比翻译更可能。 LingEval97是一个基于WMT英语 - >德语翻译任务的97000对比翻译对的大规模数据集，用简单的规则自动创建了错误。我们报告了一些系统的结果，发现最近引入的字符级NMT系统在音译方面比具有字节对编码（BPE）分割的模型表现更好，但是在形态句法协议方面表现较差，并且翻译不连续的意义单元。

##### URL
[https://arxiv.org/abs/1612.04629](https://arxiv.org/abs/1612.04629)

