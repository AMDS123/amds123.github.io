---
layout: post
title: "Improving Entity Linking by Modeling Latent Relations between Mentions"
date: 2018-04-27 18:28:24
categories: arXiv_CL
tags: arXiv_CL Knowledge Relation
author: Phong Le, Ivan Titov
mathjax: true
---

* content
{:toc}

##### Abstract
Entity linking involves aligning textual mentions of named entities to their corresponding entries in a knowledge base. Entity linking systems often exploit relations between textual mentions in a document (e.g., coreference) to decide if the linking decisions are compatible. Unlike previous approaches, which relied on supervised systems or heuristics to predict these relations, we treat relations as latent variables in our neural entity-linking model. We induce the relations without any supervision while optimizing the entity-linking system in an end-to-end fashion. Our multi-relational model achieves the best reported scores on the standard benchmark (AIDA-CoNLL) and substantially outperforms its relation-agnostic version. Its training also converges much faster, suggesting that the injected structural bias helps to explain regularities in the training data.

##### Abstract (translated by Google)
实体链接包括将命名实体的文本提及与知识库中的相应条目对齐。实体链接系统通常利用文档中文本提及（例如，共同参与）之间的关系来判断链接决定是否兼容。与以前的依靠监督系统或启发式预测这些关系的方法不同，我们将关系视为神经实体连接模型中的潜在变量。我们在没有任何监督的情况下引发关系，同时以端到端的方式优化实体链接系统。我们的多关系模型在标准基准测试（AIDA-CoNLL）上获得了最高的报告得分，并且大大优于其关系未知版本。它的训练也收敛得更快，这表明注入的结构性偏见有助于解释训练数据的规律性。

##### URL
[https://arxiv.org/abs/1804.10637](https://arxiv.org/abs/1804.10637)

##### PDF
[https://arxiv.org/pdf/1804.10637](https://arxiv.org/pdf/1804.10637)

