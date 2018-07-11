---
layout: post
title: "Enriching Knowledge Bases with Counting Quantifiers"
date: 2018-07-10 14:03:23
categories: arXiv_CL
tags: arXiv_CL Sparse Knowledge Relation
author: Paramita Mirza, Simon Razniewski, Fariz Darari, Gerhard Weikum
mathjax: true
---

* content
{:toc}

##### Abstract
Information extraction traditionally focuses on extracting relations between identifiable entities, such as &lt;Monterey, locatedIn, California&gt;. Yet, texts often also contain Counting information, stating that a subject is in a specific relation with a number of objects, without mentioning the objects themselves, for example, "California is divided into 58 counties". Such counting quantifiers can help in a variety of tasks such as query answering or knowledge base curation, but are neglected by prior work. This paper develops the first full-fledged system for extracting counting information from text, called CINEX. We employ distant supervision using fact counts from a knowledge base as training seeds, and develop novel techniques for dealing with several challenges: (i) non-maximal training seeds due to the incompleteness of knowledge bases, (ii) sparse and skewed observations in text sources, and (iii) high diversity of linguistic patterns. Experiments with five human-evaluated relations show that CINEX can achieve 60% average precision for extracting counting information. In a large-scale experiment, we demonstrate the potential for knowledge base enrichment by applying CINEX to 2,474 frequent relations in Wikidata. CINEX can assert the existence of 2.5M facts for 110 distinct relations, which is 28% more than the existing Wikidata facts for these relations.

##### Abstract (translated by Google)
信息提取传统上集中于提取可识别实体之间的关系，例如＆lt; Monterey，locatedIn，California＆gt;。然而，文本通常还包含计数信息，表明主题与许多对象具有特定的关系，而没有提及对象本身，例如，“加利福尼亚分为58个县”。这样的计数量化器可以帮助执行各种任务，例如查询应答或知识库管理，但是之前的工作会忽略这些任务。本文开发了第一个用于从文本中提取计数信息的完整系统，称为CINEX。我们利用知识库中的事实计数作为训练种子进行远程监督，并开发处理若干挑战的新技术：（i）由于知识库不完整而导致的非最大训练种子，（ii）文本中的稀疏和偏斜观察来源，以及（iii）语言模式的多样性。五项人为评估关系的实验表明，CINEX可以达到60％的平均精度，用于提取计数信息。在大规模实验中，我们通过将CINEX应用于维基数据中的2,474个频繁关系来展示知识库丰富的潜力。 CINEX可以断言存在110个不同关系的2.5M事实，这比这些关系的现有维基数据事实多28％。

##### URL
[http://arxiv.org/abs/1807.03656](http://arxiv.org/abs/1807.03656)

##### PDF
[http://arxiv.org/pdf/1807.03656](http://arxiv.org/pdf/1807.03656)

