---
layout: post
title: "Neural Compositional Denotational Semantics for Question Answering"
date: 2018-08-29 17:43:11
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge RNN Gradient_Descent Relation
author: Nitish Gupta, Mike Lewis
mathjax: true
---

* content
{:toc}

##### Abstract
Answering compositional questions requiring multi-step reasoning is challenging. We introduce an end-to-end differentiable model for interpreting questions about a knowledge graph (KG), which is inspired by formal approaches to semantics. Each span of text is represented by a denotation in a KG and a vector that captures ungrounded aspects of meaning. Learned composition modules recursively combine constituent spans, culminating in a grounding for the complete sentence which answers the question. For example, to interpret "not green", the model represents "green" as a set of KG entities and "not" as a trainable ungrounded vector---and then uses this vector to parameterize a composition function that performs a complement operation. For each sentence, we build a parse chart subsuming all possible parses, allowing the model to jointly learn both the composition operators and output structure by gradient descent from end-task supervision. The model learns a variety of challenging semantic operators, such as quantifiers, disjunctions and composed relations, and infers latent syntactic structure. It also generalizes well to longer questions than seen in its training data, in contrast to RNN, its tree-based variants, and semantic parsing baselines.

##### Abstract (translated by Google)
回答需要多步推理的构成问题具有挑战性。我们引入了一个端到端可微分模型，用于解释有关知识图（KG）的问题，该模型的灵感来自语义的形式化方法。每个文本范围由KG中的表示和捕获意义的未接地方面的向量表示。学习的组合模块递归地组合成分跨度，最终为完整的句子奠定基础，从而回答问题。例如，为了解释“非绿色”，模型将“绿色”表示为一组KG实体，将“不”表示为可训练的未接地矢量---然后使用该向量来参数化执行补充操作的组合函数。对于每个句子，我们构建一个包含所有可能的解析的解析图表，允许模型通过终端任务监督的梯度下降来共同学习组合操作符和输出结构。该模型学习各种具有挑战性的语义算子，如量词，析取和组合关系，并推断出潜在的句法结构。与RNN，基于树的变体和语义解析基线相比，它还可以很好地推广到比其训练数据更长的问题。

##### URL
[http://arxiv.org/abs/1808.09942](http://arxiv.org/abs/1808.09942)

##### PDF
[http://arxiv.org/pdf/1808.09942](http://arxiv.org/pdf/1808.09942)

