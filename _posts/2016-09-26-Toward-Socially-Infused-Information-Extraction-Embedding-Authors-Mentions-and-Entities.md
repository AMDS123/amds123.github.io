---
layout: post
title: "Toward Socially-Infused Information Extraction: Embedding Authors, Mentions, and Entities"
date: 2016-09-26 17:19:07
categories: arXiv_CL
tags: arXiv_CL Knowledge Embedding Prediction
author: Yi Yang, Ming-Wei Chang, Jacob Eisenstein
mathjax: true
---

* content
{:toc}

##### Abstract
Entity linking is the task of identifying mentions of entities in text, and linking them to entries in a knowledge base. This task is especially difficult in microblogs, as there is little additional text to provide disambiguating context; rather, authors rely on an implicit common ground of shared knowledge with their readers. In this paper, we attempt to capture some of this implicit context by exploiting the social network structure in microblogs. We build on the theory of homophily, which implies that socially linked individuals share interests, and are therefore likely to mention the same sorts of entities. We implement this idea by encoding authors, mentions, and entities in a continuous vector space, which is constructed so that socially-connected authors have similar vector representations. These vectors are incorporated into a neural structured prediction model, which captures structural constraints that are inherent in the entity linking task. Together, these design decisions yield F1 improvements of 1%-5% on benchmark datasets, as compared to the previous state-of-the-art.

##### Abstract (translated by Google)
实体链接是识别文本中实体的提及，并将其链接到知识库中的条目的任务。这个任务在微博上是特别困难的，因为几乎没有额外的文本来提供消除歧义的上下文;相反，作者依赖与读者共享知识的共同基础。在本文中，我们试图通过利用微博中的社交网络结构来捕捉这些隐含的语境。我们建立在同源性理论基础上，这意味着社会关联的个体有共同的利益，因此可能会提到同样的实体。我们通过将作者，提及和实体编码在一个连续的向量空间中来实现这个想法，该连续的向量空间被构建，使得社交连接的作者具有相似的向量表示。这些向量被结合到神经结构预测模型中，其捕捉实体链接任务中固有的结构约束。与之前的技术水平相比，这些设计决策共同使基准数据集的F1的改进达到1％-5％。

##### URL
[https://arxiv.org/abs/1609.08084](https://arxiv.org/abs/1609.08084)

##### PDF
[https://arxiv.org/pdf/1609.08084](https://arxiv.org/pdf/1609.08084)

