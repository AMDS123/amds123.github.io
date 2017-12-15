---
layout: post
title: "Lifted Rule Injection for Relation Embeddings"
date: 2016-09-23 20:40:25
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Represenation_Learning Inference Relation
author: Thomas Demeester, Tim Rocktäschel, Sebastian Riedel
mathjax: true
---

* content
{:toc}

##### Abstract
Methods based on representation learning currently hold the state-of-the-art in many natural language processing and knowledge base inference tasks. Yet, a major challenge is how to efficiently incorporate commonsense knowledge into such models. A recent approach regularizes relation and entity representations by propositionalization of first-order logic rules. However, propositionalization does not scale beyond domains with only few entities and rules. In this paper we present a highly efficient method for incorporating implication rules into distributed representations for automated knowledge base construction. We map entity-tuple embeddings into an approximately Boolean space and encourage a partial ordering over relation embeddings based on implication rules mined from WordNet. Surprisingly, we find that the strong restriction of the entity-tuple embedding space does not hurt the expressiveness of the model and even acts as a regularizer that improves generalization. By incorporating few commonsense rules, we achieve an increase of 2 percentage points mean average precision over a matrix factorization baseline, while observing a negligible increase in runtime.

##### Abstract (translated by Google)
基于表示学习的方法目前掌握着许多自然语言处理和知识库推理任务的最新技术。然而，如何有效地将常识性知识纳入这些模型是一个主要的挑战。最近的一种方法通过一阶逻辑规则的命题化来规范关系和实体表示。然而，命题化并没有扩展到仅有少数实体和规则的领域之外。在本文中，我们提出了一个高效的方法将隐含规则合并到分布式表示中以实现自动化知识库的构建。我们将实体元组嵌入映射到近似布尔空间，并根据从WordNet挖掘的蕴涵规则鼓励对关系嵌入进行偏序排序。令人惊讶的是，我们发现实体元组嵌入空间的强制约束不会损害模型的表达性，甚至可以作为一个改进泛化的调节器。通过纳入少数常识规则，我们在矩阵分解基线上实现了2个百分点的均值平均精度的提高，同时观察到运行时间可以忽略不计。

##### URL
[https://arxiv.org/abs/1606.08359](https://arxiv.org/abs/1606.08359)

##### PDF
[https://arxiv.org/pdf/1606.08359](https://arxiv.org/pdf/1606.08359)

