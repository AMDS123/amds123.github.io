---
layout: post
title: "SEE: Syntax-aware Entity Embedding for Neural Relation Extraction"
date: 2018-01-11 01:16:13
categories: arXiv_CL
tags: arXiv_CL Relation_Extraction Attention Embedding Classification Relation
author: Zhengqiu He, Wenliang Chen, Zhenghua Li, Meishan Zhang, Wei Zhang, Min Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
Distant supervised relation extraction is an efficient approach to scale relation extraction to very large corpora, and has been widely used to find novel relational facts from plain text. Recent studies on neural relation extraction have shown great progress on this task via modeling the sentences in low-dimensional spaces, but seldom considered syntax information to model the entities. In this paper, we propose to learn syntax-aware entity embedding for neural relation extraction. First, we encode the context of entities on a dependency tree as sentence-level entity embedding based on tree-GRU. Then, we utilize both intra-sentence and inter-sentence attentions to obtain sentence set-level entity embedding over all sentences containing the focus entity pair. Finally, we combine both sentence embedding and entity embedding for relation classification. We conduct experiments on a widely used real-world dataset and the experimental results show that our model can make full use of all informative instances and achieve state-of-the-art performance of relation extraction.

##### Abstract (translated by Google)
远程监督关系抽取是一种将关系抽取扩展到超大型语料库的有效方法，已被广泛用于从明文中找到新的关系事实。最近对神经关系提取的研究，通过对低维空间中的句子进行建模，在这个任务上取得了很大的进展，但很少考虑语法信息来模拟实体。在本文中，我们建议学习用于神经关系抽取的语法感知实体嵌入。首先，我们将依赖关系树上的实体上下文编码为基于树GRU的句子级实体嵌入。然后，我们利用句子内部和句子间的注意力来获取包含焦点实体对的所有句子的句子集合层次实体。最后，将句子嵌入和实体嵌入结合起来进行关系分类。我们在一个广泛使用的现实世界的数据集上进行实验，实验结果表明，我们的模型可以充分利用所有的信息实例，并实现关系抽取的最新性能。

##### URL
[http://arxiv.org/abs/1801.03603](http://arxiv.org/abs/1801.03603)

##### PDF
[http://arxiv.org/pdf/1801.03603](http://arxiv.org/pdf/1801.03603)

