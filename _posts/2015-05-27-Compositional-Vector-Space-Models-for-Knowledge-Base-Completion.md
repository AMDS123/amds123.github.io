---
layout: post
title: "Compositional Vector Space Models for Knowledge Base Completion"
date: 2015-05-27 21:23:45
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Inference RNN Relation
author: Arvind Neelakantan, Benjamin Roth, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Knowledge base (KB) completion adds new facts to a KB by making inferences from existing facts, for example by inferring with high likelihood nationality(X,Y) from bornIn(X,Y). Most previous methods infer simple one-hop relational synonyms like this, or use as evidence a multi-hop relational path treated as an atomic feature, like bornIn(X,Z) -> containedIn(Z,Y). This paper presents an approach that reasons about conjunctions of multi-hop relations non-atomically, composing the implications of a path using a recursive neural network (RNN) that takes as inputs vector embeddings of the binary relation in the path. Not only does this allow us to generalize to paths unseen at training time, but also, with a single high-capacity RNN, to predict new relation types not seen when the compositional model was trained (zero-shot learning). We assemble a new dataset of over 52M relational triples, and show that our method improves over a traditional classifier by 11%, and a method leveraging pre-trained embeddings by 7%.

##### Abstract (translated by Google)
知识库（Knowledge Base，KB）的完成通过对现有事实进行推断，例如通过从出生（X，Y）中高度可能的国籍（X，Y）进行推断，为知识库增加了新的事实。大多数以前的方法都是这样推断简单的单跳关系同义词，或者将多跳关系路径用作原子特征，如bornIn（X，Z） - > containedIn（Z，Y）。本文提出了一种解决多跳关系非原子连接的方法，用递归神经网络（RNN）构成路径的含义，递归神经网络（RNN）将路径中二元关系的矢量嵌入作为输入。这不仅使我们能够推广到在训练时间看不见的路径，而且用单个高容量的RNN来预测当组合模型被训练时没有看到的新的关系类型（零点学习）。我们组装了一个超过52M关系三元组的新数据集，表明我们的方法比传统分类器改进了11％，并且使用了预先训练的嵌入7％的方法。

##### URL
[https://arxiv.org/abs/1504.06662](https://arxiv.org/abs/1504.06662)

##### PDF
[https://arxiv.org/pdf/1504.06662](https://arxiv.org/pdf/1504.06662)

