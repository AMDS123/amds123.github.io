---
layout: post
title: "Mutual Information and Diverse Decoding Improve Neural Machine Translation"
date: 2016-03-22 21:15:30
categories: arXiv_SD
tags: arXiv_SD Attention RNN Relation
author: Jiwei Li, Dan Jurafsky
mathjax: true
---

* content
{:toc}

##### Abstract
Sequence-to-sequence neural translation models learn semantic and syntactic relations between sentence pairs by optimizing the likelihood of the target given the source, i.e., $p(y|x)$, an objective that ignores other potentially useful sources of information. We introduce an alternative objective function for neural MT that maximizes the mutual information between the source and target sentences, modeling the bi-directional dependency of sources and targets. We implement the model with a simple re-ranking method, and also introduce a decoding algorithm that increases diversity in the N-best list produced by the first pass. Applied to the WMT German/English and French/English tasks, the proposed models offers a consistent performance boost on both standard LSTM and attention-based neural MT architectures.

##### Abstract (translated by Google)
序列 - 序列神经翻译模型通过优化给定源的目标的可能性（即，$ p（y | x）$）来学习句子对之间的语义和句法关系，该目标忽略其他潜在有用的信息源。我们为神经MT引入了一个替代的目标函数，它使源句子和目标句子之间的互信息最大化，建立源和目标的双向依赖关系。我们用一个简单的重排序方法来实现模型，并且引入一个解码算法来增加第一遍产生的N-最佳列表的多样性。应用于WMT德语/英语和法语/英语任务，所提出的模型在标准LSTM和基于注意力的神经MT架构上都能提供一致的性能提升。

##### URL
[https://arxiv.org/abs/1601.00372](https://arxiv.org/abs/1601.00372)

##### PDF
[https://arxiv.org/pdf/1601.00372](https://arxiv.org/pdf/1601.00372)

