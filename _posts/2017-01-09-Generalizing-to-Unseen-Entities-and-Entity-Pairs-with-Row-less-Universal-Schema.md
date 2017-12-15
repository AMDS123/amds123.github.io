---
layout: post
title: "Generalizing to Unseen Entities and Entity Pairs with Row-less Universal Schema"
date: 2017-01-09 21:46:47
categories: arXiv_CL
tags: arXiv_CL Sparse Knowledge Attention Embedding Prediction Relation
author: Patrick Verga, Arvind Neelakantan, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Universal schema predicts the types of entities and relations in a knowledge base (KB) by jointly embedding the union of all available schema types---not only types from multiple structured databases (such as Freebase or Wikipedia infoboxes), but also types expressed as textual patterns from raw text. This prediction is typically modeled as a matrix completion problem, with one type per column, and either one or two entities per row (in the case of entity types or binary relation types, respectively). Factorizing this sparsely observed matrix yields a learned vector embedding for each row and each column. In this paper we explore the problem of making predictions for entities or entity-pairs unseen at training time (and hence without a pre-learned row embedding). We propose an approach having no per-row parameters at all; rather we produce a row vector on the fly using a learned aggregation function of the vectors of the observed columns for that row. We experiment with various aggregation functions, including neural network attention models. Our approach can be understood as a natural language database, in that questions about KB entities are answered by attending to textual or database evidence. In experiments predicting both relations and entity types, we demonstrate that despite having an order of magnitude fewer parameters than traditional universal schema, we can match the accuracy of the traditional model, and more importantly, we can now make predictions about unseen rows with nearly the same accuracy as rows available at training time.

##### Abstract (translated by Google)
通用模式通过联合嵌入所有可用模式类型的联合来预测知识库（KB）中的实体和关系的类型---不仅来自多个结构化数据库（例如Freebase或维基百科信息框）的类型，而且表达为来自原始文本的文本模式。这个预测通常被建模为矩阵完成问题，每列有一个类型，每行有一个或两个实体（分别是实体类型或二元关系类型）。将这个稀疏观察矩阵分解产生每行和每列的学习矢量嵌入。在本文中，我们探讨了在训练时间（因此没有预先学习的行嵌入）而看不到的实体或实体对的预测问题。我们提出一个没有每行参数的方法;相反，我们使用该行的观察列的向量的学习聚合函数即时产生行向量。我们尝试各种聚合函数，包括神经网络关注模型。我们的方法可以被理解为一个自然语言数据库，因为关于知识库实体的问题通过参考文本或数据库证据来回答。在预测关系和实体类型的实验中，我们证明尽管参数比传统通用模式少了一个数量级，我们可以匹配传统模型的准确性，更重要的是，我们现在可以预测几乎看不见的行与在训练时可用的相同的准确度。

##### URL
[https://arxiv.org/abs/1606.05804](https://arxiv.org/abs/1606.05804)

##### PDF
[https://arxiv.org/pdf/1606.05804](https://arxiv.org/pdf/1606.05804)

