---
layout: post
title: "Sentiment analysis based on rhetorical structure theory: Learning deep neural networks from discourse trees"
date: 2017-10-09 08:03:06
categories: arXiv_CL
tags: arXiv_CL Salient Sentiment Attention RNN Relation
author: Mathias Kraus, Stefan Feuerriegel
mathjax: true
---

* content
{:toc}

##### Abstract
Prominent applications of sentiment analysis are countless, covering areas such as marketing, customer service and communication. The conventional bag-of-words approach for measuring sentiment merely counts term frequencies; however, it neglects the position of the terms within the discourse. As a remedy, we develop a discourse-aware method that builds upon the discourse structure of documents. For this purpose, we utilize rhetorical structure theory to label (sub-)clauses according to their hierarchical relationships and then assign polarity scores to individual leaves. To learn from the resulting rhetorical structure, we propose a tensor-based, tree-structured deep neural network (named Discourse-LSTM) in order to process the complete discourse tree. The underlying attention mechanism infers the salient passages of narrative materials. In addition, we suggest two algorithms for data augmentation (node reordering and artificial leaf insertion) that increase our training set and reduce overfitting. Our benchmarks demonstrate the superior performance of our approach. Moreover, the attention mechanism reveals the salient text passages and thereby provides explanatory insights.

##### Abstract (translated by Google)
情感分析的突出应用是无数的，涵盖了营销，客户服务和沟通等领域。用于衡量情绪的传统袋子式方法仅计算术语频率;然而，它忽略了话语中术语的位置。作为一种补救措施，我们开发了一种基于文档话语结构的话语意识方法。为此，我们利用修辞结构理论根据层次关系对（子）子句进行标注，然后将极性分数分配给单个叶子。为了从最终的修辞结构中学习，我们提出了一个基于张量的，树状结构的深层神经网络（Discourse-LSTM）来处理完整的话语树。潜在的关注机制推断叙事材料的显着段落。另外，我们提出了两个用于数据增加（节点重新排序和人工叶插入）的算法，以增加我们的训练集并减少过度拟合。我们的基准证明了我们方法的优越性能。此外，注意机制揭示了显着的文本段落，从而提供解释性的见解。

##### URL
[https://arxiv.org/abs/1704.05228](https://arxiv.org/abs/1704.05228)

##### PDF
[https://arxiv.org/pdf/1704.05228](https://arxiv.org/pdf/1704.05228)

