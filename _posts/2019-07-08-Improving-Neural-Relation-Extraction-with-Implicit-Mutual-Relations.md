---
layout: post
title: "Improving Neural Relation Extraction with Implicit Mutual Relations"
date: 2019-07-08 02:16:11
categories: arXiv_AI
tags: arXiv_AI Knowledge_Graph Knowledge Relation_Extraction Embedding RNN Relation
author: Jun Kuang, Yixin Cao, Jianbing Zheng, Xiangnan He, Ming Gao, Aoying Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Relation extraction (RE) aims at extracting the relation between two entities from the text corpora. It is a crucial task for Knowledge Graph (KG) construction. Most existing methods predict the relation between an entity pair by learning the relation from the training sentences, which contain the targeted entity pair. In contrast to existing distant supervision approaches that suffer from insufficient training corpora to extract relations, our proposal of mining implicit mutual relation from the massive unlabeled corpora transfers the semantic information of entity pairs into the RE model, which is more expressive and semantically plausible. After constructing an entity proximity graph based on the implicit mutual relations, we preserve the semantic relations of entity pairs via embedding each vertex of the graph into a low-dimensional space. As a result, we can easily and flexibly integrate the implicit mutual relations and other entity information, such as entity types, into the existing RE methods. 
 Our experimental results on a New York Times and another Google Distant Supervision datasets suggest that our proposed neural RE framework provides a promising improvement for the RE task, and significantly outperforms the state-of-the-art methods. Moreover, the component for mining implicit mutual relations is so flexible that can help to improve the performance of both CNN-based and RNN-based RE models significant.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.05333](http://arxiv.org/abs/1907.05333)

##### PDF
[http://arxiv.org/pdf/1907.05333](http://arxiv.org/pdf/1907.05333)

