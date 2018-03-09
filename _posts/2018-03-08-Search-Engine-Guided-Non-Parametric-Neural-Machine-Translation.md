---
layout: post
title: "Search Engine Guided Non-Parametric Neural Machine Translation"
date: 2018-03-08 08:15:24
categories: arXiv_AI
tags: arXiv_AI Attention NMT
author: Jiatao Gu, Yong Wang, Kyunghyun Cho, Victor O.K. Li
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we extend an attention-based neural machine translation (NMT) model by allowing it to access an entire training set of parallel sentence pairs even after training. The proposed approach consists of two stages. In the first stage--retrieval stage--, an off-the-shelf, black-box search engine is used to retrieve a small subset of sentence pairs from a training set given a source sentence. These pairs are further filtered based on a fuzzy matching score based on edit distance. In the second stage--translation stage--, a novel translation model, called translation memory enhanced NMT (TM-NMT), seamlessly uses both the source sentence and a set of retrieved sentence pairs to perform the translation. Empirical evaluation on three language pairs (En-Fr, En-De, and En-Es) shows that the proposed approach significantly outperforms the baseline approach and the improvement is more significant when more relevant sentence pairs were retrieved.

##### Abstract (translated by Google)
在本文中，我们扩展了基于注意的神经机器翻译（NMT）模型，即使在训练之后，它也允许它访问整个训练集的平行句对。所提出的方法由两个阶段组成。在第一阶段 - 检索阶段中，使用现成的黑盒搜索引擎从给定源句子的训练集中检索句子对的小子集。根据基于编辑距离的模糊匹配分数对这些对进行进一步过滤。在第二阶段 - 翻译阶段，一种称为翻译记忆增强NMT（TM-NMT）的新翻译模型无缝地使用源句子和一组检索到的句子对来执行翻译。对三种语言对（En-Fr，En-De和En-Es）的实证评估表明，所提出的方法明显优于基准方法，并且当检索到更多相关的句对时改进更为显着。

##### URL
[http://arxiv.org/abs/1705.07267](http://arxiv.org/abs/1705.07267)

##### PDF
[http://arxiv.org/pdf/1705.07267](http://arxiv.org/pdf/1705.07267)

