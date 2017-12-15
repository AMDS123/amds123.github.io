---
layout: post
title: "Query-by-Example Search with Discriminative Neural Acoustic Word Embeddings"
date: 2017-06-12 19:30:57
categories: arXiv_CL
tags: arXiv_CL Embedding RNN
author: Shane Settle, Keith Levin, Herman Kamper, Karen Livescu
mathjax: true
---

* content
{:toc}

##### Abstract
Query-by-example search often uses dynamic time warping (DTW) for comparing queries and proposed matching segments. Recent work has shown that comparing speech segments by representing them as fixed-dimensional vectors --- acoustic word embeddings --- and measuring their vector distance (e.g., cosine distance) can discriminate between words more accurately than DTW-based approaches. We consider an approach to query-by-example search that embeds both the query and database segments according to a neural model, followed by nearest-neighbor search to find the matching segments. Earlier work on embedding-based query-by-example, using template-based acoustic word embeddings, achieved competitive performance. We find that our embeddings, based on recurrent neural networks trained to optimize word discrimination, achieve substantial improvements in performance and run-time efficiency over the previous approaches.

##### Abstract (translated by Google)
通过示例查询经常使用动态时间规整（DTW）来比较查询和提议的匹配段。最近的工作表明，通过将语音片段表示为固定维向量---声学词汇嵌入---并测量它们的向量距离（例如，余弦距离）来比较语音片段可以比基于DTW的方法更准确地区分词语。我们考虑一种按照查询范例搜索的方法，其根据神经模型嵌入查询和数据库段，然后是最近邻搜索以找到匹配的段。之前有关使用基于模板的声学词嵌入的基于嵌入的基于查询的查询的工作取得了有竞争力的表现。我们发现，我们的嵌入，基于循环神经网络训练，以优化单词歧视，实现性能和运行时效率比以前的方法实质性的提高。

##### URL
[https://arxiv.org/abs/1706.03818](https://arxiv.org/abs/1706.03818)

##### PDF
[https://arxiv.org/pdf/1706.03818](https://arxiv.org/pdf/1706.03818)

