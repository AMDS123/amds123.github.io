---
layout: post
title: "Embedding Multimodal Relational Data for Knowledge Base Completion"
date: 2018-09-05 06:07:31
categories: arXiv_AI
tags: arXiv_AI Knowledge Embedding Prediction Relation
author: Pouya Pezeshkpour, Liyan Chen, Sameer Singh
mathjax: true
---

* content
{:toc}

##### Abstract
Representing entities and relations in an embedding space is a well-studied approach for machine learning on relational data. Existing approaches, however, primarily focus on simple link structure between a finite set of entities, ignoring the variety of data types that are often used in knowledge bases, such as text, images, and numerical values. In this paper, we propose multimodal knowledge base embeddings (MKBE) that use different neural encoders for this variety of observed data, and combine them with existing relational models to learn embeddings of the entities and multimodal data. Further, using these learned embedings and different neural decoders, we introduce a novel multimodal imputation model to generate missing multimodal values, like text and images, from information in the knowledge base. We enrich existing relational datasets to create two novel benchmarks that contain additional information such as textual descriptions and images of the original entities. We demonstrate that our models utilize this additional information effectively to provide more accurate link prediction, achieving state-of-the-art results with a considerable gap of 5-7% over existing methods. Further, we evaluate the quality of our generated multimodal values via a user study. We have release the datasets and the open-source implementation of our models at https://github.com/pouyapez/mkbe.

##### Abstract (translated by Google)
在嵌入空间中表示实体和关系是用于关系数据的机器学习的充分研究的方法。然而，现有方法主要关注有限实体集之间的简单链接结构，忽略知识库中经常使用的各种数据类型，例如文本，图像和数值。在本文中，我们提出了多模态知识库嵌入（MKBE），它使用不同的神经编码器来处理这种观察数据，并将它们与现有的关系模型相结合，以学习实体和多模态数据的嵌入。此外，使用这些学习的嵌入和不同的神经解码器，我们引入了一种新的多模态插补模型，以从知识库中的信息生成缺失的多模态值，如文本和图像。我们丰富了现有的关系数据集，以创建两个新的基准，其中包含其他信息，如文本描述和原始实体的图像。我们证明了我们的模型有效地利用这些附加信息来提供更准确的链接预测，实现最先进的结果，与现有方法相差5-7％。此外，我们通过用户研究评估生成的多峰值的质量。我们已经在https://github.com/pouyapez/mkbe上发布了我们模型的数据集和开源实现。

##### URL
[http://arxiv.org/abs/1809.01341](http://arxiv.org/abs/1809.01341)

##### PDF
[http://arxiv.org/pdf/1809.01341](http://arxiv.org/pdf/1809.01341)

