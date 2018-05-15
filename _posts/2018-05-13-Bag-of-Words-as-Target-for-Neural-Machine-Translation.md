---
layout: post
title: "Bag-of-Words as Target for Neural Machine Translation"
date: 2018-05-13 12:24:20
categories: arXiv_CL
tags: arXiv_CL
author: Shuming Ma, Xu Sun, Yizhong Wang, Junyang Lin
mathjax: true
---

* content
{:toc}

##### Abstract
A sentence can be translated into more than one correct sentences. However, most of the existing neural machine translation models only use one of the correct translations as the targets, and the other correct sentences are punished as the incorrect sentences in the training stage. Since most of the correct translations for one sentence share the similar bag-of-words, it is possible to distinguish the correct translations from the incorrect ones by the bag-of-words. In this paper, we propose an approach that uses both the sentences and the bag-of-words as targets in the training stage, in order to encourage the model to generate the potentially correct sentences that are not appeared in the training set. We evaluate our model on a Chinese-English translation dataset, and experiments show our model outperforms the strong baselines by the BLEU score of 4.55.

##### Abstract (translated by Google)
一个句子可以翻译成多个正确的句子。然而，现有的大多数神经机器翻译模型只使用其中一个正确的翻译作为目标，其他正确的句子在训练阶段被当作不正确的句子来惩罚。由于一个句子的大部分正确翻译共享相似的词组，所以可以通过词组区分正确的翻译和不正确的翻译。在本文中，我们提出了一种在训练阶段使用句子和词袋作为目标的方法，以便鼓励模型生成未在训练集中出现的潜在正确句子。我们在中英文翻译数据集上评估我们的模型，实验表明，我们的模型比BLEU得分4.55的强基线要好。

##### URL
[https://arxiv.org/abs/1805.04871](https://arxiv.org/abs/1805.04871)

##### PDF
[https://arxiv.org/pdf/1805.04871](https://arxiv.org/pdf/1805.04871)

