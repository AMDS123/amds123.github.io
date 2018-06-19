---
layout: post
title: "Co-training Embeddings of Knowledge Graphs and Entity Descriptions for Cross-lingual Entity Alignment"
date: 2018-06-18 02:06:46
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Embedding Inference
author: Muhao Chen, Yingtao Tian, Kai-Wei Chang, Steven Skiena, Carlo Zaniolo
mathjax: true
---

* content
{:toc}

##### Abstract
Multilingual knowledge graph (KG) embeddings provide latent semantic representations of entities and structured knowledge with cross-lingual inferences, which benefit various knowledge-driven cross-lingual NLP tasks. However, precisely learning such cross-lingual inferences is usually hindered by the low coverage of entity alignment in many KGs. Since many multilingual KGs also provide literal descriptions of entities, in this paper, we introduce an embedding-based approach which leverages a weakly aligned multilingual KG for semi-supervised cross-lingual learning using entity descriptions. Our approach performs co-training of two embedding models, i.e. a multilingual KG embedding model and a multilingual literal description embedding model. The models are trained on a large Wikipedia-based trilingual dataset where most entity alignment is unknown to training. Experimental results show that the performance of the proposed approach on the entity alignment task improves at each iteration of co-training, and eventually reaches a stage at which it significantly surpasses previous approaches. We also show that our approach has promising abilities for zero-shot entity alignment, and cross-lingual KG completion.

##### Abstract (translated by Google)
多语言知识图（KG）嵌入通过跨语言推理提供实体和结构化知识的潜在语义表示，这有益于各种知识驱动的跨语言NLP任务。然而，正确地学习这种跨语言推理通常会阻碍许多幼儿园实体对齐的低覆盖率。由于许多多语种的KGs也提供实体的字面描述，本文中我们介绍一种基于嵌入的方法，该方法利用弱对齐的多语言KG用于使用实体描述进行半监督的跨语言学习。我们的方法对两种嵌入模型进行协同训练，即多语言KG嵌入模型和多语言文字描述嵌入模型。这些模型是基于大型维基百科的三语数据集进行训练的，大多数实体对齐方式对训练是未知的。实验结果表明，所提出的方法对实体对齐任务的性能在共同训练的每次迭代中都有所提高，并且最终达到了明显超过先前方法的阶段。我们还表明，我们的方法具有很好的零射实体对齐和跨语言KG完成的能力。

##### URL
[http://arxiv.org/abs/1806.06478](http://arxiv.org/abs/1806.06478)

##### PDF
[http://arxiv.org/pdf/1806.06478](http://arxiv.org/pdf/1806.06478)

