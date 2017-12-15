---
layout: post
title: "Efficient Parallel Learning of Word2Vec"
date: 2016-06-24 20:05:53
categories: arXiv_CL
tags: arXiv_CL Embedding Language_Model
author: Jeroen B.P. Vuurens, Carsten Eickhoff, Arjen P. de Vries
mathjax: true
---

* content
{:toc}

##### Abstract
Since its introduction, Word2Vec and its variants are widely used to learn semantics-preserving representations of words or entities in an embedding space, which can be used to produce state-of-art results for various Natural Language Processing tasks. Existing implementations aim to learn efficiently by running multiple threads in parallel while operating on a single model in shared memory, ignoring incidental memory update collisions. We show that these collisions can degrade the efficiency of parallel learning, and propose a straightforward caching strategy that improves the efficiency by a factor of 4.

##### Abstract (translated by Google)
自推出以来，Word2Vec及其变体被广泛用于在嵌入空间中学习保留语义或表示实体的单词或实体的表示，可用于生成各种自然语言处理任务的最新结果。现有的实现旨在通过在共享内存中的单个模型上并行运行多个线程来有效学习，而忽略偶然的内存更新冲突。我们证明这些冲突会降低并行学习的效率，并提出一个简单的缓存策略，将效率提高4倍。

##### URL
[https://arxiv.org/abs/1606.07822](https://arxiv.org/abs/1606.07822)

##### PDF
[https://arxiv.org/pdf/1606.07822](https://arxiv.org/pdf/1606.07822)

