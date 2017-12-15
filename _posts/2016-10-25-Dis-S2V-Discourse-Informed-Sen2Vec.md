---
layout: post
title: "Dis-S2V: Discourse Informed Sen2Vec"
date: 2016-10-25 20:19:35
categories: arXiv_CL
tags: arXiv_CL Relation
author: Tanay Kumar Saha, Shafiq Joty, Naeemul Hassan, Mohammad Al Hasan
mathjax: true
---

* content
{:toc}

##### Abstract
Vector representation of sentences is important for many text processing tasks that involve clustering, classifying, or ranking sentences. Recently, distributed representation of sentences learned by neural models from unlabeled data has been shown to outperform the traditional bag-of-words representation. However, most of these learning methods consider only the content of a sentence and disregard the relations among sentences in a discourse by and large. In this paper, we propose a series of novel models for learning latent representations of sentences (Sen2Vec) that consider the content of a sentence as well as inter-sentence relations. We first represent the inter-sentence relations with a language network and then use the network to induce contextual information into the content-based Sen2Vec models. Two different approaches are introduced to exploit the information in the network. Our first approach retrofits (already trained) Sen2Vec vectors with respect to the network in two different ways: (1) using the adjacency relations of a node, and (2) using a stochastic sampling method which is more flexible in sampling neighbors of a node. The second approach uses a regularizer to encode the information in the network into the existing Sen2Vec model. Experimental results show that our proposed models outperform existing methods in three fundamental information system tasks demonstrating the effectiveness of our approach. The models leverage the computational power of multi-core CPUs to achieve fine-grained computational efficiency. We make our code publicly available upon acceptance.

##### Abstract (translated by Google)
句子的矢量表示对许多涉及聚类，分类或排列句子的文本处理任务都很重要。最近，由未标记数据的神经模型学习的句子的分布表示已经被证明超过了传统的词袋表示。然而，这些学习方法大多只考虑句子的内容，忽视语篇中句子之间的关系。在本文中，我们提出了一系列用于学习句子潜在表示的新模型（Sen2Vec），它们考虑了句子的内容以及句子间的关系。我们首先用一个语言网络来表示句子间的关系，然后利用网络将语境信息引入基于内容的Sen2Vec模型。引入了两种不同的方法来利用网络中的信息。我们的第一种方法是以两种不同的方式对已经训练好的Sen2Vec向量进行网络相对于网络的改造：（1）使用节点的邻接关系;（2）使用随机采样方法，对节点的邻居进行采样。第二种方法是使用正规化器将网络中的信息编码到现有的Sen2Vec模型中。实验结果表明，我们提出的模型在三个基本的信息系统任务中胜过现有的方法，证明了我们的方法的有效性。这些模型利用多核CPU的计算能力来实现细粒度的计算效率。我们在接受之后公开提供我们的代码。

##### URL
[https://arxiv.org/abs/1610.08078](https://arxiv.org/abs/1610.08078)

##### PDF
[https://arxiv.org/pdf/1610.08078](https://arxiv.org/pdf/1610.08078)

