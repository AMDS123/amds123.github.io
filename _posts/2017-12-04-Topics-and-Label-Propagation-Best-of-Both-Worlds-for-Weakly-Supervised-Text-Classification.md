---
layout: post
title: "Topics and Label Propagation: Best of Both Worlds for Weakly Supervised Text Classification"
date: 2017-12-04 06:05:21
categories: arXiv_CL
tags: arXiv_CL Weakly_Supervised Text_Classification Classification
author: Sachin Pawar, Nitin Ramrakhiyani, Swapnil Hingmire, Girish K. Palshikar
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a Label Propagation based algorithm for weakly supervised text classification. We construct a graph where each document is represented by a node and edge weights represent similarities among the documents. Additionally, we discover underlying topics using Latent Dirichlet Allocation (LDA) and enrich the document graph by including the topics in the form of additional nodes. The edge weights between a topic and a text document represent level of "affinity" between them. Our approach does not require document level labelling, instead it expects manual labels only for topic nodes. This significantly minimizes the level of supervision needed as only a few topics are observed to be enough for achieving sufficiently high accuracy. The Label Propagation Algorithm is employed on this enriched graph to propagate labels among the nodes. Our approach combines the advantages of Label Propagation (through document-document similarities) and Topic Modelling (for minimal but smart supervision). We demonstrate the effectiveness of our approach on various datasets and compare with state-of-the-art weakly supervised text classification approaches.

##### Abstract (translated by Google)
我们提出了一个基于标签传播的弱监督文本分类算法。我们构造一个图形，其中每个文档由节点表示，边权重表示文档之间的相似性。此外，我们使用潜在狄利克雷分配（LDA）发现潜在主题，并通过以附加节点的形式包含主题来丰富文档图。主题和文本文档之间的边权重表示它们之间的“亲和度”级别。我们的方法不需要文档级标签，而只需要为主题节点设置手动标签。这显着降低了所需的监督水平，因为只有少数话题足以实现足够高的准确性。标签传播算法被用于这个富集图在节点间传播标签。我们的方法结合了标签传播（通过文档 - 文档相似性）和主题建模（用于最小但智能的监督）的优点。我们证明了我们的方法在各种数据集上的有效性，并与最先进的弱监督文本分类方法进行了比较。

##### URL
[http://arxiv.org/abs/1712.02767](http://arxiv.org/abs/1712.02767)

##### PDF
[http://arxiv.org/pdf/1712.02767](http://arxiv.org/pdf/1712.02767)

