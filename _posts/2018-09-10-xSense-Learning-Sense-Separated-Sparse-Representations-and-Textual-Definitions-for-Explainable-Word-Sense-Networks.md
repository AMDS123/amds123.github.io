---
layout: post
title: "xSense: Learning Sense-Separated Sparse Representations and Textual Definitions for Explainable Word Sense Networks"
date: 2018-09-10 14:27:08
categories: arXiv_CL
tags: arXiv_CL Sparse Embedding RNN
author: Ting-Yun Chang, Ta-Chung Chi, Shang-Chi Tsai, Yun-Nung Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the success achieved on various natural language processing tasks, word embeddings are difficult to interpret due to the dense vector representations. This paper focuses on interpreting the embeddings for various aspects, including sense separation in the vector dimensions and definition generation. Specifically, given a context together with a target word, our algorithm first projects the target word embedding to a high-dimensional sparse vector and picks the specific dimensions that can best explain the semantic meaning of the target word by the encoded contextual information, where the sense of the target word can be indirectly inferred. Finally, our algorithm applies an RNN to generate the textual definition of the target word in the human readable form, which enables direct interpretation of the corresponding word embedding. This paper also introduces a large and high-quality context-definition dataset that consists of sense definitions together with multiple example sentences per polysemous word, which is a valuable resource for definition modeling and word sense disambiguation. The conducted experiments show the superior performance in BLEU score and the human evaluation test.

##### Abstract (translated by Google)
尽管在各种自然语言处理任务上取得了成功，但由于密集的矢量表示，字嵌入很难解释。本文侧重于解释各个方面的嵌入，包括向量维度和定义生成中的意义分离。具体来说，给定上下文和目标词，我们的算法首先将目标词嵌入投影到高维稀疏向量，并选择能够通过编码的上下文信息最好地解释目标词的语义的特定维度，其中可以间接推断出目标词的意义。最后，我们的算法应用RNN以人类可读的形式生成目标词的文本定义，这使得能够直接解释相应的词嵌入。本文还介绍了一个大而高质量的上下文定义数据集，它由感知定义和每个多义词的多个例句组成，这是定义建模和词义消歧的宝贵资源。进行的实验表明，在BLEU评分和人体评价测试中表现出色。

##### URL
[http://arxiv.org/abs/1809.03348](http://arxiv.org/abs/1809.03348)

##### PDF
[http://arxiv.org/pdf/1809.03348](http://arxiv.org/pdf/1809.03348)

