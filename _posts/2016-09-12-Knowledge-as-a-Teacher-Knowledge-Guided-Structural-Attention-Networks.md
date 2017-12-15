---
layout: post
title: "Knowledge as a Teacher: Knowledge-Guided Structural Attention Networks"
date: 2016-09-12 07:29:59
categories: arXiv_CL
tags: arXiv_CL Salient Knowledge Attention RNN
author: Yun-Nung Chen, Dilek Hakkani-Tur, Gokhan Tur, Asli Celikyilmaz, Jianfeng Gao, Li Deng
mathjax: true
---

* content
{:toc}

##### Abstract
Natural language understanding (NLU) is a core component of a spoken dialogue system. Recently recurrent neural networks (RNN) obtained strong results on NLU due to their superior ability of preserving sequential information over time. Traditionally, the NLU module tags semantic slots for utterances considering their flat structures, as the underlying RNN structure is a linear chain. However, natural language exhibits linguistic properties that provide rich, structured information for better understanding. This paper introduces a novel model, knowledge-guided structural attention networks (K-SAN), a generalization of RNN to additionally incorporate non-flat network topologies guided by prior knowledge. There are two characteristics: 1) important substructures can be captured from small training data, allowing the model to generalize to previously unseen test data; 2) the model automatically figures out the salient substructures that are essential to predict the semantic tags of the given sentences, so that the understanding performance can be improved. The experiments on the benchmark Air Travel Information System (ATIS) data show that the proposed K-SAN architecture can effectively extract salient knowledge from substructures with an attention mechanism, and outperform the performance of the state-of-the-art neural network based frameworks.

##### Abstract (translated by Google)
自然语言理解（NLU）是口语对话系统的核心组成部分。最近，递归神经网络（RNN）在NLU上获得了强大的结果，因为它们具有优良的保持时间序列信息的能力。传统上，NLU模块考虑到它们的扁平结构而标记话语的语义槽，因为底层RNN结构是线性链。然而，自然语言展现了语言特性，为更好地理解提供了丰富的结构化信息。本文引入了一种新的模型 - 知识引导结构关注网络（K-SAN），将RNN推广到另外引入先验知识指导下的非平坦网络拓扑。有两个特点：1）可以从小的训练数据中获取重要的子结构，使模型能够推广到以前看不见的测试数据; 2）模型自动计算出预测给定句子语义标签所必需的显着子结构，从而提高理解性能。基于空中旅行信息系统（ATIS）数据的实验表明，提出的K-SAN架构可以有效地从子结构中提取关注机制的显着知识，并且胜过基于最新技术的神经网络框架的性能。

##### URL
[https://arxiv.org/abs/1609.03286](https://arxiv.org/abs/1609.03286)

##### PDF
[https://arxiv.org/pdf/1609.03286](https://arxiv.org/pdf/1609.03286)

