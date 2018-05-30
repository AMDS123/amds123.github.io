---
layout: post
title: "Unsupervised Alignment of Embeddings with Wasserstein Procrustes"
date: 2018-05-29 02:35:15
categories: arXiv_CL
tags: arXiv_CL Adversarial OCR Embedding Optimization
author: Edouard Grave, Armand Joulin, Quentin Berthet
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the task of aligning two sets of points in high dimension, which has many applications in natural language processing and computer vision. As an example, it was recently shown that it is possible to infer a bilingual lexicon, without supervised data, by aligning word embeddings trained on monolingual data. These recent advances are based on adversarial training to learn the mapping between the two embeddings. In this paper, we propose to use an alternative formulation, based on the joint estimation of an orthogonal matrix and a permutation matrix. While this problem is not convex, we propose to initialize our optimization algorithm by using a convex relaxation, traditionally considered for the graph isomorphism problem. We propose a stochastic algorithm to minimize our cost function on large scale problems. Finally, we evaluate our method on the problem of unsupervised word translation, by aligning word embeddings trained on monolingual data. On this task, our method obtains state of the art results, while requiring less computational resources than competing approaches.

##### Abstract (translated by Google)
我们考虑在高维上对齐两组点的任务，这在自然语言处理和计算机视觉方面有很多应用。作为一个例子，最近表明，可以通过对准在单语数据上训练的单词嵌入来推断双语词典，而不用监督数据。这些最近的进展基于对抗训练来学习两种嵌入之间的映射。在本文中，我们建议使用基于正交矩阵和置换矩阵的联合估计的替代公式。虽然这个问题不是凸的，但我们建议通过使用凸松弛来初始化我们的优化算法，传统上考虑用于图同构问题。我们提出了一个随机算法来最大限度地减少大规模问题的成本函数。最后，我们通过调整单语数据上训练的单词嵌入来评估我们的无监督词汇翻译问题的方法。在这个任务上，我们的方法获得了最先进的结果，同时比竞争方法需要更少的计算资源。

##### URL
[http://arxiv.org/abs/1805.11222](http://arxiv.org/abs/1805.11222)

##### PDF
[http://arxiv.org/pdf/1805.11222](http://arxiv.org/pdf/1805.11222)

