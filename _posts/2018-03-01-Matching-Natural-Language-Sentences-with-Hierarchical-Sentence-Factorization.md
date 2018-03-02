---
layout: post
title: "Matching Natural Language Sentences with Hierarchical Sentence Factorization"
date: 2018-03-01 02:48:47
categories: arXiv_CL
tags: arXiv_CL CNN RNN Classification Deep_Learning Relation
author: Bang Liu, Ting Zhang, Fred X. Han, Di Niu, Kunfeng Lai, Yu Xu
mathjax: true
---

* content
{:toc}

##### Abstract
Semantic matching of natural language sentences or identifying the relationship between two sentences is a core research problem underlying many natural language tasks. Depending on whether training data is available, prior research has proposed both unsupervised distance-based schemes and supervised deep learning schemes for sentence matching. However, previous approaches either omit or fail to fully utilize the ordered, hierarchical, and flexible structures of language objects, as well as the interactions between them. In this paper, we propose Hierarchical Sentence Factorization---a technique to factorize a sentence into a hierarchical representation, with the components at each different scale reordered into a "predicate-argument" form. The proposed sentence factorization technique leads to the invention of: 1) a new unsupervised distance metric which calculates the semantic distance between a pair of text snippets by solving a penalized optimal transport problem while preserving the logical relationship of words in the reordered sentences, and 2) new multi-scale deep learning models for supervised semantic training, based on factorized sentence hierarchies. We apply our techniques to text-pair similarity estimation and text-pair relationship classification tasks, based on multiple datasets such as STSbenchmark, the Microsoft Research paraphrase identification (MSRP) dataset, the SICK dataset, etc. Extensive experiments show that the proposed hierarchical sentence factorization can be used to significantly improve the performance of existing unsupervised distance-based metrics as well as multiple supervised deep learning models based on the convolutional neural network (CNN) and long short-term memory (LSTM).

##### Abstract (translated by Google)
自然语言句子的语义匹配或识别两个句子之间的关系是许多自然语言任务的核心研究问题。取决于训练数据是否可用，先前的研究已经提出了无监督的基于距离的方案和用于句子匹配的有监督的深度学习方案。然而，以前的方法要么忽略要么不能完全利用语言对象的有序，层次结构和灵活结构，以及它们之间的相互作用。在本文中，我们提出了分层句子因式分解 - 一种将句子分解为分层表示的技术，其中每个不同尺度的分量重新排列为“谓词参数”形式。所提出的句子分解技术导致了以下发明：1）新的无监督距离度量，其通过求解惩罚性最优传输问题来计算一对文本片段之间的语义距离，同时保留重新排序的句子中的单词的逻辑关系，以及2 ）基于分解式句子层次结构的监督语义训练的新型多尺度深度学习模型。基于多种数据集，如STSbenchmark，Microsoft Research复述识别（MSRP）数据集，SICK数据集等，我们将这些技术应用于文本对相似度估计和文本对关系分类任务。大量实验表明，因式分解可用于显着提高现有无监督距离度量的性能，以及基于卷积神经网络（CNN）和长期短期记忆（LSTM）的多监督深度学习模型。

##### URL
[https://arxiv.org/abs/1803.00179](https://arxiv.org/abs/1803.00179)

##### PDF
[https://arxiv.org/pdf/1803.00179](https://arxiv.org/pdf/1803.00179)

