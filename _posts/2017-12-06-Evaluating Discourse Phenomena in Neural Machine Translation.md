---
layout: post
title: 'Evaluating Discourse Phenomena in Neural Machine Translation'
date: 2017-12-06 02:49:44
categories: arXiv_CL
tags: arXiv_CL
author: Rachel Bawden, Rico Sennrich, Alexandra Birch, Barry Haddow
---

* content
{:toc}

##### Abstract
For machine translation to tackle discourse phenomena, models must have access to extra-sentential linguistic context. There has been recent interest in modelling context in neural machine translation (NMT), but models have been principally evaluated with standard automatic metrics, poorly adapted to evaluating discourse phenomena. In this article, we present hand-crafted, discourse test sets, designed to test the models' ability to exploit previous source and target sentences. We investigate the performance of recently proposed multi-encoder NMT models trained on subtitles for English to French. We also explore a novel way of exploiting context from the previous sentence. Despite gains using BLEU, multi-encoder models give limited improvement in the handling of discourse phenomena: 50% accuracy on our coreference test set and 53.5% for coherence/cohesion (compared to a non-contextual baseline of 50%). A simple strategy of decoding the concatenation of the previous and current sentence leads to good performance, and our novel strategy of multi-encoding and decoding of two sentences leads to the best performance (72.5% for coreference and 57% for coherence/cohesion), highlighting the importance of target-side context.

##### Abstract (translated by Google)
对于机器翻译来处理话语现象，模型必须能够使用超常量的语言语境。近来对神经机器翻译（NMT）中的建模背景感兴趣，但是模型主要是用标准的自动度量标准评估的，不适合于评估话语现象。在本文中，我们提出了手工制作的话语测试集，旨在测试模型利用之前源语句和目标语句的能力。我们调查了最近提出的用于英语到法语的字幕训练的多编码器NMT模型的性能。我们还探索了一个新的方法来利用上一句的语境。尽管使用BLEU获益，但多编码器模型在语篇现象处理方面的改进有限：我们的共参考测试集的准确性为50％，相干性/内聚性为53.5％（与非上下文基线的50％相比）。一个简单的对前一个和当前句子连接进行解码的策略导致了良好的性能，并且我们的两个句子的多重编码和解码的新策略导致最好的表现（72.5％为共同性，57％为一致性/内聚性）突出了目标方面的重要性。

##### URL
[https://arxiv.org/abs/1711.00513](https://arxiv.org/abs/1711.00513)

