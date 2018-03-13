---
layout: post
title: "Knowledge Aided Consistency for Weakly Supervised Phrase Grounding"
date: 2018-03-11 02:00:24
categories: arXiv_CV
tags: arXiv_CV Knowledge Weakly_Supervised Optimization
author: Kan Chen, Jiyang Gao, Ram Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Given a natural language query, a phrase grounding system aims to localize mentioned objects in an image. In weakly supervised scenario, mapping between image regions (i.e., proposals) and language is not available in the training set. Previous methods address this deficiency by training a grounding system via learning to reconstruct language information contained in input queries from predicted proposals. However, the optimization is solely guided by the reconstruction loss from the language modality, and ignores rich visual information contained in proposals and useful cues from external knowledge. In this paper, we explore the consistency contained in both visual and language modalities, and leverage complementary external knowledge to facilitate weakly supervised grounding. We propose a novel Knowledge Aided Consistency Network (KAC Net) which is optimized by reconstructing input query and proposal's information. To leverage complementary knowledge contained in the visual features, we introduce a Knowledge Based Pooling (KBP) gate to focus on query-related proposals. Experiments show that KAC Net provides a significant improvement on two popular datasets.

##### Abstract (translated by Google)
给定自然语言查询，短语接地系统旨在将图像中提及的对象本地化。在弱监督的情况下，图像区域（即提议）与语言之间的映射在训练集中不可用。之前的方法通过学习重建预测提议的输入查询中包含的语言信息来训练接地系统来解决此缺陷。然而，这种优化仅仅受到语言形式造成的重建损失的指导，并且忽略了来自外部知识的提案中包含的丰富的视觉信息和有用的线索。在本文中，我们探讨视觉和语言模式中包含的一致性，并利用互补的外部知识来促进弱监督接地。我们提出了一种新的知识辅助一致性网络（KAC Net），它通过重构输入查询和提议信息进行优化。为了利用视觉特征中包含的互补知识，我们引入了基于知识库（KBP）的大门，专注于查询相关的提案。实验表明，KAC Net在两个流行数据集上提供了重大改进。

##### URL
[https://arxiv.org/abs/1803.03879](https://arxiv.org/abs/1803.03879)

##### PDF
[https://arxiv.org/pdf/1803.03879](https://arxiv.org/pdf/1803.03879)

