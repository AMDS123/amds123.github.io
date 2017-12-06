---
layout: post
title: 'Addressing the Rare Word Problem in Neural Machine Translation'
date: 2017-12-06 09:46:00
categories: arXiv_CL
tags: arXiv_CL NMT
author: Minh-Thang Luong, Ilya Sutskever, Quoc V. Le, Oriol Vinyals, Wojciech Zaremba
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) is a new approach to machine translation that has shown promising results that are comparable to traditional approaches. A significant weakness in conventional NMT systems is their inability to correctly translate very rare words: end-to-end NMTs tend to have relatively small vocabularies with a single unk symbol that represents every possible out-of-vocabulary (OOV) word. In this paper, we propose and implement an effective technique to address this problem. We train an NMT system on data that is augmented by the output of a word alignment algorithm, allowing the NMT system to emit, for each OOV word in the target sentence, the position of its corresponding word in the source sentence. This information is later utilized in a post-processing step that translates every OOV word using a dictionary. Our experiments on the WMT14 English to French translation task show that this method provides a substantial improvement of up to 2.8 BLEU points over an equivalent NMT system that does not use this technique. With 37.5 BLEU points, our NMT system is the first to surpass the best result achieved on a WMT14 contest task.

##### Abstract (translated by Google)
神经机器翻译（NMT）是机器翻译的新方法，已经显示出与传统方法相当的有希望的结果。传统NMT系统的一个显着弱点是它们不能正确翻译非常罕见的单词：端到端的NMT往往具有相对较小的词汇表，单个unk符号表示每个可能的词汇外（OOV）单词。在本文中，我们提出并实施一个有效的技术来解决这个问题。我们训练NMT系统的数据是由一个字对齐算法的输出增加，允许NMT系统发出，对目标句子中的每个OOV字，其相应的单词在源句子的位置。稍后在后处理步骤中使用该信息，该步骤使用字典翻译每个OOV字。我们在WMT14英语到法语翻译任务上的实验表明，与不使用此技术的等效NMT系统相比，此方法可提供高达2.8 BLEU点的实质性改进。我们的NMT系统以37.5 BLEU的分数首次超越WMT14比赛任务中取得的最佳成绩。

##### URL
[https://arxiv.org/abs/1410.8206](https://arxiv.org/abs/1410.8206)

