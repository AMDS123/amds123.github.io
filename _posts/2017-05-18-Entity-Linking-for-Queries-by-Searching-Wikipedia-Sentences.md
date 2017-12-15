---
layout: post
title: "Entity Linking for Queries by Searching Wikipedia Sentences"
date: 2017-05-18 08:03:49
categories: arXiv_CL
tags: arXiv_CL Embedding
author: Chuanqi Tan, Furu Wei, Pengjie Ren, Weifeng Lv, Ming Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple yet effective approach for linking entities in queries. The key idea is to search sentences similar to a query from Wikipedia articles and directly use the human-annotated entities in the similar sentences as candidate entities for the query. Then, we employ a rich set of features, such as link-probability, context-matching, word embeddings, and relatedness among candidate entities as well as their related entities, to rank the candidates under a regression based framework. The advantages of our approach lie in two aspects, which contribute to the ranking process and final linking result. First, it can greatly reduce the number of candidate entities by filtering out irrelevant entities with the words in the query. Second, we can obtain the query sensitive prior probability in addition to the static link-probability derived from all Wikipedia articles. We conduct experiments on two benchmark datasets on entity linking for queries, namely the ERD14 dataset and the GERDAQ dataset. Experimental results show that our method outperforms state-of-the-art systems and yields 75.0% in F1 on the ERD14 dataset and 56.9% on the GERDAQ dataset.

##### Abstract (translated by Google)
我们提出了一个简单而有效的方法来连接查询中的实体。关键的思想是搜索类似于维基百科文章中的查询的句子，并直接使用类似句子中的人标注实体作为查询的候选实体。然后，在候选实体及其相关实体之间使用丰富的特征，如链接概率，上下文匹配，单词嵌入和相关性，在基于回归的框架下对候选进行排名。我们的方法的优点在于两个方面，这有助于排名过程和最终链接结果。首先，通过在查询中筛选出不相关的实体，可以大大减少候选实体的数量。其次，除了从所有维基百科文章导出的静态链接概率之外，我们还可以获得查询敏感的先验概率。我们在查询实体链接的两个基准数据集上进行实验，即ERD14数据集和GERDAQ数据集。实验结果表明，我们的方法胜过了最先进的系统，在ERD14数据集中F1的产率为75.0％，GERDAQ数据集的产量为56.9％。

##### URL
[https://arxiv.org/abs/1704.02788](https://arxiv.org/abs/1704.02788)

##### PDF
[https://arxiv.org/pdf/1704.02788](https://arxiv.org/pdf/1704.02788)

