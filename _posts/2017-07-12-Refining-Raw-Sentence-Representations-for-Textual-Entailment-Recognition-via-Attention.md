---
layout: post
title: "Refining Raw Sentence Representations for Textual Entailment Recognition via Attention"
date: 2017-07-12 07:23:58
categories: arXiv_CL
tags: arXiv_CL Attention RNN Classification Recognition
author: Jorge A. Balazs, Edison Marrese-Taylor, Pablo Loyola, Yutaka Matsuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we present the model used by the team Rivercorners for the 2017 RepEval shared task. First, our model separately encodes a pair of sentences into variable-length representations by using a bidirectional LSTM. Later, it creates fixed-length raw representations by means of simple aggregation functions, which are then refined using an attention mechanism. Finally it combines the refined representations of both sentences into a single vector to be used for classification. With this model we obtained test accuracies of 72.057% and 72.055% in the matched and mismatched evaluation tracks respectively, outperforming the LSTM baseline, and obtaining performances similar to a model that relies on shared information between sentences (ESIM). When using an ensemble both accuracies increased to 72.247% and 72.827% respectively.

##### Abstract (translated by Google)
在本文中，我们将介绍Rivercorners团队用于2017年RepEval共享任务的模型。首先，我们的模型通过使用双向LSTM将一对句子分别编码为可变长度表示。之后，它通过简单的聚合函数创建固定长度的原始表示，然后使用注意机制进行细化。最后它将两个句子的精炼表示组合成一个单独的向量用于分类。利用这个模型，我们分别在匹配和不匹配的评估轨道上获得了72.057％和72.055％的测试精度，性能优于LSTM基线，并且获得类似于依赖句子之间共享信息（ESIM）的模型的性能。当使用合奏时，两个精度分别增加到72.247％和72.827％。

##### URL
[https://arxiv.org/abs/1707.03103](https://arxiv.org/abs/1707.03103)

##### PDF
[https://arxiv.org/pdf/1707.03103](https://arxiv.org/pdf/1707.03103)

