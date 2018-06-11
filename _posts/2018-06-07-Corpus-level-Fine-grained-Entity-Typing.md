---
layout: post
title: "Corpus-level Fine-grained Entity Typing"
date: 2018-06-07 03:13:55
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Prediction
author: Yadollah Yaghoobzadeh, Heike Adel, Hinrich Sch&#xfc;tze
mathjax: true
---

* content
{:toc}

##### Abstract
This paper addresses the problem of corpus-level entity typing, i.e., inferring from a large corpus that an entity is a member of a class such as "food" or "artist". The application of entity typing we are interested in is knowledge base completion, specifically, to learn which classes an entity is a member of. We propose FIGMENT to tackle this problem. FIGMENT is embedding- based and combines (i) a global model that scores based on aggregated contextual information of an entity and (ii) a context model that first scores the individual occurrences of an entity and then aggregates the scores. Each of the two proposed models has some specific properties. For the global model, learning high quality entity representations is crucial because it is the only source used for the predictions. Therefore, we introduce representations using name and contexts of entities on the three levels of entity, word, and character. We show each has complementary information and a multi-level representation is the best. For the context model, we need to use distant supervision since the context-level labels are not available for entities. Distant supervised labels are noisy and this harms the performance of models. Therefore, we introduce and apply new algorithms for noise mitigation using multi-instance learning. We show the effectiveness of our models in a large entity typing dataset, built from Freebase.

##### Abstract (translated by Google)
本文讨论了语料库级实体类型的问题，即从大语料库推断实体是诸如“食物”或“艺术家”之类的成员。我们感兴趣的实体类型的应用是完成知识库，特别是要了解一个实体是哪个类的成员。我们提出FIGMENT来解决这个问题。 FIGMENT是基于嵌入的并且组合了（i）基于实体的聚合上下文信息评分的全局模型和（ii）首先对实体的单个实例进行评分然后聚合评分的上下文模型。两个建议模型中的每一个都有一些特定的属性。对于全球模型，学习高质量实体表示是至关重要的，因为它是用于预测的唯一来源。因此，我们使用实体的名称和上下文来介绍实体，词和字符三个层次上的表示。我们显示每个人都有补充信息，多层次表示是最好的。对于上下文模型，我们需要使用远程监督，因为上下文级别标签不适用于实体。遥远的监督标签是嘈杂的，这有损于模型的性能。因此，我们通过多实例学习引入并应用新的噪声抑制算法。我们展示了我们的模型在一个由Freebase构建的大型实体类型数据集中的有效性。

##### URL
[http://arxiv.org/abs/1708.02275](http://arxiv.org/abs/1708.02275)

##### PDF
[http://arxiv.org/pdf/1708.02275](http://arxiv.org/pdf/1708.02275)

