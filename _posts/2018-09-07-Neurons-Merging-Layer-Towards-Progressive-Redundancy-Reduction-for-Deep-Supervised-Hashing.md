---
layout: post
title: "Neurons Merging Layer: Towards Progressive Redundancy Reduction for Deep Supervised Hashing"
date: 2018-09-07 04:10:47
categories: arXiv_CV
tags: arXiv_CV Optimization Relation
author: Chaoyou Fu, Liangchen Song, Xiang Wu, Guoli Wang, Ran He
mathjax: true
---

* content
{:toc}

##### Abstract
Deep supervised hashing has become an active topic in web search and information retrieval. It generates hashing bits by the output neurons of a deep hashing network. During binary discretization, there often exists much redundancy among hashing bits that degenerates retrieval performance in terms of both storage and accuracy. This paper formulates the redundancy problem in deep supervised hashing as a graph learning problem and proposes a novel layer, named Neurons Merging Layer (NMLayer). The NMLayer constructs a graph to model the adjacency relationship among different neurons. Specifically, it learns the relationship by the defined active and frozen phases. According to the learned relationship, the NMLayer merges the redundant neurons together to balance the importance of each output neuron. Based on the NMLayer, we further propose a progressive optimization strategy for training a deep hashing network. That is, multiple NMLayers are progressively trained to learn a more compact hashing code from a long redundant code. Extensive experiments on four datasets demonstrate that our proposed method outperforms state-of-the-art hashing methods.

##### Abstract (translated by Google)
深度监督哈希已经成为网络搜索和信息检索的一个活跃话题。它通过深度哈希网络的输出神经元生成散列位。在二进制离散化期间，散列位之间经常存在很多冗余，这使得在存储和准确性方面退化检索性能。本文将深度监督哈希中的冗余问题表示为图学习问题，并提出了一个名为神经元合并层（NMLayer）的新层。 NMLayer构造一个图来模拟不同神经元之间的邻接关系。具体而言，它通过定义的活动和冻结阶段来学习关系。根据所学习的关系，NMLayer将冗余神经元合并在一起以平衡每个输出神经元的重要性。基于NMLayer，我们进一步提出了一种用于训练深度哈希网络的渐进式优化策略。也就是说，逐步训练多个NMLayer以从长冗余代码中学习更紧凑的散列代码。对四个数据集的大量实验表明，我们提出的方法优于最先进的散列方法。

##### URL
[http://arxiv.org/abs/1809.02302](http://arxiv.org/abs/1809.02302)

##### PDF
[http://arxiv.org/pdf/1809.02302](http://arxiv.org/pdf/1809.02302)

