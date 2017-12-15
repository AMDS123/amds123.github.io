---
layout: post
title: "Row-less Universal Schema"
date: 2016-04-21 15:39:01
categories: arXiv_CL
tags: arXiv_CL Knowledge Attention Relation
author: Patrick Verga, Andrew McCallum
mathjax: true
---

* content
{:toc}

##### Abstract
Universal schema jointly embeds knowledge bases and textual patterns to reason about entities and relations for automatic knowledge base construction and information extraction. In the past, entity pairs and relations were represented as learned vectors with compatibility determined by a scoring function, limiting generalization to unseen text patterns and entities. Recently, 'column-less' versions of Universal Schema have used compositional pattern encoders to generalize to all text patterns. In this work we take the next step and propose a 'row-less' model of universal schema, removing explicit entity pair representations. Instead of learning vector representations for each entity pair in our training set, we treat an entity pair as a function of its relation types. In experimental results on the FB15k-237 benchmark we demonstrate that we can match the performance of a comparable model with explicit entity pair representations using a model of attention over relation types. We further demonstrate that the model per- forms with nearly the same accuracy on entity pairs never seen during training.

##### Abstract (translated by Google)
通用模式共同嵌入知识库和文本模式，以推理自动知识库建设和信息抽取的实体和关系。在过去，实体对和关系被表示为学习向量，其兼容性由评分函数确定，限制对看不见的文本模式和实体的泛化。最近，通用模式的“无列”版本使用组合模式编码器来推广到所有的文本模式。在这项工作中，我们采取下一步，提出一个“无行”的通用模式模型，去除显式的实体对表示。我们没有为我们的训练集中的每个实体对学习矢量表示，而是将一个实体对视为其关系类型的函数。在FB15k-237基准测试的实验结果中，我们证明我们可以使用关注类型的关注模型来匹配具有显式实体对表示的可比较模型的性能。我们进一步证明，模型在训练过程中从未见过的实体对具有几乎相同的准确性。

##### URL
[https://arxiv.org/abs/1604.06361](https://arxiv.org/abs/1604.06361)

##### PDF
[https://arxiv.org/pdf/1604.06361](https://arxiv.org/pdf/1604.06361)

