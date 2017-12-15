---
layout: post
title: "Enhancing Sentence Relation Modeling with Auxiliary Character-level Embedding"
date: 2016-03-30 22:39:59
categories: arXiv_SD
tags: arXiv_SD Embedding RNN Relation
author: Peng Li, Heng Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Neural network based approaches for sentence relation modeling automatically generate hidden matching features from raw sentence pairs. However, the quality of matching feature representation may not be satisfied due to complex semantic relations such as entailment or contradiction. To address this challenge, we propose a new deep neural network architecture that jointly leverage pre-trained word embedding and auxiliary character embedding to learn sentence meanings. The two kinds of word sequence representations as inputs into multi-layer bidirectional LSTM to learn enhanced sentence representation. After that, we construct matching features followed by another temporal CNN to learn high-level hidden matching feature representations. Experimental results demonstrate that our approach consistently outperforms the existing methods on standard evaluation datasets.

##### Abstract (translated by Google)
基于神经网络的句子关系建模方法自动生成原始句对的隐藏匹配特征。然而，由于复杂的语义关系（如包含或矛盾），可能无法满足匹配特征表示的质量。为了解决这个问题，我们提出了一种新的深度神经网络架构，它将预训练词嵌入和辅助字符嵌入联合起来学习语义。将这两种单词序列表示作为输入到多层双向LSTM中以学习增强的句子表示。之后，我们构造匹配特征，然后构造另一个时间CNN，以学习高级隐藏匹配特征表示。实验结果表明，我们的方法始终胜过标准评估数据集上的现有方法。

##### URL
[https://arxiv.org/abs/1603.09405](https://arxiv.org/abs/1603.09405)

##### PDF
[https://arxiv.org/pdf/1603.09405](https://arxiv.org/pdf/1603.09405)

