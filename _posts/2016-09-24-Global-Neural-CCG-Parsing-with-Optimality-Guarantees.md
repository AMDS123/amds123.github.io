---
layout: post
title: "Global Neural CCG Parsing with Optimality Guarantees"
date: 2016-09-24 01:41:43
categories: arXiv_CL
tags: arXiv_CL
author: Kenton Lee, Mike Lewis, Luke Zettlemoyer
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce the first global recursive neural parsing model with optimality guarantees during decoding. To support global features, we give up dynamic programs and instead search directly in the space of all possible subtrees. Although this space is exponentially large in the sentence length, we show it is possible to learn an efficient A* parser. We augment existing parsing models, which have informative bounds on the outside score, with a global model that has loose bounds but only needs to model non-local phenomena. The global model is trained with a new objective that encourages the parser to explore a tiny fraction of the search space. The approach is applied to CCG parsing, improving state-of-the-art accuracy by 0.4 F1. The parser finds the optimal parse for 99.9% of held-out sentences, exploring on average only 190 subtrees.

##### Abstract (translated by Google)
在解码过程中，我们引入了第一个具有最优保证的全局递归神经解析模型。为了支持全局特征，我们放弃动态程序，直接在所有可能的子树的空间中搜索。虽然这个空间在句子长度上是指数级大的，但我们表明可以学习一个有效的A *解析器。我们用现有的解析模型来扩充现有的解析模型，这些解析模型在外部得分上具有信息边界，而全局模型具有松散的边界，但只需要模拟非局部现象。全球模式的训练有一个新的目标，鼓励解析器探索一小部分搜索空间。该方法适用于CCG解析，提高了0.4F1的最新精度。解析器找到99.9％的句子的最优解析，平均只探索190个子树。

##### URL
[https://arxiv.org/abs/1607.01432](https://arxiv.org/abs/1607.01432)

##### PDF
[https://arxiv.org/pdf/1607.01432](https://arxiv.org/pdf/1607.01432)

