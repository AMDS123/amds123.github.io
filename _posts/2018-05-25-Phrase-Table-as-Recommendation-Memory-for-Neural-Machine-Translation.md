---
layout: post
title: "Phrase Table as Recommendation Memory for Neural Machine Translation"
date: 2018-05-25 03:14:27
categories: arXiv_CL
tags: arXiv_CL Attention NMT Prediction Recommendation
author: Yang Zhao, Yining Wang, Jiajun Zhang, Chengqing Zong
mathjax: true
---

* content
{:toc}

##### Abstract
Neural Machine Translation (NMT) has drawn much attention due to its promising translation performance recently. However, several studies indicate that NMT often generates fluent but unfaithful translations. In this paper, we propose a method to alleviate this problem by using a phrase table as recommendation memory. The main idea is to add bonus to words worthy of recommendation, so that NMT can make correct predictions. Specifically, we first derive a prefix tree to accommodate all the candidate target phrases by searching the phrase translation table according to the source sentence. Then, we construct a recommendation word set by matching between candidate target phrases and previously translated target words by NMT. After that, we determine the specific bonus value for each recommendable word by using the attention vector and phrase translation probability. Finally, we integrate this bonus value into NMT to improve the translation results. The extensive experiments demonstrate that the proposed methods obtain remarkable improvements over the strong attentionbased NMT.

##### Abstract (translated by Google)
近年来，神经机器翻译（NMT）因其良好的翻译表现而备受关注。然而，一些研究表明NMT通常会产生流畅但不忠实的翻译。在本文中，我们提出了一种通过使用短语表作为推荐记忆来减轻这个问题的方法。主要想法是为值得推荐的单词添加奖励，以便NMT可以做出正确的预测。具体而言，我们首先通过根据源句子搜索短语翻译表来导出前缀树以容纳所有候选目标短语。然后，我们通过NMT在候选目标词组与之前翻译的目标词之间进行匹配来构建推荐词集。之后，我们使用注意向量和短语翻译概率确定每个可推荐词的具体奖金值。最后，我们将此奖金值整合到NMT中以改进翻译结果。广泛的实验表明，所提出的方法在强烈注意力的NMT上获得了显着的改进。

##### URL
[http://arxiv.org/abs/1805.09960](http://arxiv.org/abs/1805.09960)

##### PDF
[http://arxiv.org/pdf/1805.09960](http://arxiv.org/pdf/1805.09960)

