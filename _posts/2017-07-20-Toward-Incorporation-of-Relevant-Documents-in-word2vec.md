---
layout: post
title: "Toward Incorporation of Relevant Documents in word2vec"
date: 2017-07-20 16:33:48
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Navid Rekabsaz, Bhaskar Mitra, Mihai Lupu, Allan Hanbury
mathjax: true
---

* content
{:toc}

##### Abstract
Recent advances in neural word embedding provide significant benefit to various information retrieval tasks. However as shown by recent studies, adapting the embedding models for the needs of IR tasks can bring considerable further improvements. The embedding models in general define the term relatedness by exploiting the terms' co-occurrences in short-window contexts. An alternative (and well-studied) approach in IR for related terms to a query is using local information i.e. a set of top-retrieved documents. In view of these two methods of term relatedness, in this work, we report our study on incorporating the local information of the query in the word embeddings. One main challenge in this direction is that the dense vectors of word embeddings and their estimation of term-to-term relatedness remain difficult to interpret and hard to analyze. As an alternative, explicit word representations propose vectors whose dimensions are easily interpretable, and recent methods show competitive performance to the dense vectors. We introduce a neural-based explicit representation, rooted in the conceptual ideas of the word2vec Skip-Gram model. The method provides interpretable explicit vectors while keeping the effectiveness of the Skip-Gram model. The evaluation of various explicit representations on word association collections shows that the newly proposed method out- performs the state-of-the-art explicit representations when tasked with ranking highly similar terms. Based on the introduced ex- plicit representation, we discuss our approaches on integrating local documents in globally-trained embedding models and discuss the preliminary results.

##### Abstract (translated by Google)
神经词嵌入的最新进展为各种信息检索任务提供了显着的益处。然而，正如最近的研究所显示的那样，针对IR任务的需求调整嵌入模型可以带来相当大的进一步改进。通常，嵌入模型通过利用术语“短窗口上下文中的共现”来定义术语相关性。 IR中对于查询的相关术语的另一种（并且被充分研究的）方法是使用本地信息，即一组顶级检索的文档。鉴于这两种术语相关性的方法，在本文中，我们报告了将查询的局部信息合并到单词嵌入中的研究。这个方向面临的一个主要挑战是，词嵌入的密集向量及其对术语相关性的估计仍然难以解释和难以分析。作为替代方案，明确的词语表示提出了维度容易解释的向量，并且最近的方法显示了对密集向量的有竞争力的表现。我们引入了一个基于神经的显式表示，植根于word2vec Skip-Gram模型的概念思想。该方法提供可解释的显式向量，同时保持Skip-Gram模型的有效性。各种关于词汇关联集合的显式表达的评估表明，当提出排序高度相似的词语时，新提出的方法可以显示最先进的显式表达。在引入的表示形式的基础上，我们讨论了将本地文档整合到全局训练的嵌入模型中的方法，并讨论了初步的结果。

##### URL
[https://arxiv.org/abs/1707.06598](https://arxiv.org/abs/1707.06598)

##### PDF
[https://arxiv.org/pdf/1707.06598](https://arxiv.org/pdf/1707.06598)

